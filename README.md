# DongY
**DongY** is a centimeter-level RGB imagery dataset collected by UAVs in Dongying, China, specifically designed for fine-scale extraction and mapping of **soil saline patches**. This dataset supports research in remote sensing, precision agriculture, land salinization monitoring, and deep learning-based semantic segmentation.

The dataset includes:

- **UAV RGB imagery**
  - `DongY_2022/` — imagery from September 28, 2022
  - `DongY_2024/` — imagery from August 29, 2024
- **Pixel-level annotations** (`.png` masks)
  - `Labels/` — manually labeled saline patch masks


## Data Format

- Images: `.tif`
- Masks: single-channel `.png`, where:
  - `0` = background (non-saline)
  - `1` = soil saline patch


**Note:** This dataset is currently under review for publication. Citation format will be provided after acceptance.
  

