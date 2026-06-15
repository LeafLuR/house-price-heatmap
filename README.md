# 🏠 70城房价数据大屏

国家统计局70个大中城市商品住宅销售价格指数数据可视化大屏。

## 数据
- **来源**: [国家统计局](https://www.stats.gov.cn/sj/zxfb/)
- **时间跨度**: 2021年7月 ~ 2026年4月 (58个月)
- **城市**: 70个大中城市
- **指标**: 新建商品住宅 / 二手住宅 → 环比/同比/定基

## 功能
- 🗺️ **中国地图热力图** — 城市涨跌一目了然
- ⏰ **时间轴播放** — 观察近5年房价变化趋势
- ⭐ **重点关注** — 杭州、大连、昆明、哈尔滨
- 📈 **趋势图** — 重点城市价格走势
- 🏆 **涨跌榜** — 每月涨跌幅排名

## 在线访问
https://leaflur.github.io/house-price-heatmap/

## 更新数据
每月国家统计局发布后,运行爬虫:
```bash
cd /path/to/repo
python3 scrape_70city.py
git add data.json && git commit -m "update data"
git push
```
