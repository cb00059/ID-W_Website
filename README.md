# MIST 353 Website Prototype



## Table of Contents

- [Overview](#Overview)
- [Page_Descriptions](#Page_Descriptions)
- [Research_Summary](Research_Summary)
- [Future_Enhancement](#Future_Enhancement)
- [Resources](#Resources)
- [Reflection](#Reflection)

## Overview

This is a prototype displaying the general structure of the website I will complete for my MIST 353 project. It contains a main page
and a couple example pages of infectious diseases that would be tracked. Ideally, each page will have a heatmap of the outbreaks of the selected disease
alongside a climate map for the selected region. These are not reflected in this model as it is still early and I did not have the time nor know-how.

The website reflects the ability to page between selected diseases, but does not yet have the ability to page between the regions within each page of disease.

## Page_Descriptions

The Home page (weathermain.html) contains a brief description of the website's purpose and ability. It also provides links to the alternative pages of the site.
These pages are each representing a different disease. Each of the individual disease pages also provides a link back to the main page. 

[HomePage](ID&W_Website/wwwroot/weathermain.html)

The COVID-19 Page is meant to track the data relatd to COVID-19 outbreaks segmented by region. Currently it does not have the ability to do so, however. 
It currently contains a table that shows how I would display the rate of spread in relation to the specified climate when it comes to COVID-19.
As Such:
| Climate  |Risk / Spread Rate| 
|:------------:|:--------------:|
| Tropical | High | 
| Temperate | Medium  | 
| Dry | Low  |


[COVID-19 Page](ID&W_Website/wwwroot/covidmain.html

The Anthrax page does thes same thing as the COVID-19 page, but is meant to keep track of Anthrax.

## Research_Summary
Competitive Analysis
WHO (World Health Organization) : https://data.who.int/dashboards/covid19/more-resources?n=c 
CDC: https://covid.cdc.gov/covid-data-tracker/#maps_positivity-week 
Republic of Lebanon - Ministry of health: https://www.moph.gov.lb/en/Pages/9/1024/the-ministry 
These websites contain important principles that I would like to contain in mine. First, I enjoy the usage of heat maps in these. It will be very beneficial for my idea to show climate-maps of regions or the world and compare those to a map of outbreaks / rates of infection of disease in that same region. This helps draw a visual parallel to bring proof to my point. There are also alternative graphs used throughout the websites. Ideally, My website would contain data for more than one disease, as the ones above do, and allow a search or filter function that allows browsing among them. I am unsure if this will end up in my final product, but at minimum I will probably use COVID-19 data as it was well tracked and still semi-relevant. 

Repository research 
Simple weather website that allows searching of different areas and shows details related to that area. https://github.com/PritamSarbajna/simple-weather-website 
SORMAS https://github.com/SORMAS-Foundation/SORMAS-Project 

The simple weather website has a nice clear function with a neat section that tells all relevant details to the place that was looked up by the user. Additionally, depending on the location that is searched, a different background image will appear. The images are not exactly random either. For example, everytime you search “New York” the same image will appear, even if you switch to a different place and come back, New York has its own picture. Sormas has a lot of information and intractability. I particularly like their map feature and the ever-changing bar graph to represent the cases of diseases along with the easily adjustable metric of switching between the diseases at the click of a button. 

## Future_Enhancement

I have already touched on previous sections the ways I plan on improving the site.

Most of the main features I have envisioned for the website I have not yet figured out how to do / implement cleanly. 
The primary implementation is the heat maps in comparison to disease spread/outbreak maps for each disease. This is the main purpose of my website.
I want to provide clear visuals for the user.  In the future, I will need to figure out how to properly construct the layout of the website 
(nav, header, etc.) in order to adjust the layout to look appealing for the end user. Additionally, I want the the maps to be interactive.
By this, I mean the ability to hover over the map and, for example, it displays where that place is in the world and the potential risk / relevant data
in a tool tip format. 

## Resources

### Chat GPT (OpenAI)

I was too lazy to write the headers for my pages:

Prompt: make it a blank webpage that is just titled "weathermmain" 


Prompt:make me a separate blank HTML page titled "covidmmain"


Prompt: give it an h2 line that displays to the user "Dedicated to Tracking COVID-19"

I wanted to see the framework for the statement for bootstrap buttons:

Prompt: write a line of code that uses the bootstrap primary button to redirect the user to an html page titled "covidmmain.html" 

Wanted a framework for a README:

Prompt: write me a template of a  simple README.md 

Prompt: how do you make a table in README.md

### Bootswatch

Needed Bootstrap to make my website prettier:
https://bootswatch.com/cyborg/


### W3 Schools

There were many W3 Schools resources I used, so there are some I do not remember, but here are the ones that I do.

To learn nav as a seprate divider than div:
https://www.w3schools.com/html/tryit.asp?filename=tryhtml_layout_float

CSS Padding:
https://www.w3schools.com/css/css_padding.asp

Bootstrap Nav:
https://www.w3schools.com/bootstrap5/bootstrap_navs.php

Boostrap Alerts:
https://www.w3schools.com/bootstrap5/tryit.asp?filename=trybs_alerts&stacked=h

Boostrap Table:
https://www.w3schools.com/bootstrap5/tryit.asp?filename=trybs_table_bordered&stacked=h

GetElementID line:
https://www.w3schools.com/js/js_intro.asp
