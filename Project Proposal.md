# Data-Viz-Interface

I propose building a data visualization web interface that allows users to see how different news outlets have used different terminology
-- 

This web interface allows users to explore how different news outlets have used different terms over time and compare.  When people open up the web page, they are asked to type in a word and hit enter.  Below it, a rectangular landscape box is animating with different cubes that represent how often new outlets use that word.  The number and speed of boxes correlate respectively to the number of times the word is used and number of articles using that word, respectively. There are several rectangular boxes with different data sets – the rectangular boxes correspond to the different news outlets.  The width of the box is the x-axis and is time in years.

This website will correspond to a long chained string of neopixel matrices.  The matrices will animate like the rectangular boxes do, and the user can chose which data set to send to the neopixels.   I anticipate this would be installed on a wall with an ipad or laptop in front of it.  

On the software side, I anticipate using processing.js or p5.  I would expect that I would need to use some javascript or html as well.   I would need:
-	a way to control the text input field to the api
-	an API system to pull the data from the websites (JSON or xml)
-	a way of visualizing that data and drawing it to a canvas (processing)
-	some html experience getting it to look nice
-	a way of talking to the matrices (probably java and ajax, could be a fadecandy)

On the hardware side, I would use:
-	neopixel matrices from adafruit
-	a fairly hefty power source
-	probably a capacitor since I am using a lot of power to protect those neopixels from any power surges
-	a photon
-	a wifi source that is reliable

-- 

I anticipate working with a web interface to be challenging since I have never done it before.  I have never used p5 or javascript. I am also not certain that this data visualization will prove to be interesting, so I may need to work on resolving that from a visual/artistic standpoint.  I am most interested in/challenged by having a successful data visualization and if that means leaving out the hardware side of this project then so be it.  

On the hardware side, I know how to send data from a webpage to a photon.. but I don’t know how to parse data along a string of chained neopixel matrices.  That could be tricky. 

Week 1: Start experimenting with the basics of building a web interface, do some related examples from p5 or processing.js
Week 2: Get a rough data visualization web interface working for one news outlet, then work on extending that to more. 
Week 3: Have a working and attractive web interface
Week 4: Build neopixel matrices if appropriate and time available. 
Week 5: Present project. 

