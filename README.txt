To re-create the ParaView images, please follow the steps below.


1. Open ParaView
2. Load the borough files (can load one or all) located in the geojson_files/boroughs folder.
3. Click Apply (should be highlighted in green under the Pipeline Browser on the middle left-hand
	side).
4. To change the lines coloring for each borough, select the corresponding borough file under
	Pipeline Browser. Then, under Properties -> Coloring -> Solid Color, select a color.
5. To thicken the outline of each borough, go to Properties -> Styling -> Line Width and change
	the number. We used a line width of 2 for our images.
6. To change the background of the image, go to Properties -> Background. Uncheck "Use Color 
	Palette For Background" and select Background. Then select a color. We used black.
7. Next, load the pollutant GeoJSON files located in the geojson_files folder and click Apply.
8. Select the pollutant file and go to Properties -> Coloring -> Measure.
9. To thicken the pollutantlines, go to Properties -> Styling -> Line Width and change the number. 
	We used a line width of 2 for our images.
10. Repeat steps 7-9 for each pollutant for each borough.