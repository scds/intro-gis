---
layout: default
title: Getting Started
nav_order: 3
---

<!-- Edit the content below for the workshop in question. Once you're ready to publish, remove the comment characters e.g. "<!--" at the start and end -->


# Workshop Content

## Workshop slides

<iframe src="https://mcmasteru365-my.sharepoint.com/personal/homuthc_mcmaster_ca/_layouts/15/Doc.aspx?sourcedoc={cc63983e-20b4-476d-bf2b-e750ced2dc08}&amp;action=embedview&amp;wdAr=1.7777777777777777" width="610px" height="367px" frameborder="0"></a></iframe>

<!--
<iframe src="//docs.google.com/viewer?url=https://github.com/scds/intro-gis/raw/main/assets/docs/Intro%20to%20GIS%20(QGIS)%20-%20Slides.pdf?dl=0&hl=en_US&embedded=true" class="gde-frame" style="position:absolute;top:0;left:0;width:100%;height:100%;border:none;" scrolling="no"></iframe>
-->
<br />

[Download the workshop slides as a PDF](https://github.com/scds/intro-gis/blob/main/assets/docs/Intro%20to%20GIS%20(QGIS)%20-%20Slides.pdf)

## Workshop activity

### Activity - Dr. John Snow’s Cholera Map (1854)

Dr. John Snow theorized that the cholera outbreak was attributed to contaminated water. He mapped the location of the 13 water pumps in the Soho district of London, and the location of those who fell ill, and noticed a concentration around one particular pump on Broad (now Broadwick) Street.

This exercise will be an introduction to the QGIS interface, in the replication of Dr. Snow’s map. 

*__Data sources:__*
- Point data, courtesy of [Don Boyes](http://donboyes.com/2011/10/14/john-snow-and-serendipity/) (University of Toronto), for water pump and cholera case locations (file size: ~26 KB) 
- [OpenStreetMap](http://download.geofabrik.de/) data for the Greater London area (file size: ~77 MB) 

#### Part 1 - Create a basic map

<iframe src="https://mcmasteru365-my.sharepoint.com/:w:/r/personal/homuthc_mcmaster_ca/Documents/Instruction%20and%20Outreach/Intro_to_GIS/Intro%20to%20GIS%20-%20Activity%20Part%201.docx?d=wc4ac6cc4a09b414399a7742a7529ae38&csf=1&web=1&e=X0qFOs" width="610px" height="367px" frameborder="0"></a></iframe>
<br />
[Download Part 1 as a PDF](https://github.com/scds/intro-gis/blob/main/assets/docs/Intro%20to%20GIS%20-%20Activity%20Part%201.pdf)

#### Part 2 - Basic spatial analysis

Using Snow’s theory that the source is contaminated water from the pumps, we’re going to determine which pump serves the greatest number of people affected, based on their proximity to the pump. 

Thiessen polygons are drawn in such a way that the boundaries represent the halfway point between neighbouring pumps. Therefore, any location within a polygon is closer to the pump within the same polygon, than any other pump. These polygons will be used to calculate the concentration of cases per pump. 

<iframe src="https://mcmasteru365-my.sharepoint.com/:w:/r/personal/homuthc_mcmaster_ca/Documents/Instruction%20and%20Outreach/Intro_to_GIS/Intro%20to%20GIS%20-%20Activity%20Part%202.docx?d=wa7c183a21a4b475bbd2d6f3ccd15a945&csf=1&web=1&e=Wh8dQt" width="610px" height="367px" frameborder="0"></a></iframe>
<br />
[Download Part 2 as a PDF](https://github.com/scds/intro-gis/blob/main/assets/docs/Intro%20to%20GIS%20-%20Activity%20Part%202.pdf)

#### Reference material

**[QGIS Training Guide](https://docs.qgis.org/3.4/en/docs/training_manual/index.html)**
- Lessons specific to this workshop:
  - **[3.2 Lesson: Symbology](https://docs.qgis.org/3.4/en/docs/training_manual/basic_map/symbology.html)**
  - **[4.2 Lesson: The Label Tool](https://docs.qgis.org/3.4/en/docs/training_manual/vector_classification/label_tool.html)**
  
**[QGIS Tutorials](http://www.qgistutorials.com/en/)**
- Lessons specific to this workshop:
  - **[Importing Spreadsheets or CSV files](https://www.qgistutorials.com/en/docs/importing_spreadsheets_csv.html)**
  - **[Making a Map](http://www.qgistutorials.com/en/docs/making_a_map.html)**
  - **[Points in Polygon Analysis](https://www.qgistutorials.com/en/docs/points_in_polygon.html)**
