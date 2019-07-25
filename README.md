# Interactive Data Visualization of Public Bus Transportation connections between bus stations in Aracaju, Brazil.

The public bus transportation network has a great importance in the routine of the major part of the inhabitants of Aracaju-SE, Brazil. However, the mobility inside the network is cloudy for those whom has no knowledge about the bus lines' routes.

<a name="tryit"></a>
### Try it now [here](https://bl.ocks.org/brunocabral/raw/828ed927fdfe83a6b64dbd9dee34ead4/0cd7b5380817168b012bc11a94a59041c1d1ac2c/)

## Folder

The main file `dataviz_mapping_aracaju.html` is in root directory.

`css/` : css files 

`data/` : JSON source data of bus public transportation

`etc/`: other files


## Source
   1. Regional public transportation data retrieved from [SMTT Aju](http://www.smttaju.com.br/smtt/transporte/itinerario-e-horario-dos-onibus) (Originally PDF Format).
   2. https://d3js.org/
   3. https://lodash.com/
   4. Credits also to some code snippets found on internet that inspired and were adapted:
      1. [Glowing effect](https://www.visualcinnamon.com/2016/06/glow-filter-d3-visualization.html)
      2. [ Multiple Links between nodes in force layout](http://bl.ocks.org/thomasdobber/9b78824119136778052f64a967c070e0) 
      3. [Arc Calculation](https://stackoverflow.com/questions/11368339/drawing-multiple-edges-between-two-nodes-with-d3)

### Planned updates:
- Add a dropdown to choose bus line;
- Show bus lines that visit less than 2 stations (no connections);
- Show more info about a bus line selected (url to original pdf);
- ~Show a summary visualization of the sequencial station connections when a bus line is selected, in a format similar to [this](https://image.winudf.com/v2/image/YmUuc3RpYl9zY3JlZW5zaG90c18xXzVlODFhMzk/screen-1.jpg?fakeurl=1&type=.jpg);~ (done) 
- Allow to choose between bus line directions (invert station sequence);

## How to run

1. Live [here](#tryit) as mentioned previously.

2. Locally: 
   1. Downloading the projecting 
   2. Opening `dataviz_mapping_aracaju.html`.  
       - But be aware that CORS issue could happen when try loading JSON/CSS files. If this happen, one solution is changing the loading  of the respective files to remote (web URLS instead of local). 
