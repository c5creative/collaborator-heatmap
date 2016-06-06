# collaborator-heatmap
Generate Leaflet-based heatmap from collaborator-location data.

## Underlying data
Input data is geolocation (lat, long) and frequency, stored as JSON array. This data came out of a SQL database, was massaged in Excel,
exported to CSV, and then converted to JSON array via http://www.convertcsv.com/csv-to-json.htm.

## Usage
Replace the data with yours, and tweak the underlying map parameters in heatmap.html.

## Example output
![collaborator map image](https://raw.githubusercontent.com/c5creative/collaborator-heatmap/master/images/collaborator-heatmap.png)
