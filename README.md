# Whale FM Archive

###About Whale FM

Whale FM ran from Nov 2011 to March 2015 and was a collaboration between [Zooniverse](https://zooniverse.org) and [Scientific American](www.scientificamerican.com).

<img src="https://raw.githubusercontent.com/zooniverse/WhaleFM/master/screenshot.png" alt="Whale FM Screenshot" style="width:90%;padding-left:5%;">

The project was designed to organise recordings of Orca and Pilot Whale calls. Volunteers were asked to match sounds to the most-similar call from a range of other recordings. Data provided by [WHOI](http://www.whoi.edu/).

The original Whale FM site was built as a branch of the Zooniverse's [Juggernaut](https://github.com/zooniverse/Juggernaut) Rails 3 app.

###Legacy Data

All the original classifications, assets (images and sound file), and other ancillary Rails tables have been preserved in both Gzipped MySQL and CSV formats. All user data has been stripped, reducing each user to a unique id integer.

These include a table of **matches** that show how many times each pair of calls were marked by volunteers as a match, explicitly as a non-match, or skipped entirely (i.e. were confusing).

<img src="https://raw.githubusercontent.com/zooniverse/WhaleFM/master/avatar.jpg" alt="Whale FM avatar" style="width:20%;padding-left:40%;">

The data is stored in this repo within the CSV, SQL, and JSON subdirectories. An archive site now exists at [whale.fm](http://whale.fm) with more links and information.