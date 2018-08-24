# heatboard.js

heatboard.js is a fork of oakmacs [chessboard.js](https://github.com/oakmac/chessboardjs) with added heat map functionality.
heatboard.js is a JavaScript chessboard component. It depends on [jQuery].

Please see [chessboardjs.com] for basic usage.

## New functions in heatboard.js

```javascript
require('heatboard');
let map = []; // 8x8 array
let min = 2;
let max = 100;
let color = [255, 0, 0];
let unit = '%';

// for single data heatmap (only positive values)
chessboard.drawHeatmap(map, min, max, color, unit);

// for comparison heatmap (positive and negative values)
chessboard.drawComparisonHeatmap(map, min, max);
```
