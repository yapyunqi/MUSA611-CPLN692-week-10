# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas. Please produce at least a paragraph which addresses the topics below

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

My application aims to visualize the territorial injustices of austerity and its outcomes in the UK. More specifically, I want to build an interactive dashboard that will display spending cuts as well as numerous socio-economic outcomes across England.

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

I have aggregated data from a wide variety of sources and cleaned them into a single CSV file, as part of my capstone course. I will work directly from this csv file for the javascript final.

## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

I intend to use leaflet as the base for my mapping, and chart JS/chartist JS to display visualizations of my statistical analysis. I will very likely use Bootstrap to customize the front-end bits of my application. Selectize.js seems like quite a cool function to explore, but at this point I'm not yet sure how I'll use it in my dashboard. I'm currently also exploring other dataviz libraries like D3js, carto.js, and amcharts.

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final?

I want my dashboard to be accessible to the layperson. My argument is that austerity is by nature a political project, but too often it is so far buried under accounting books and academic jargon that not many people actually actively engage with what it means and what the implications of pursuing austerity are. I want my visualizations to make clear how austerity has wreaked devastation on British society and exacerbated inequalities through its differential reach.

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

I still expect to have a side bar for my application, with drop down menus and buttons for users to specify certain inputs. I think I will then split the remaining parts of the screen into two halves: one displaying a (probably choropleth) map, and the other a chart of sorts displaying more information related to the map.

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

I think it might be quite challenging to figure out how to code my application such that it will be able to perform statistical analysis on the fly - failing that I might have to pre-calculate all the results, which might not be very efficient because I want to allow quite a lot of user input.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get help interpreting a technology's
purpose/usage).

My interest lies mainly in data visualization, so I want to be exposed to more interactive javascript dataviz libraries (particularly ones that allow a lot of flexibility in terms of accepting user inputs).
