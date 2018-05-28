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

Check out:

* [Wikipedia](https://www.wikiwand.com/en/Automatic_identification_system#/Detailed_description:_Class_A_units)
  for a description of the columns in the data.
* [aishub](http://www.aishub.net/stations): it's possible they have *more* data
  if necessary.
* [marinetraffic](https://www.marinetraffic.com/en/p/ais-historical-data): it's
  possible they have historical AIS data available - especially and including
  [for research](https://www.marinetraffic.com/en/p/ais-for-research).

Also check out this possibly related paper by Luke Bornn where paths of NBA
  players were clustered and analyzed: [Possession Sketches: Mapping NBA
  Strategies](http://www.sloansportsconference.com/wp-content/uploads/2017/02/1624.pdf). A
  final useful tool may be [Kalman
  filters](https://www.wikiwand.com/en/Fast_Kalman_filter), used for
  interpolation of noisy data where position and speed matters. Something to this end is done in [Extended Kalman Filter for State Estimation and Trajectory Prediction of a Moving Object Detected by an Unmanned Aerial Vehicle](https://ieeexplore.ieee.org/document/4282823/). 
