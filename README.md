# Cmput275Assignmentonep1
Copy of Cmput275 Assignment. 

This is a program which takes an arduino wired up to a Adrafruit display with a joystick, and loads the whole map of edmonton via sd card
and allows the user to travel around the map of edmonton(displayed on the display) with a cursor controled by the joystick, and will find 
the shortest route between any two places on the map that the user selects. Zoom in functions are included and are done through push buttons.

In this Assignment, the Arduino acts as a client, in which user can select two points on the arduino and send the data. Your computer will 
act as the server, and will calculate the shortest route from the two selected points and send the data back to the arduino to display the shortest route.

In part one of this assignment, we tackle the server part of assignment, where we send two points(in latitude and longditude that are in edmonton) via stdin and we run the script server.py to return the shortest route. This is done via graph techniques and dijkstra's algorithm.The route is sent by stdout in which it is displayed in the form of wavepoints(latitude longditude). These are the connected points on the roads of edmonton which are in terms of distance the shortest route to get to your destination. This is done by taking a huge text file containing all different locations in edmonton(we call each point a vertex) and finding the shortest distance bewtween the vertexes to get to your destination.

Part two upcomming...
