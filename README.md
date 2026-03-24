# chitty-pkg-google-cloud

Chitty Workspace marketplace package — BigQuery analytics and Cloud Storage management for Google Cloud Platform.

## Requirements

- [Chitty Workspace](https://github.com/MTPython406/Chitty-Workspace) (required)
- [Chitty SDK](https://github.com/MTPython406/chitty-sdk) (`pip install chitty-sdk`)
- [Google Cloud CLI](https://cloud.google.com/sdk/docs/install) (`gcloud`)

## Tools

| Tool | Description |
|------|-------------|
| `gcloud_bigquery` | Query, explore, and manage BigQuery datasets and tables |
| `gcloud_storage` | Upload, download, list, and manage Cloud Storage objects |

## Features

- Run SQL queries on BigQuery datasets
- Explore table schemas and row counts
- Upload/download files to Cloud Storage
- Feature flags for mutating operations (disabled by default)
- Auto-creates focused sub-agents per dataset

## Installation

Install via the Chitty Workspace Marketplace tab, or manually:

```bash
# Clone into your Chitty marketplace directory
git clone https://github.com/MTPython406/chitty-pkg-google-cloud.git \
  ~/.chitty-workspace/data/tools/marketplace/google-cloud
```

## License

MIT — see [Chitty Workspace](https://github.com/MTPython406/Chitty-Workspace) for full license.

Built by [DataVisions.ai](https://datavisions.ai) | [chitty.ai](https://chitty.ai)
