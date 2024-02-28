# geoJSON_viewer
A Quick HTML page to show Geojson data and quick conversion code for geojson / gml files with wrong coordinate format

## How to run
1. Check if your GeoJSON file is ready to be loaded into the HTML
    1. Coordinates in EPSG 4326?
    2. if not use file data_processing to create legit geoJSON
  
2. in index.html set filepath to your geoJSON and set initial view coordinates for map
3. with terminal cd into the folder where index.html and your geojson lie
    1. run: python3 -m http.server
    2. access your html file via localhost:8000 in your browser
    3. for more infos on local test servers see https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/set_up_a_local_testing_server
