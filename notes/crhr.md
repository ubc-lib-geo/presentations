Intros - Maya and me
https://arcg.is/1LX1180


Summary of the hour
- I'll do a short presentation just framing GIS and covering some concepts and definitions, sort of as a primer Mayas section.
- where she will talk about a suite of software available from the software provider Esri.


I want to acknowledge that I'm on the traditional, ancestral, and unceded territory of the musqueam people. And I want to ask you all
to at some point in this next hour as we talk about ideas and concepts related to geography, to think about what that means to you and
how that might be different from someone else's interpretation.
As you think about GIS and analyzing and visualzing geographic spaces, think about how different interpretations of land, territories, resources might
affect the way we work with geographic information.

And for those of you who may be at home in another territory, I want to make sure you know about native-land.ca as a tool to
discover other territories around the world.

## Slide 0

Framing your understanding of GIS
We’ll start with a little history
Which will hopefully frame GIS using a non-technical example.
Then we’ll gradually pull together some concepts and definitions to better contextualize GIS and spatial information.
I’ll pause for questions along the way - drop them in the chat if needed.

## Slide 1
So, starting with some history. John Snow. A London physician and epidemiologist.
Some also consider him the originator of modern spatial analysis - or comparing the relationships of things in space.
In 1850s London, John snow investigated a cholera outbreak, leading to a discovery that the source of the
outbreak was a specific city water pump.

## Slide 2
In his work, he collected data about the locations of cholera cases, and indicated them with a dot on a map,
as you can kind of see here, to show the spatial distribution of cholera cases.
Just looking at this data can tell you what? - that cases were clustered around a certain area.

## Slide 3
If we zoom into that are on the map, we can see in addition seeing the locations of the cholera cases, there’s also water pumps.
Using these two datasets, John Snow was able to better understand how two at the time seemingly unrelated
spatial phenomena were in fact intertwined. And the rest is history – he was able to eventually find that all of those who were sick
were using a specific water pump.

## Slide 4
What John Snow did summarizes the essence of GIS and working with geographic information.
He collected data. Data that is tied to a place or location. which houses were people sick? Where are they water pumps?
He explored and analyzed that data, looking for patterns.
And he communicated those patterns visually (I don't know if this map was actually made by John Snow,
but it is often used to refer to his findings).
In any case, you can imagine that this cartographic visualization may be more effective in communicating spatial patterns,
than a written document.

## Slide 5
That was 1854, and I'm sure a lot of the work that John Snow did was rather painstaking.
Collecting the data was probably done door-to-door, creating the map was done by hand, etc.
Now we have technology that can do these things much more easily, and this technology (GIS Technology) has lowered the bar for acquiring,
analyzing, and visualizing data. However, over time other types of technology has made data more prevalent and advanced

## Slide 6
Some of the types and uses of geographic information that we see today are really amazing.
Like Satellite imagery used for all kinds of environmental monitoring.
We work with a company called Planet.com who operates a cluster of satellites in orbit around the earth. They have a method
for researchers to request through an API a satellite be in a position in space at a certain time to capture custom imagery
of a specific location on earth. When I heard that I was blown away. the future is now.
We have social media data or transactional data tied to locations that can tell market researchers what the buzz words
are or who's buying what.
There's Census data from most countries and regions of the world – which is some of the rawest, richest, and most accessible data
in the world for urban planning or studies in demographics.

What these data all have in common is that they're tied to a locations.
And Geographic information systems are meant to work with this type of data.

## Slide 7
A Geographic information system is a technology that enables the use of geographic data.
And I like this analogy. We use this technology in similar way to a word processor.
We add information, review and edit it, we style it. We organize our files, we relate them to other files.

## Slide 8
I've used the term "geographic information" a few times and I just want to talk briefly about machine
readable geographic information – which I refer to as spatial data or geospatial data.
As we've covered geographic information is information tied to a place. spatial data is the machine readable form of geographic information.
spatial data comes in two main types: raster and vector.

Raster data is comprised of pixels. When you zoom into it, it becomes pixelated. data like satellite imagery is a raster type.
Vector data is made up of basic geometries instead of pixels. So things like road networks or boundaries.

The important thing to know is that each of these file types come with the right information that allow GISs and other
geospatial technology to situate them in their real-world locations – often times this is lat long information and other essential
geographic information like projection or other coordinate system-related details.


## Slide
One thing I would like to stress is the abundance of technology that works with geographic data.
I can't keep up with all of it, and it seems like there's something new each day.
But I can attempt to group them into types.
There are what I call utilities. These are the applications that perform a specific task or set of tasks.
These can be things like web mapping frameworks, or python scripts, or a specific data editors
Then there are Desktop GISs like QGIS and Esri's AcMap. These are like the toolboxes that give a wide range of
functionality for managing data, analyzing it, and visualizing it.
And then there's GIS infrastructure. Which is used my groups of people to manage and provide access to data.
When we think of traditional GIS we're usually thinking of desktop software.

## Slide
The last thing that I want to briefly touch on is the idea of cartography - or effectively communicating geographic information.
If we go back to using the analogy of a word processor and writing.
We can all probably recognize a well written document.
A superior writer uses excellent grammar, spelling.  And maybe even they have a writing style of their own.
In the map world these skills and talents are transferred through cartography, or cartographic design.
