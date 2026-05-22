# 🌤️ 5A 景区天气

一个轻量级的 5A 级景区实时天气监控页面，支持地图可视化、天气筛选和景区关注。

**在线预览：** https://rootusercc.github.io/5A-weather/

---

## 功能

| 模块 | 说明 |
|------|------|
| ⭐ 我的关注 | 收藏感兴趣的景区，快速查看天气 |
| 🏔️ 5A 级景区 | 全部 5A 景区列表，支持天气 / 时间筛选 |
| 🗺️ 全景 5A | 中国地图可视化，点击省份查看景区天气 |
| 🔍 搜索 | 搜索任意地点并添加为自定义景区 |

### 天气筛选
- ☀️ 晴 / ⛅ 多云 / 🌧️ 雨 / ❄️ 雪 / ☁️ 阴

### 时间筛选
- 今天 / 周一 ~ 周五 / 周六 / 周日 / 周末

---

## 技术栈

- HTML5 + CSS3 + Vanilla JavaScript
- [ECharts](https://echarts.apache.org/) 中国地图可视化
- [和风天气 API](https://dev.qweather.com/) 实时天气数据

---

## 本地运行

```bash
git clone https://github.com/RootUserCC/5A-weather.git
cd 5A-weather
# 直接用浏览器打开 index.html
```

> 由于调用和风天气 API，需要联网使用。

---

## 数据来源

- **景区坐标**：5A 级景区公开地理信息
- **天气数据**：和风天气开发服务

---

## 许可证

MIT
