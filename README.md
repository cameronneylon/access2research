Access to Research Map
======================

An IPython Notebook that scrapes the website of [Access to Research](http://www.accesstoresearch.org.uk/)
to obtain the URLs for the participating libraries. It then searches each library
web page for a postcode, writing out a CSV file with library name, URL, and postcode
where it was found.

The full csv file as well as split up into sets of one hundred are in the repository.
The split files were uploaded to a Google Map to display the map as a set of pins. [A
post](http://cameronneylon.net/blog/improving-on-access-to-research) on the construction 
and irony involved in creating this map is available
on [my blog](http://cameronneylon.net). 
[The map that was built](https://mapsengine.google.com/map/edit?mid=zBC5pwaMebo8.kakfyX3YqeXs)
can be found on Google Maps Engine and 
[a visualisation of the IPython notebook](http://nbviewer.ipython.org/github/cameronneylon/access2research/blob/master/access2research.ipynb)
is available via the IPython Notebook Viewer.