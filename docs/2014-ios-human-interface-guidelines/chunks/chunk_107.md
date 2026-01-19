<!-- Chunk 107 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 366 -->
A **map view** presents geographical data and supports most of the functionality provided by the built-in Maps app (shown below in Photos).  
![](images/_page_162_Picture_3.jpeg)  
**API Note:** To learn more about defining a map view in your code, see *Map Kit Framework Reference* .  
#### A map view:  
- Displays a geographical area using standard map data, satellite imagery, or a combination of both
- Can display annotations(which mark single points) and overlays(which delineate paths or two-dimensional areas)
- Supports both programmatic and user-controlled zooming and panning  
Use a map view to give users an interactive view of a geographical area. If you're developing a routing app, use a map view to display the user's route (for more information about creating a routing app, see ["Routing"](#page-96-0) (page 97)).  
**In general, let users interact with the map.** People are accustomed to interacting with the built-in Maps app, and they expect to be able to interact with your map in similar ways.  
**Use the standard pin colors in a consistent way.** A map pin shows the location of a point of interest in your map. People are familiar with the pin colorsin the built-in Maps app,so it's best to avoid redefining the meaning of these colors in your app. When you use the standard pin colors, be sure to use them in the following ways:  
- Use red for a destination point
- Use green for a starting point
- Use purple for a user-specified point