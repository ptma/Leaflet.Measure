# Leaflet.Measure 
Leaflet.Measure Is a leaflet plugin for measuring distances and areas.  

Online [DEMO](https://ptma.github.io/Leaflet.Measure/examples/measure.html).

## Example
```javascript
var map = L.map("map", {
        center: [29, 120],
    });
    
L.control.measure().addTo(map);
```

## Options
| Option | Type | Default | Description |
|--------|------|---------|-------------|
| position | String | 'topleft' | The position of the control. |
| title | String | 'Measurement' | The title of the control. |
| collapsed | Boolean | false | If true, the control will be collapsed into an icon and expanded on mouse hover or touch. |
| color | String | '#FF0080'| The color of the lines or polygons. |

### Text options
The default is in English, you can set it to the language that you want.
| Option | Type | Default | Description |
|--------|------|---------|-------------|
| linearMeasurement | String | 'Distance measurement'|  |
| areaMeasurement | String | 'Area measurement'|  |
| start | String | 'Start'|  |
| meter | String | 'm'|  |
| kilometer | String | 'km'|  |
| squareMeter | String | 'm²'|  |
| squareKilometers | String | 'km²'|  |
