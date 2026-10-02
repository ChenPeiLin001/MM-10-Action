# MM-10-Action
MM-10-Action is an open source dataset for human activity recognition(HAR) based on millimeter wave radar(mmwave radar). This dataset is in the form of raw data and time-doppler map.

The dataset will made available when our paper is accepted. Look forward to your attention.--2025.03.06

## News
**[2026-10-02]** The time-doppler map data (TDMs) of MM-10-Action is now publicly available on ModelScope!

## Dataset Availability
The **TDMs (Time-Doppler Maps)** data is now available on ModelScope:

- **ModelScope**: [dugujiujian/tdms-data](https://www.modelscope.cn/datasets/dugujiujian/tdms-data)

### TDMs-data Contents
The TDMs-data repository contains the time-doppler map data of MM-10-Action:

| File / Directory | Description |
| --- | --- |
| `data_ex1_time_doppler.npz` | Time-doppler map data (experiment 1) |
| `data_ex2_time_doppler.npz` | Time-doppler map data (experiment 2) |
| `data_ex3_time_doppler.npz` | Time-doppler map data (experiment 3) |
| `data_ex*_all_png_path.json` | Path index of the time-doppler map images |
| `data_ex*_time_doppler/` | Time-doppler map images (PNG) |

### Download
Download via ModelScope website or SDK:

```bash
# via modelscope SDK
from modelscope.msdatasets import MsDataset
ds = MsDataset.load('dugujiujian/tdms-data', subset_name='default', split='train')

# via git
git clone https://www.modelscope.cn/datasets/dugujiujian/tdms-data.git
```
