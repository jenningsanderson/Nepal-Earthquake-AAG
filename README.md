# The 2015 Nepal Earthquake

Running Epic-OSM in a Jupyter Environment for quick iteration of the questions and easy visualization of the data.

### Contents

 1. config.yml                 - The global configuration file required by epic-osm
 2. nepal-earthquake.yml       - Analysis window configuration file
 3. Nepal-Earthquake.ipynb     - Main Analysis Notebook
 4. Importing-Nepal-Data.ipynb - A series of commands to manually import the data in pieces (as opposed to running a full rake new command).

#### Why import the data in pieces?
This is a stress test of the current MongoDB implementation of Epic-OSM. We are reaching some of our greatest sizes here, and we should be recreating some of these jobs as map-reduce? However, since we want this to _actually work_, it's importing in small pieces.