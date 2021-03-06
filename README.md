# Interactive Data Visualization of Public Bus Transportation connections between bus stations in Aracaju, Sergipe, Brazil.

The public bus transportation network has a great importance in the routine of the major part of the inhabitants of Aracaju, Sergipe, Brazil. However, the mobility inside the network is cloudy for those whom has no knowledge about the bus lines' routes.

This project aimed to bring to surface some information insights about the flow of the current bus network:
- For each bus line: which bus stations are visited by it?
- For each bus station: which bus lines visits there? Where can I reach from there?
- Which bus stations are the most connected? Which ones are the less?
  
## Screenshots
![alt screenshots](https://raw.githubusercontent.com/brunocabral/dataviz-mapping-aju/master/etc/Screenshots.jpg)
## Demo 
<a name="tryit"></a>
### Try it now [here](https://bl.ocks.org/brunocabral/raw/828ed927fdfe83a6b64dbd9dee34ead4/daa78f38c59cb9d65df8067e6ec67cfbb50bc588/) 👈



## Folder

The main file `dataviz_mapping_aracaju.html` is in `root/` directory.

`css/` : css files 

`data/` : JSON source data of bus public transportation

`etc/`: images and other files


## Source
   1. Regional public transportation data retrieved from [SMTT Aju](http://www.smttaju.com.br/smtt/transporte/itinerario-e-horario-dos-onibus) (Originally PDF Format).
   
## How to run

1. Live demo [here](#tryit) as mentioned previously.

2. Locally: 
   1. Download and extract the project
   2. Open in browser `dataviz_mapping_aracaju.html`.  
       - But be aware that CORS issue could happen when try loading JSON/CSS files. If this happen, one solution is changing the loading  of the respective files to remote (web URLS instead of local) or in Mozilla Firefox disable it (about:config) to able for preview. 

## Credits

https://d3js.org/
   
https://lodash.com/

Credits also to some code snippets found on internet that inspired and were adapted:
   1. [Glowing effect](https://www.visualcinnamon.com/2016/06/glow-filter-d3-visualization.html)
   2. [ Multiple Links between nodes in force layout](http://bl.ocks.org/thomasdobber/9b78824119136778052f64a967c070e0) 
   3. [Arc Calculation](https://stackoverflow.com/questions/11368339/drawing-multiple-edges-between-two-nodes-with-d3)

## Planned updates:
- Add a dropdown to choose bus line;
- Show bus lines that visit less than 2 stations (no connections);
- ~Show more info about a bus line selected (url to original pdf)~ (done);
- ~Show a summary visualization of the sequencial station connections when a bus line is selected, in a format similar to [this](https://image.winudf.com/v2/image/YmUuc3RpYl9zY3JlZW5zaG90c18xXzVlODFhMzk/screen-1.jpg?fakeurl=1&type=.jpg);~ (done) 
