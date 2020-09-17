# Leaflet.Measure 
Leaflet.Measure 是一个 Leaflet 的测量距离和面积的工具插件。  

在线 [示例](https://ptma.gitee.io/leaflet.measure/examples/measure.html).

## 用法示例
```javascript
var map = L.map("map", {
        center: [29, 120],
    });
    
L.control.measure().addTo(map);
```

## 选项
| 选项 | 类型 | 默认值 | 描述 |
|--------|------|---------|-------------|
| position | String | 'topleft' | 控件位置。 |
| title | String | 'Legend' | 控件面板的标题。 |
| collapsed | Boolean | false | 面板是否默认展开。 |
| color | String | '#FF0080'| 测量线条的颜色。 |

### 文本选项
默认为英文， 如需要可以设置为你所期望的语言文本。
| 选项 | 类型 | 默认值 | 描述 |
|--------|------|---------|-------------|
| linearMeasurement | String | 'Distance measurement'|  |
| areaMeasurement | String | 'Area measurement'|  |
| start | String | 'Start'|  |
| meter | String | 'm'|  |
| kilometer | String | 'km'|  |
| squareMeter | String | 'm²'|  |
| squareKilometers | String | 'km²'|  |
