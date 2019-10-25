<div align="center">
  <h1>Awesome-GIS-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 GIS 技术资源。</p>
</div>

<br />

> 地理信息系统（Geographic Information System或 Geo－Information system，GIS）有时又称为“地学信息系统”。它是一种特定的十分重要的空间信息系统。它是在计算机硬、软件系统支持下，对整个或部分地球表层（包括大气层）空间中的有关地理分布数据进行采集、储存、管理、运算、分析、显示和描述的技术系统。

推荐一个其它的很棒的收藏列表，:point_right: https://github.com/sshuair/awesome-gis

## Contents

- [技术标准](#技术标准)
- [Web GIS](#web-gis)
  - [地图引擎](#地图引擎)
  - [开发工具](#开发工具)
- [其它资源](#其它资源)
  - [平台](#平台)

## 技术标准

- [OGC](http://www.opengeospatial.org/) - 开放地理空间联盟（OGC）是一个致力于为全球地理空间社区制定高质量开放标准的国际非营利组织。
- [OSGeo](https://www.osgeo.org/) - 开源空间信息基金会，一个全球性非营利性组织，目标是支持全球性的合作，建立和推广高品质的空间信息开源软件。
- [OSGeo 中国中心](https://www.osgeo.cn/) - OSGeo 中国中心是由国家遥感中心发起、Autodesk 中国有限公司协助，经 OSGeo 正式授权的非营利性组织。OSGeo 中国中心的使命是支持开源地理信息软件和遥感软件的开发以及推动其更广泛的应用，尤其是帮助中国地区的用户和开发者更好地使用 OSGeo 基金会提供的源代码、产品及服务。
- [ESRI](https://www.esri.com/) - GIS 行业巨头，ArcGIS 发布者的官网。
- [EPSG](http://www.epsg.org/) - EPSG 的维护组织 IOGP 官网。
- [EPSG.io](http://epsg.io/) - 全球坐标系统 EPSG 查询。
- [Spatial Reference](https://spatialreference.org/) - 空间参考定义查询。
- [GeoJSON Specification](https://geojson.org/) - GeoJSON 规范。[中文翻译](https://www.oschina.net/translate/geojson-spec?cmp)
- [TopoJSON Specification](https://github.com/topojson/topojson-specification) - TopoJSON 规范，是 GeoJSON 的扩展，优化了数据结构和效率。
- [Vector Tile Specification](https://github.com/mapbox/vector-tile-spec) - Mapbox 矢量瓦片规范。
- [MBTiles Specification](https://github.com/mapbox/mbtiles-spec) - MBTiles 规范。
- [UTFGrid Specification](https://github.com/mapbox/utfgrid-spec) - UTFGrid 规范。

[Go Top ↑](#awesome-gis-list)

## Web GIS

### 地图引擎

- [Leaflet](https://leafletjs.com/) - 目前最流行的、移动端优先、轻量级 Web GIS 开源框架。
  - [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw) - Leaflet 插件，矢量绘图、编辑工具，**Leaflet 官方发布**。
  - [Leaflet.fullscreen](https://github.com/Leaflet/Leaflet.fullscreen) - Leaflet 插件，地图全屏显示，**Leaflet 官方发布**。
  - [Leaflet-measure](https://github.com/ljagis/leaflet-measure) - Leaflet 插件，面积、距离测量。
  - [esri-Leaflet](https://github.com/Esri/esri-leaflet) - Leaflet 插件，用于在 Leaflet 中使用 ArcGIS 地图服务的一组轻量级 api，**ESRI 官方实现**。
  
- [Openlayers](https://openlayers.org/) - 一个开源的、高性能、功能丰富的二维地图引擎。

- [Cesium.js](https://cesiumjs.org/) - 目前最具优势的、功能丰富的开源三维地图引擎。

- [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/overview/) - 一个开源的、基于 WebGL 技术的现代化地图引擎，由 MapBox 公司进行持续维护。
  - [DECK.GL](https://deck.gl/) - 基于 Mapbox-GL 引擎，由 WebGL 驱动的大数据可视化框架，**Uber 公司发布**。
  - [React Mapbox GL](https://uber.github.io/react-map-gl/) - 基于 React.js 集成了 MapBox GL 的实现，**Uber 公司维护**。
  
- [wrld.js](https://www.wrld3d.com/) - 基于 Leaflet.js 的 WebGL 3D 地图引擎。

### 开发工具

- Utils
  - [Turf.js](http://turfjs.org/) - 一个开源的提供给浏览器和 Node.js 平台进行高级空间分析的工具库。
  - [JSTS](https://github.com/bjornharrtell/jsts) - 开源的空间分析库。
  - [proj4js](http://proj4js.org/) - proj4 的 JavaScript 实现，可进行坐标系统转换。
  - [Mapnik](https://mapnik.org/) - 地图数据可视化库。
  
- Map Server
  - [TileStache](http://tilestache.org/) - 基于 Python、Mapnik 的地图瓦片服务器。
  - [TileStrata](https://github.com/naturalatlas/tilestrata) - 基于 Node.js、Mapnik 的可插拔地图瓦片服务器。

[Go Top ↑](#awesome-gis-list)

## 其它资源

### 平台

- [ArcGIS](https://www.arcgis.com/) - GIS 行业商业巨头，其商业软件几乎为行业标准。
- [MapTiler](https://www.maptiler.com/) - 一个提供地图设计，切片的地图托管平台，官方开源。
- [OpenMapTiler](https://openmaptiles.org/) - 提供免费的自托管地图矢量瓦片数据。
- [mapshaper](https://mapshaper.org/) - 在线地图数据编辑工具，支持 Shapefile、GeoJSON、TopoJSON、DBF 和 CSV 格式。
- [mygeodata](https://mygeodata.cloud/converter/) - 在线地理数据转换工具。

[Go Top ↑](#awesome-gis-list)
