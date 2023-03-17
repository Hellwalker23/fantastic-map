//ES6
npm install --save svgmap

//npm install --save svgmap
import svgMap from 'svgmap';
import 'svgmap/dist/svgMap.min.css';

//CDN
<script src="https://cdn.jsdelivr.net/npm/svg-pan-zoom@3.6.1/dist/svg-pan-zoom.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/StephanWagner/svgMap@v2.10.1/dist/svgMap.min.js"></script>
<link href="https://cdn.jsdelivr.net/gh/StephanWagner/svgMap@v2.10.1/dist/svgMap.min.css" rel="stylesheet">

//Create an HTML element where to show your map, then use JavaScript to initialize:
<div id="svgMap"></div>

//<div id="svgMap"></div>
new svgMap({
  targetElementID: 'svgMap',
  data: {
    data: {
      gdp: {
        name: 'GDP per capita',
        format: '{0} USD',
        thousandSeparator: ',',
        thresholdMax: 50000,
        thresholdMin: 1000
      },
      change: {
        name: 'Change to year before',
        format: '{0} %'
      }
    },
    applyData: 'gdp',
    values: {
      AF: { gdp: 587, change: 4.73 },
      AL: { gdp://ES6
npm install --save svgmap

//npm install --save svgmap
import svgMap from 'svgmap';
import 'svgmap/dist/svgMap.min.css';

//CDN
<script src="https://cdn.jsdelivr.net/npm/svg-pan-zoom@3.6.1/dist/svg-pan-zoom.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/StephanWagner/svgMap@v2.10.1/dist/svgMap.min.js"></script>
<link href="https://cdn.jsdelivr.net/gh/StephanWagner/svgMap@v2.10.1/dist/svgMap.min.css" rel="stylesheet">

//Create an HTML element where to show your map, then use JavaScript to initialize:
<div id="svgMap"></div>

//<div id="svgMap"></div>
new svgMap({
  targetElementID: 'svgMap',
  data: {
    data: {
      gdp: {
        name: 'GDP per capita',
        format: '{0} USD',
        thousandSeparator: ',',
        thresholdMax: 50000,
        thresholdMin: 1000
      },
      change: {
        name: 'Change to year before',
        format: '{0} %'
      }
    },
    applyData: 'gdp',
    values: {
      AF: { gdp: 587, change: 4.73 },
      AL: { gdp: 4583, change: 11.09 },
      DZ: { gdp: 4293, change: 10.01 }
      // ...
    }
  }
}); 4583, change: 11.09 },
      DZ: { //ES6
npm install --save svgmap

//npm install --save svgmap
import svgMap from 'svgmap';
import 'svgmap/dist/svgMap.min.css';

//CDN
<script src="https://cdn.jsdelivr.net/npm/svg-pan-zoom@3.6.1/dist/svg-pan-zoom.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/StephanWagner/svgMap@v2.10.1/dist/svgMap.min.js"></script>
<link href="https://cdn.jsdelivr.net/gh/StephanWagner/svgMap@v2.10.1/dist/svgMap.min.css" rel="stylesheet">

//Create an HTML element where to show your map, then use JavaScript to initialize:
<div id="svgMap"></div>

//<div id="svgMap"></div>
new svgMap({
  targetElementID: 'svgMap',
  data: {
    data: {
      gdp: {
        name: 'GDP per capita',
        format: '{0} USD',
        thousandSeparator: ',',
        thresholdMax: 50000,
        thresholdMin: 1000
      },
      change: {
        name: 'Change to year before',
        format: '{0} %'
      }
    },
    applyData: 'gdp',
    values: {
      AF: { gdp: 587, change: 4.73 },
      AL: { gdp: 4583, change: 11.09 },
      DZ: { gdp: 4293, change: 10.01 }
      // ...
    }
  }
}); 4583, change: 11.09 },
      DZ: { gdp: 4293, change: 10.01 }
      // ...
    }
  }
});gdp: 4293, change: 10.01 }
      // ...
    }
  }
});
