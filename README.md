# terrain-tiles
Access Terrain Tiles from Amazon Web Server (AWS) /  Export elevation and color data to .csv / Import to Rhino/Grasshopper.

Use Colab notebook *Terrain_Tiles.ipynb* for exporting elevation and color data. A single tile requires **lagitude, longitude and zoom level** as input parameters. Data is exported in .csv format and saved to a specified gDrive location. *TILE_X1147_Y777_Z11_COLOR.csv* and *TILE_X1147_Y777_Z11_ELEVATION.csv* example files are provided. 

Use Grasshopper file *TerrainTiles.gh* to import elevation and color data to build a colored mesh model in the McNeel Rhinoceros environment.

gDrive account needed.

![alt text](https://github.com/mmmarcopalma/terrain-tiles/blob/main/RH20210103212549.jpg)

![alt text](https://github.com/mmmarcopalma/terrain-tiles/blob/main/RH20210103212554.jpg)

![alt text](https://github.com/mmmarcopalma/terrain-tiles/blob/main/RH20210103212559.jpg)

![alt text](https://github.com/mmmarcopalma/terrain-tiles/blob/main/RH20210103222053.jpg)

--- 

About Terrain Tiles

https://registry.opendata.aws/terrain-tiles/

https://github.com/tilezen/joerd/tree/master/docs

https://github.com/tilezen/joerd/blob/master/docs/data-sources.md

Explore and Search Tiles

https://eos.com/landviewer/

https://elevation-tiles-prod.s3.amazonaws.com/index.html#4/14.82/-403.59
