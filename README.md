# OpenSearch Dashboards Desktop - Snap Packaging

Snap package for [OpenSearch Dashboards Desktop](https://github.com/opensearch-project/dashboards-desktop).

## Automated Build
This repository uses GitHub Actions to build the `.snap` package using `snapcore/action-build`.

## Manual Installation
Download the built `.snap` from GitHub Actions artifacts, then install with:

```bash
sudo snap install opensearch-desktop_*.snap --dangerous
```
