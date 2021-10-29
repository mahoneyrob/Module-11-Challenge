# OVERVIEW
The purpose of this project is to create a website that contains data about UFO sightings.  The data is presented as a JSON file, and it is extracted with javascript and put in a webpage with HTML.  A filter was also built for date, location, and type of UFO.

## Results
The webpage seems fairly simple to use.  Other than formatting, it contains a filter section, and a table with a large listing of UFO sightings.  There are 5 search criteria that can be used in the filter.  They are date of sighting, city of sighting, state of sighting, country of sighting, and shape of UFO.  The filter is very exciting in that all you need to do is enter text, and the filter will be activated without hitting a filter button.  You can also filter on more than one filter type, for instance, you can look at sighting seen in California on January 1st, 2010 by entering ca for the state, and 1/1/2010 for the date.

## Summary
The is a huge drawback that I see for this website, and that has to do with the fact that javascript is case sensitive.  When I first created the website, I had my default placeholders for state and country capitalized, so when I entered NM, I got no results, but nm did get me results.  

Because of this, I would add 2 things to make this website better.  The first is a disclaimer that reminds the viewers of the case sensitive nature of the data. I would put this just above the first filter for date.  The second thing I would do is add a duration filter.  There is a slight drawback to the duration filter in that not all of the duration data is formatted the same way, but it could be a welcome addition none the less.