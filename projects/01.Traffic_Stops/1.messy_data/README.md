# Week 2: Data is Messy

This project uses the San Diego Police Department 2016 traffic stop
data (see
[https://data.sandiego.gov/datasets/police-vehicle-stops/](https://data.sandiego.gov/datasets/police-vehicle-stops/)). The city
makes a bunch of interesting data available at
[https://data.sandiego.gov](https://data.sandiego.gov).

By the end of this week you will be able to:

* Work with messy real-world data
* Identify when data is bad, and what to do about it
* Perform more sophisticated analysis in Tableau, including aggregations, formulas and new plot types

## Questions to pursue:

As you explore the SDPD dataset, you will be trying to build a picture
of the nature of traffic stops in San Diego. To draw conclusions,
you'll typically looking at the difference between occurences
(e.g. getting stopped) across multiple attributes (e.g. time, space,
gender, ethnicity). This analysis will sometimes show no
difference. However, sometimes it will show a difference, and you'll
have to determine whether this difference is due to a significant
reason or just random flucuations.

When working with real data created by many individual humans,
oddities in the data collection process often occlude the "real"
picture. This could be null values, inconsistent data input, typos in
data, and approximations during data entry. These oddities are
unavoidable, and this project begins with exploring and handling the
messiness in data.

* After loading the data, plot the counts of the values of each
  field. Keep an eye out for null values, values that seem impossible
  (e.g. outliers), and values that occur 'unnaturally' often. 

A few sample questions to pursue, to get you started:

* What ages do you see? oldest? youngest? null values? *anything
  else?*
* Examine the "Stop Cause" field. What are some issues and how should
  you deal with it?
* Traffic stops by ethnicity: what major ethnicity seems to be
  underrepresented? what data are needed to figure this out precisely?
* Plot counts of fields by time -- are the traffic stops uniform? or
  is there a pattern? is the pattern an oddity?
    - Number of traffic stops by quarter, month, day?
    - Number of traffic stops by day of month? day of week? hour of
      day? minute of the hour?
* Are there dates where stops are abnormally low/high? why?
* Gender breakdown of traffic stops by hour of day? Median age by hour
  of day?
* Percentage of cars searched by hour? by ethnicity? by gender?
* Property seized/arrested in relation to searched? Ask the same
  question here as with stops overall?
* Ask the same questions for various "Stop Causes"

## Further Reading

[This collection of "falsehoods programmers believe in"](https://github.com/kdeldycke/awesome-falsehood) is worth a good
look every time you start to work with a new type of data.  A good
example is 
[Falsehoods programmers believe about time](https://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time),
which starts with "There are always 24 hours in a day."

[Guide to messy data for journalists](https://qz.com/572338/the-quartz-guide-to-bad-data/)
contains a good checklist for questioning the quality of a dataset.

[The Stanford Open Policing Project](https://openpolicing.stanford.edu/) has data, tutorials, and links to some of the best work data scientists are doing with police data.  Thanks to Jan Overgoor from that group for helping with resources for how to approach the SDPD data.

## Assigned Readings

See [readings](readings.md)
