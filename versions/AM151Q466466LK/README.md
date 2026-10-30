<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.51″ AMOLED 显示屏 466×466（AM151Q466466LK）</h1>

<p align="center"><b>AMOLED 模组 · QSPI · CO5300AF-42</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: CO5300AF-42" src="https://img.shields.io/badge/Driver-CO5300AF--42-E7352C?style=flat-square" />
  <img alt="Touch: CST820" src="https://img.shields.io/badge/Touch-CST820-F39C12?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.51 寸 466×466 AMOLED 模组宣传图" src="./images/PNG-1.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.51 英寸 |
| 类型 | AMOLED |
| 分辨率 | 466×466 |
| 外形尺寸 | 44.30 x 44.30 mm |
| 有效显示区域 | 38.31 x 38.31 mm |
| 接口 | QSPI |
| 驱动 IC | CO5300AF-42 |
| 触摸驱动 | CST820 |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf`](./datasheets/CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf) |
| 规格文档 | [`DS_CST_820_V1_2_e0543732ca.pdf`](./datasheets/DS_CST_820_V1_2_e0543732ca.pdf) |
| 规格文档 | [`AM151Q466466LK.pdf`](./datasheets/AM151Q466466LK.pdf) |
| CAD 图纸 | [`OK-14F024-04.pdf`](./cad/OK-14F024-04.pdf) |
| 转接板资料 | [`PCB-1.51寸AMOLED屏转接板.pdf`](./adapter/PCB-1.51%E5%AF%B8AMOLED%E5%B1%8F%E8%BD%AC%E6%8E%A5%E6%9D%BF.pdf) |

## 仓库结构

```text
display-amoled-1.51inch-466x466/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── AM151Q466466LK/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        └── adapter/          # 转接板资料 + 转接板图片
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
