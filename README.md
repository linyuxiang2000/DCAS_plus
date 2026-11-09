# DCAS++: A small object detection method for traffic scenes integrating four-scale high-resolution detection and object-aware dynamic aggregation

<div align=center>
<img src="./ultralytics/assets/VisDrone_mAP_Params.png" alt="VisDrone_mAP_Params" width = "549" />
</div>


## <div align="center">Documentation</div>

### Benchmark
| **Model**     | **Datasets** |  **mAP@0.5<sup>val**  | **mAP@0.5:0.95<sup>val** | **Params** | **Weight**                                                                                           |
|:-------------:|:------------:|:---------------------:|:------------------------:|:----------:|:----------------------------------------------------------------------------------------------------:|
| YOLOv8s       | VisDrone     |         33.1%         |          18.9%           | 11.1M      | [Download](https://pan.baidu.com/s/1fvyu_ZMK8CFsWPI69ClVKA?pwd=m5ja) |
| DCAS++  | VisDrone     |         39.8%         |          23.4%           | 5.5M      | [Download](https://pan.baidu.com/s/1ZR0aqnQ-pTGmIP8uOZ06KQ?pwd=ptb8) |
| YOLOv8s       | BDD100K      |         53.6%         |          31.1%           | 11.1M      | [Download](https://pan.baidu.com/s/1pdX5B97T1_Jlz33e3JKkBA?pwd=2hqz) |
| DCAS++ | BDD100K      |         58.1%         |          34.4%           | 5.5M      | [Download](https://pan.baidu.com/s/10kP0swizT-FPApCVp4vxAQ?pwd=b5v9) |
| YOLOv8s       | TT100K       |         85.4%         |          65.4%           | 11.1M      | [Download](https://pan.baidu.com/s/1aVF3kHTi06_0vQlTT7pJhg?pwd=mb9p) |
| DCAS++  | TT100K       |         94.9%         |          72.8%           | 5.5M      | [Download](https://pan.baidu.com/s/1FlDthdsDCMxwh88Xc8smcw?pwd=hsr6) |

### Data download
Note that all data has been cleaned and converted to YOLO format labels.
- VisDrone (1.81 GB): [GoogleDrive](https://drive.google.com/file/d/18rZfHuRK40nH43iVbLOd95h6Yv6BoKKl/view?usp=sharing)
- BDD100K (4.25 GB): [GoogleDrive](https://drive.google.com/file/d/1-ghEyaWKQ1lna4kcxXrUKfAAZygpMlh0/view?usp=sharing)
- TT100K (8.74 GB): [GoogleDrive](https://drive.google.com/file/d/10V2pUSmd6nzD5Cs9o0E_4IUfRjVYr6RK/view?usp=sharing)

## Acknowledgement
The code implementation is based on [YOLOv8](https://github.com/ultralytics/ultralytics) and [DCAS](https://github.com/crafly/DCAS), thanks to their open-source code.
The data is based on the [VisDrone](https://github.com/VisDrone/VisDrone-Dataset), [BDD100K](https://www.vis.xyz/bdd100k/), and [TT100K](https://cg.cs.tsinghua.edu.cn/traffic-sign/) datasets, thanks to their open-source data.
