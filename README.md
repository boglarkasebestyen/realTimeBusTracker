# Real-time Bus Tracker

This is 1 out of 3 of my 1st semester final assignments via MIT xPro's Fullstack with MERN course. It demonstrates the frontend side of a single page banking application built on following the provided user stories and with the help of the provided starter code. I have refactored its design, implemented the components, added additional validation criteria, as well as used React Context in order to share the required data between the components.


The exercise demonstrates checking active bus routes in real time located between Boston University and MIT in Boston, MA and shows the buses on the map by having a marker on them. In order to not put too much stress on the API, the positions are only updated in every 15 seconds.
<br/>
<br/>
The tracker is implemented using the [mapbox](https://www.mapbox.com) JavaScript library and requesting data using the [API](https://www.mbta.com/developers) of the Massachusetts Bay Transportartion Authority. The implementation includes key concepts such as DOM manipulation and asynchronous programming. 


<p align="center">

<img src="https://media.giphy.com/media/uJjAWcLq3OZf6JpZvw/giphy.gif"/>

</p>

## How to run

Clone the respository and open the index.html file in your browser of choice. 

## Future improvements
* Using an API that covers a Californian transportation route, such as BART for Northern California. 
* Adding a marker on the starter- and the destination point.

## Additional information
I also have an implementation of a moving marker on the BART route from San Francisco to San Jose, California. However, this was done by providing every BART station's location coordinate. The files for this version are uploaded [here](https://github.com/boglarkasebestyen/boglarkasebestyen.github.io/tree/master/1st_semester_assignments/bartTracker).

## Live demo
Take a look at the project [here](https://boglarkasebestyen.github.io/busTracker/index.html).

# License

MIT License

Copyright (c) 2021 Boglárka Sebestyén

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
