---
layout: default
title: Module Quiz
# parent: Module 1
nav_order: 3
---

# Module 2 Quiz

You can submit your answers to these questions via the Module 2 Quiz on Canvas.  Questions are listed here with hyperlinks to the relevant section of the lab if you need help finding answers.

## Rubrics

### Written Answers 

Written answers should be brief but they should adequately answer the question.  Bullet point format is sufficient unless otherwise specified.  All written answers will be evaluated following this general rubric.

* Scores & categories are general guides, you TA may assign scores between these levels
* Your TA will provide brief comments where applicable, if you need more feedback you can follow up with your TA.

|Score|      Category      |                             Details                              |
|-----|--------------------|------------------------------------------------------------------|
|0%   |Missing             |N/A                                                               |
|40%  |Insufficient        |Minimal effort, missing major key points, or serious logical flaws|
|60%  |Below Expectations  |Missing a few key points or minor logical flaws                   |
|80%  |Met Expectations    |Hits key points and mostly well constructed                       |
|100% |Exceeds Expectations|Clearly thought out, concise, and astute                          |


### Map Submissions

Maps will be evaluated for completeness following the rubric below.  Later in term, maps will be evaluated for correctness and cartography.  For now, as long as you can make a map with the necessary elements, you'll get full credit!

|Score| Category |                     Details                     |
|-----|----------|-------------------------------------------------|
|0%   |Missing   |N/A                                              |
|50%  |Incomplete|Did not follow instructions, missing key elements|
|100% |Complete  |Successfully made a map with required components |

---

# Quiz Questions 

## Part 1: Map Projections Tutorials

### Exercise 1

[**1)**](https://ubc-library-rc.github.io/map-projections/content/exercise1-discover-coord.html#inspecting-the-metadata) Metadata is _____ about ____.


### Exercise 2

[**2)**](https://ubc-library-rc.github.io/map-projections/content/exercise2-transform.html#exercise-2-projecting-on-the-fly) In your own words, what does Project “On the Fly” do?


### Exercise 3

[**3)**](https://ubc-library-rc.github.io/map-projections/content/exercise3-project.html#exercise-3-project-your-data) What UTM zone is Vancouver in?

* 10 S
* 11 N
* 10 N
* 18 N

[**4)**] Use the [What UTM Zone am I in?](https://mangomap.com/robertyoung/maps/69585/what-utm-zone-am-i-in-#) tool to match find the UTM zones for these cities:


### Exercise 4

[**5)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#inspect-the-attribute-tables) What spatial unit is the Shape_Area of the CAN_albersEA in? (hint check the Spatial Reference Info).

* Kilometers
* Meters
* Square Miles
* Square Kilometers
* Square Meters
* Degrees


[**6)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#inspect-the-attribute-tables) What is the difference in Shape_Area given for the CAN_webMercator and CAN_albersEA layers in **Square Kilometers**?  Round to the nearest whole number.

<!-- 41,118,591 +- 100 -->


[**7)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#calculating-population-density)  We are multiplying by 1000000 to convert the units to population per square ____.

<!-- Kilometer -->

[**8)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#calculating-population-density) What is the population density of the **CAN_webMercator** layer? Round your answer to the nearest hundredth place.

<!-- 0.72433603 -->

[**9)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#calculating-population-density) What is the population density of the **CAN_albersEA** layer? Round your answer to the nearest hundredth place.

<!-- 3.71718812 -->

[**10)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#calculating-population-density) How do the calculations compare?  Which layer do you think has the most accurate Population Density and why?


## Part 2: Comparing the Projections

[**11)**](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html#calculating-population-density) 


<!-- [**1)**](/docs/Application_Part1.md)
In your own words, describe what a map projection is.  Why do we use them and why are they all wrong?

## ArcGIS Pro Tutorial

