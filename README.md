
[![GDS](../../actions/workflows/gds.yaml/badge.svg)](../../actions/workflows/gds.yaml)
[![DRC](../../actions/workflows/drc.yaml/badge.svg)](../../actions/workflows/drc.yaml)
[![LVS](../../actions/workflows/lvs.yaml/badge.svg)](../../actions/workflows/lvs.yaml)
[![DOCS](../../actions/workflows/docs.yaml/badge.svg)](../../actions/workflows/docs.yaml)

# Who

Carsten Wulff

# Why

Current Mirror

# How

Followed the tutorial


# What


| What            |        Cell/Name |
| :----              |  :----:       |
| Schematic       | design/LELO_EX_SKY130A/LELO_EX.sch |
| Layout          | design/LELO_EX_SKY130A/LELO_EX.mag |



# Signal interface


| Signal   | Direction | Domain  | Description                     |
|:---------|:---------:|:-------:|:--------------------------------|
| IBPS_5U  | Input     | VDD_1V8 | Input current, nominally 5 uA   |
| IBNS_20U | Output    | VDD_1V8 | Output current, nominally 20 uA |
| VSS      | Input     | Ground  |                                 |



# Key parameters


| Parameter           | Min     | Typ             | Max     | Unit  |
| :---                | :---:   | :---:           | :---:   | :---: |
| Technology          |         | Skywater 130 nm |         |       |
| AVDD                | 1.7     | 1.8             | 1.9     | V     |
| Temperature         | -40     | 27              | 125     | C     |
