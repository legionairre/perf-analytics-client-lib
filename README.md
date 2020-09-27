PerfAnalytics.JS is a client-side library, which collects some performance related key metrics from browser and sends to the PerfAnalytics.API

- This library
    - does not harm clients performance,
    - measures TTFB, FCP, Dom Load, and Window Load events
    - measures Network timings for Document, Image, Font, JS, and CSS,
    - works on all modern browsers Except Microsoft Products,
    - sends performance metrics to API in a proper way,
    - is generic and can be used in any web application, (npm install perf-analytics-gkivanc)
    - smaller than 3KB Gzip 

- This library npm [link](https://www.npmjs.com/package/perf-analytics-gkivanc)

- IMPORTANT: Before use the client-side library you should run PerfAnalytics.API
    - PerfAnalytics.API [Github](https://github.com/legionairre/perf-analytics-api)

## Available Scripts

In your project root folder,

### `npm install perf-analytics-gkivanc`

## Example Usage

You should import package in index.js file

`import 'perf-analytics-gkivanc/PerfAnalytics';`

That's it. Collect happy metrics :)
