# RTM Visualizer
A simple HTML5 visualizer for the RichTerrainMapping project. The RichTerrainMapping project is a long-distance RC glider that can autonomously scan and create topographic maps with labelled landmarks, all while needing only a single data capture. The depth mapping is created by two 8MP sony cameras connected to a raspberry pi running Tensorflow to recognize landmarks in real time and smooth the collected data. This data is then combined into an archive with other sensor information to create a topographic map for previously unmapped areas. 

# Future functions
This visualizer is only displaying the captured texture (sample sets using google maps data) and the captured depth map. This is not displaying any landmarks or other data, and the sample datasets do not actually represent real correlated data.

# Code
This program uses bootstrap for the UI, three.js for the rendering, and UPNG.js for decoding the depth map. 

# Demo
To test out this project, check out the [hosted demo](http://rtmviz.astehneylabs.com).
\
There are two included demo archives, [a Depth Map demo](http://rtmviz.astehneylabs.com/demos/Depth_Map_Demo.zip), and [a normal data archive](http://rtmviz.astehneylabs.com/demos/Depth_Map_Demo.zip).
