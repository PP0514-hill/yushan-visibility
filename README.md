# 玉山可見域地圖 Yushan Visibility

全台哪裡看得見玉山：以玉山主峰（3,952 m）為原點的反向視域，含地球曲率與大氣折射（k = 0.13），並結合當日天氣判定「現在看不看得到」。

- 網頁：`index.html`（單檔，Leaflet + 內嵌視域圖層）
- 天氣快照：`weather.json`（排程更新；Open-Meteo 模式預報，接上授權碼後加入中央氣象署實測與環境部 AQI）
- 地形：Copernicus DEM GLO-30 © ESA / Airbus DS；計算：GDAL `gdal_viewshed`
- 地名：OpenStreetMap contributors（ODbL）；行政區界：g0v twgeojson

初樸建築師事務所 ProtoPlain Architects
