# project1 documentation!

## Description

An integration of cookie-cutter and daytona

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `az storage blob upload-batch -d` to recursively sync files in `data/` up to `container1/data/`.
* `make sync_data_down` will use `az storage blob upload-batch -d` to recursively sync files from `container1/data/` to `data/`.