[**2)**](docs/Application_Part2.md#introductory-tutorial)
Upload your *Central_Wellington_Layout.pdf*.

[**3)**](docs/Application_Part2.md#explore-your-data)
What does the select layer by attributes tool do?

- Find features that meet specific criteria.
- Find features that are in a specific area.
- Find features based on their spatial relationship to other features.


[**4)**](docs/Application_Part2.md#make-a-layout)
A ______ in ArcGIS Pro is a way to put a map on a page and map elements like a north arrow, legend, scale bar, and extent indicator.

- Map frame
- Layout
- Data view
- Geoprocessing pane

[**5)**](docs/Application_Part2.md#use-geoprocessing-tools)
What tool was used to create the 1500 meter zone around the campsites?

- Select by location
- Buffer
- Intersect
- Select by attribute

[**6)**](docs/Application_Part2.md#create-points-on-a-map)
What is the first step when creating a new point layer?

- Create a polygon feature class in the project geodatabase
- Create a raster dataset
- Make sure you are zoomed into your area of interest. 
- Create point feature class in the project geodatabase

## Foundations of Eipdemiology

[**7)**](docs/Application_Part3.md#belief-perseverance)
In your own words, what is belief perseverance and how did it inhibit the development of European medicine? Give your own example of belief perseverance. This can be a historical example or one from your own personal experience.

[**8)**](docs/Application_Part3_1.md#georeferencing)
In your own words, what does georeferencing do?

[**9)**](docs/Application_Part3_1.md#georeferencing#adding-the-deaths-feature-dataset)
A ______ is a file management structure that is unique to ESRI products.

- Folder
- Zipfile
- Shapefile
- Geodatabase

[**10)**](docs/Application_Part3_1.md#georeferencing#inspect-the-data)
How many cholera deaths were recorded in this outbreak? ______ How many locations (points) are in the dataset? ______ What is the highest number of deaths at one location? ______

[**11)**](docs/Application_Part3_2.md#georeferencing#symbolize-by-count)
______ point symbols are sized differently to convey magnitude/intensity.

- Triangular
- Sequential
- Graduated
- Bigger

[**12)**](docs/Application_Part3_3.md#central-tendency)
What do the mean center and directional distribution tell us about a set of points?

[**13)**](docs/Application_Part3_3.md#kernel-density)
Why might Kernel Density be more useful for identifying the source of a source(s) of a cholera outbreak outbreak than the mean center and directional distribution?

[**14)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Application_Part3_4.html)
Upload your *Kernel_Density.pdf*. -->


<!-- 
[**2)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part1_1.html)
A ______ is a naturally occurring magnet.  They were first used by the ______ civilization in present day Mexico to orient their buildings and towns.

[**3)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part1_2.html)
The ______ projection revolutionized navigation because mariners could use it to navigate anywhere in the world by following a constant ______.  However, it is problematic for modern day use because it exaggerates the size of landmasses farther from the equator.  


[**5)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part1_4.html)
The ______ aimed to map lands in Canada based on their suitability for agriculture, forestry, recreation and wildlife.  It was the first digital ______.

[**6)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part2_1.html)
The first step in creating an abstraction of the earth is to simplify it to a geoid.  The geoid is an abstract representation of the earth that smooths out ______ but preserves elevation differences due to ______ differentials.  Once we have a geiod, we can fit it to an oblate spheriod using either a local or global ______

[**7)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part2_1.html)
If you are mapping a city like Vancouver, a ______ datum is best.  When mapping the whole world, you'll want to use a ______ datum.

[**8)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part2_1.html)
______ is a measure of angular distance North/South of the equator and ______ is a measure of angular distance from the prime meridian.  Together, they form a ______, describing locations on the surface of a simplified model of the earth known as a ______ which represents the earth as an oblate spheroid.  

[**9)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part2_2.html)
The Mercator projection should never be used to calculate:[Area/Distance/Bearing] . (select all that apply)


[**10)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part2_2.html)
This type projection is great for displaying a small area like the city of Vancouver, but it should not be used to display all of Canada on one map.

* Universal Transverse Mercator
* Conic
* Cylindrical
* Planar

[**11)**](https://june-skeeter.github.io/Module1_GEOS270/docs/Content_Part2_2.html)
A map displaying UBC campus would be a ______ scale map.  A map displaying the whole world would be a ______ scale map.

 -->