# sheetmapper-d3
Mapbox's [Sheet Mapper](https://www.mapbox.com/impact-tools/sheet-mapper) using D3.js instead of Tabletop.js

Mapbox's Sheet Mapper impact tool is a quick way to: 
> Create a live-updating map that displays the locations of all of your POIs or events, powered by a simple spreadsheet.

Mapbox's [code template](https://github.com/mapbox/impact-tools/blob/1696b19fc5d3ed8872756f1a58a121293410ea4b/Sheet-Mapper-Sample-Code.html) (as of publishing this repo on May 13th, 2020) uses [Tabletop.js](https://github.com/jsoma/tabletop) to read data from a Google Sheet.

As of September 2020, Google is retiring v3 of the Sheets API and Tabletop.js will no longer work. The creator recommends using the [Papa Parse](https://www.papaparse.com/) library instead.

Given that Mapbox uses D3.js for the [Sheet Mapper Advanced](https://www.mapbox.com/impact-tools/sheet-mapper-advanced-caching) impact tool, I updated Sheet Mapper to follow suit and published this code as reference.

_NOTE:_ With the change to D3.js, this sample cannot be run directly from an HTML file on your local disk. You need to run it off a server, local or online
