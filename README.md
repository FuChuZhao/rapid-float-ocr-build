# rapid-float-ocr-build

Public GitHub Actions workflows for building/testing the private `rapid-float-ocr` source repository.

- Triggered only via `workflow_dispatch`
- Clones the private source repo via SSH deploy key
- Uploads build/test artifacts with minimal retention and deletes them after download (handled by the private repo scripts)

