# Tourism · Interactive Trip Maps

[中文](#中文) · [English](#english)

一个用于集中保存和发布互动旅行地图的 GitHub Pages 仓库。每份行程都以适合手机浏览的网页呈现，整合每日时间线、目的地点位、交通方式、住宿、活动与费用信息。

A GitHub Pages collection for interactive trip maps. Each itinerary is published as a mobile-friendly webpage combining a daily timeline, mapped destinations, transport, accommodation, activities, and recorded costs.

> Live site / 在线网站: **[f-yuan303.github.io/Tourism](https://f-yuan303.github.io/Tourism/)**

---

## 中文

### 项目简介

`Tourism` 是个人旅行计划的长期归档与发布仓库。网页采用互动地图与每日时间线相结合的方式，让行程在电脑和手机上都能快速查看。后续新增的旅行计划会继续收录在本仓库中，并在下表中提供独立链接和目的地简介。

### 旅行网页

| 行程 | 日期 | 目的地与路线 | 网页 |
|---|---|---|---|
| 新西兰南岛行程 | 11 月 27 日–12 月 5 日，共 9 天 | 皇后镇 → 格林诺奇 → 但尼丁 → 克伦威尔 → 瓦纳卡 → 普卡基湖 → Twizel → 库克山国家公园 → 特卡波 → 基督城。行程涵盖湖泊与山地风景、快艇、滑翔伞、Skyline、射击体验、冰川直升机徒步、观星和野生动物园。 | **[打开互动地图](https://f-yuan303.github.io/Tourism/)** |

### 页面功能

- 按天切换的行程时间线
- 互动地图、路线连线与地点标记
- 景点、餐饮、住宿和交通分类
- 活动费用与已预订信息
- 地图导航入口
- 面向手机屏幕优化的响应式界面

### 制作工具

本项目的互动行程页面使用 **[Trip Map Builder](https://github.com/hiyeshu/trip-map-builder)** skill 制作。该 skill 提供从行程信息整理、目的地研究到生成移动端互动地图页面的一体化流程，默认使用 Leaflet 地图和时间线式界面，也支持继续扩展预约、导航及旅行内容链接。

### 仓库结构

```text
Tourism/
├── index.html    # 当前的新西兰南岛互动行程
└── README.md     # 中英文项目说明与网页目录
```

未来新增行程时，会为每份网页保留独立路径，并同步更新本 README 中的旅行网页目录。

---

## English

### About

`Tourism` is a long-term collection for publishing personal travel plans. It combines interactive maps with day-by-day timelines so itineraries remain easy to consult on both desktop and mobile. Future trips will be added to this repository with their own page links and destination summaries in the directory below.

### Trip Pages

| Trip | Dates | Destinations and Route | Page |
|---|---|---|---|
| New Zealand South Island | Nov 27–Dec 5 · 9 days | Queenstown → Glenorchy → Dunedin → Cromwell → Wānaka → Lake Pūkaki → Twizel → Aoraki / Mount Cook National Park → Lake Tekapo → Christchurch. Highlights include alpine and lake scenery, jet boating, paragliding, Skyline Queenstown, a shooting experience, a glacier heli-hike, stargazing, and a wildlife park. | **[Open interactive map](https://f-yuan303.github.io/Tourism/)** |

### Features

- Day-by-day itinerary navigation
- Interactive maps, route lines, and location markers
- Categorised sights, dining, accommodation, and transport
- Activity costs and booking notes
- Quick map-navigation links
- Responsive, mobile-first presentation

### Built With

The interactive itinerary was created with the **[Trip Map Builder](https://github.com/hiyeshu/trip-map-builder)** skill. It supports an end-to-end workflow—from structuring trip inputs and researching destinations to generating a mobile-first Leaflet map with a timeline interface—and can be extended with reservation, navigation, and travel-content links.

### Repository Structure

```text
Tourism/
├── index.html    # Current New Zealand South Island trip map
└── README.md     # Bilingual project guide and page directory
```

As new trips are added, each page will receive its own path and this README directory will be updated with the new destination and link.

---

## Links

- **Live site:** https://f-yuan303.github.io/Tourism/
- **Repository:** https://github.com/F-Yuan303/Tourism
- **Trip Map Builder skill:** https://github.com/hiyeshu/trip-map-builder

