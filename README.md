Augmented Reality Flood Simulator for Iowa Flood Center
============

This is the github repository for my Google Summer of Code 2013 project with Iowa Flood Center.

Project summary:

> The aim of this project is to create a web-based augmented reality application using HTML5 technologies for an interactive flood simulation. Users will place encoded paper markers on a board, each representing an object such as a house, car, bridge, levee, dam etc. A webcam is then used to detect and track these markers in real-time. 3D virtual objects will be overlaid on these markers on the screen. A height-map terrain can be loaded by the user to represent the actual terrain condition of a specific place and to provide more interesting structures for flooding to occur. Additional sculpting of the terrain is possible using special “sculpting markers” which can either bump or dent a terrain area. A rainfall event can then be initiated which will flood the area according to variables such as rainfall amount, drainage rate and evaporation rate. Other sources of water can be created by the user using markers which represent water sources, or by removing water-holding structures such as levees or dams. The flood simulation will interact with the 3D virtual objects in the scene.

_Note: You need to run the project using a http server before WebRTC will work, otherwise you will get a permission error. I recommend installing node.js and it's http-server module to get a quick http server running._
