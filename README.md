# Transportation_Map
This is a course homework using pyspark and kafka. I also used bokeh lib to plot the real-time map.
It is a good attempt with streaming messages.

## Background

For this project, I am working with the real-time stream of the NS, the train company of the Netherlands. You can see an example webpage that uses this same stream to display the train information on a map: https://spoorkaart.mwnn.nl/ .

As some items are not in English, you can find useful ones below: 

ndovloketnl-arrivals : For each arrival of a train in a station, describe the previous and next station, time of arrival (planned and actual), track number,...

ndovloketnl-departures: For each departure of a train from a station, describe the previous and next station, time of departure (planned and actual), track number,...

ndovloketnl-gps: For each train, describe the current location, speed, bearing.



