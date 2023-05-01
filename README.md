# Mapping 101+4
Youtube demo link: https://www.youtube.com/watch?v=HnfiJs22vbI&ab_channel=ChristopherShih

![alt text](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/main%20(2).png)

Mapping 101+4 is a geographic information system (GIS) that provides users with map information for cities all around the globe. Developed in C++ with the GTK graphics library. Map data is courtesy of the OpenStreetMap API. Mapping 101+4 allows users to view street names, points of interest, and transit lines, as well as providing directions functionality, similar to common GPS applications today.

Please note that this project's code is **NOT** open-source, as it is property of the ECE297 course at the University of Toronto. Please contact chris.shih@mail.utoronto.ca directly for further inquiries. 

## Features
* Mouse drag to pan across city map.
* Mouse scroll to zoom in/out.
* Display points of interest (restaurants, hotels, transit, gas stations, etc.)
* Find optimal route between two locations.
* Search bar to find specific locations.
* Mapping coverage for 15+ cities across the globe. 

## Algorithms
**Drawing Graphics:** The program utilizes a spatial hashing algorithm - city streets and features are hashed into grid cells on the map. This results in incredibly fast performance, with the program maintaining framerates around 30-50 fps on most maps. 

| Points of Interest  | Metro Stations |
| ------------- | ------------- |
| ![POI](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/zoomin.png)  | ![Metro Stations](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/metro.png) |

| Swapping Maps  | Finding Directions |
| ------------- | ------------- |
| ![Swap Maps](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/swapmapgif.gif)  | ![Enter Directions](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/enterdirections.png) |

| Directions Demo  | Directions Result |
| ------------- | ------------- |
| ![Directions Demo](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/directionsgif.gif)  | ![Directions Result](https://github.com/csh03/ECE297---Mapping-101-4/blob/main/screenshots/directions%20result%20(2).png) |

