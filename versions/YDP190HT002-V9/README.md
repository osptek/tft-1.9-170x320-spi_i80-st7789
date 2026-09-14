<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.9″ TFT 170×320（ST7789V3 · SPI / I80）</h1>

<p align="center"><b>触摸 TFT · SPI / I80 · ST7789V3</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Size: 1.9 inch" src="https://img.shields.io/badge/Size-1.9%22-3498DB?style=flat-square" />
  <img alt="Resolution: 170x320" src="https://img.shields.io/badge/Resolution-170%C3%97320-8E44AD?style=flat-square" />
  <img alt="Interface: SPI / I80" src="https://img.shields.io/badge/Interface-SPI%20%2F%20I80-27AE60?style=flat-square" />
  <img alt="Driver: ST7789V3" src="https://img.shields.io/badge/Driver-ST7789V3-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.9 寸 170×320 TFT SPI / I80 模组（ST7789V3）宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [产品简介](#产品简介)
- [规格参数](#规格参数)
- [仓库结构](#仓库结构)
- [相关资料](#相关资料)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 产品简介

OSPTEK **1.9 寸 170×320 TFT** 是一款可在 **SPI** 与 **I80** 之间切换的彩色触摸显示模组，显示驱动为 **ST7789V3**。适合手持终端、穿戴与小型竖屏 HMI 等场景。同一料号、同一 LCD FPC 通过 IM 脚选择接口。

规格标识（仓库名）：`tft-1.9-170x320-spi_i80-st7789`

当前模组版本：**YDP190HT002-V9**。外形与电气细节以 [`docs/YDP190HT002-V9_外形图.pdf`](./docs/YDP190HT002-V9_外形图.pdf) 为准。

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.9 英寸 |
| 类型 | 触摸 TFT（彩色，常黑） |
| 分辨率 | 170×320 |
| 接口 | SPI / I80（IM 选择 4-wire SPI 或 8080 8-bit） |
| 驱动 IC | ST7789V3 |
| 触摸驱动 | CST816D |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 外形图为准。

## 仓库结构

```text
tft-1.9-170x320-spi_i80-st7789/                                # 仓库根（导航见 ../../README.md）
└── versions/
    └── YDP190HT002-V9/                                # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## 相关资料

### 本产品资料

| 资料 | 链接 |
| ---- | ---- |
| 外形图（YDP190HT002-V9） | [`docs/YDP190HT002-V9_外形图.pdf`](./docs/YDP190HT002-V9_外形图.pdf) |

## 购买链接

<p align="center">
  <a href="https://shop110742373.taobao.com/"><img alt="淘宝官方店铺" src="https://img.shields.io/badge/淘宝-官方店铺-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="速卖通官方店铺" src="https://img.shields.io/badge/速卖通-官方店铺-E62E04?style=for-the-badge&logo=aliexpress&logoColor=white" /></a>
</p>

**国内（淘宝）**

- 店铺：[鱼鹰光电工厂店](https://shop110742373.taobao.com/)

**海外（AliExpress）**

- 店铺：[OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

## 技术支持

- 技术支持 / 产品咨询：<luyu@osptek.com>
- QQ 技术交流群：**985881096**
- 公司官网：<https://osptek.com/>
- 有任何问题，都可以在本仓库 Issues 中提问

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
