### Itella mapping

Dependencies:
- Leaflet 1.0+

Integrated plugins:
- Leaflet.markercluster
- Leaflet-active-area

Include dependencies before using itella-mapping.js

MarkerCluster css files not included (should be used from CDN or downloaded).

```html
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" />
<link rel="stylesheet" href="https://unpkg.com/leaflet.markercluster@1.4.1/dist/MarkerCluster.css" />
<link rel="stylesheet" href="https://unpkg.com/leaflet.markercluster@1.4.1/dist/MarkerCluster.Default.css" />

<script src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
```

### Testing

```
npm install
npm start
```
Starts local server usually at localhost:8080 and watches for changes in src folder

### Building itella-mapping.js

```
npm install
npm run build
```
This will create both css and js files in dist folder (src/images is needed as well).