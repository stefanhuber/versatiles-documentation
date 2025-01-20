# VersaTiles

!!! note ""
    VersaTiles is a completely FLOSS stack for generating, distributing, and using map tiles based on OpenStreetMap data, free of any commercial interests.

## Example to use our Map

```html title="Copy/Paste Example"
<!-- add MapLibre JavaScript and CSS -->
<script src="https://tiles.versatiles.org/assets/maplibre-gl/maplibre-gl.js"></script>
<link href="https://tiles.versatiles.org/assets/maplibre-gl/maplibre-gl.css" rel="stylesheet" />

<!-- add container for the map -->
<div id="map" style="width:100%;aspect-ratio:16/9"></div>

<!-- start map -->
<script>
  new maplibregl.Map({
    container: 'map',
    style: 'https://tiles.versatiles.org/assets/styles/colorful.json'
  }).addControl(new maplibregl.NavigationControl());
</script>
```

## Documentation

 - [Basics](basics/web_maps.md)
 - [Compendium](compendium/index.md)
 - [Guides](guides/deploy_in_google_cloud.md)
