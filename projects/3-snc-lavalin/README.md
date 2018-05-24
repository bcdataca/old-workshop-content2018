# Interpolating ship paths in the Port of Metro Vancouver

**Hosted by:** SNC-Lavalin  
**Mentors:** Cameron Wallace

## Goal

Look through the data to find all the records for a particular ship over a ten
day period, and:

1. generate a route map for the ship over that ten day period;
2. identify when there is bad data for the ship and correct it so that the
   resulting route map is as close as possible to what it should be;
3. for bonus marks, make sure the routes don’t go over land (find open data to
   describe the coastline in polygons, and incorporate it).

Alternatively, identify characteristics that might flag "good" data vs. "bad"
data (*e.g.,* speed variations), and identify ways to systematically correct for
bad data without minimum variation of the route. Identify the number of trips
that would be caught and fixed with the methods.

Please visit the
[project page](http://workshop.bcdata.ca/2018/project/project-3/) for a full
description of the problem.

## Data team notes

These data are well formatted and fairly easy to work with; however, the problem
may prove tricky in that spatial time series data sometimes pose unique
challenges from the "typical" data science point of view. We anticipate that
tools like Latent Dirichlet Allocation or Kalman filters may prove useful this
project group.
