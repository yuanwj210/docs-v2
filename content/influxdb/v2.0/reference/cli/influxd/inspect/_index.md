---
title: influxd inspect
description: The `influxd inspect` commands and subcommands inspecting on-disk InfluxDB time series data.
influxdb/v2.0/tags: [inspect]
menu:
  influxdb_2_0_ref:
    parent: influxd
weight: 201
aliases:
  - /v2.0/reference/cli/influxd/inspect/
products: [oss]
---

The `influxd inspect` commands and subcommands inspecting on-disk InfluxDB time series data.

## Usage
```sh
influxd inspect [subcommand]
```

## Subcommands
| Subcommand                                                                     | Description                           |
|:----------                                                                     |:-----------                           |
| [build-tsi](/v2.0/reference/cli/influxd/inspect/build-tsi/)                    | Rebuild the TSI index and series file |
| [compact-series-file](/v2.0/reference/cli/influxd/inspect/compact-series-file) | Compact the series file               |
| [dump-tsi](/v2.0/reference/cli/influxd/inspect/dump-tsi/)                      | Output low level TSI information      |
| [dumpwal](/v2.0/reference/cli/influxd/inspect/dumpwal/)                        | Output TSM data from WAL files        |
| [export-blocks](/v2.0/reference/cli/influxd/inspect/export-blocks/)            | Export block data                     |
| [export-index](/v2.0/reference/cli/influxd/inspect/export-index/)              | Export TSI index data                 |
| [report-tsi](/v2.0/reference/cli/influxd/inspect/report-tsi/)                  | Report the cardinality of TSI files   |
| [report-tsm](/v2.0/reference/cli/influxd/inspect/report-tsm/)                  | Run TSM report                        |
| [verify-seriesfile](/v2.0/reference/cli/influxd/inspect/verify-seriesfile/)    | Verify the integrity of series files  |
| [verify-tsm](/v2.0/reference/cli/influxd/inspect/verify-tsm/)                  | Check the consistency of TSM files    |
| [verify-wal](/v2.0/reference/cli/influxd/inspect/verify-wal/)                  | Check for corrupt WAL files           |

## Flags
| Flag |          | Description                    |
|:---- |:---      |:-----------                    |
| `-h` | `--help` | Help for the `inspect` command |