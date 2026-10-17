# Committed dataset

**Source dataset:** Criteo Uplift v2.1

**Selection:** Every 71st source row (starting at row 0) across all 13,979,592 records; 196,896 real observations. Systematic subset, not the complete dataset or a simple random sample.

**Data license:** [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). This applies to the data, independently of the project code.

## Sources

- https://ailab.criteo.com/criteo-uplift-prediction-dataset/
- https://huggingface.co/datasets/criteo/criteo-uplift/resolve/main/criteo-research-uplift-v2.1.csv.gz

## CSV files

| File | Rows | Bytes |
|---|---:|---:|
| [criteo_uplift_v2_1_sample.csv](raw/criteo_uplift_v2_1_sample.csv) | 196,896 | 45,748,350 |

Attribution: Eustache Diemert, Artem Betlei, Christophe Renaudin, Massih-Reza Amini / Criteo AI Lab, A Large Scale Benchmark for Uplift Modeling (2018). Original feature/treatment/outcome columns are retained. Exclude post-treatment exposure from pre-treatment modeling. Respect v2.1 sampling/design notes; observed incrementality is not the originating company's population effect. Projects 02 and 07 intentionally share this source subset but answer different questions.

The CSV files contain published observations or their documented format conversion; no training records were invented. Source formats and raw CSV exports are distinguished by the manifest. File checksums and schemas are recorded in [csv-manifest.json](csv-manifest.json).
