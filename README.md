# Meteorit-landing


## Overview

The Meteoritical Society collects data on meteorites that have fallen to Earth from outer space. This dataset includes the location, mass, composition, and fall year for over 45,000 meteorites that have struck on Earth.

This dataset was downloaded from NASA's Data Portal, and is based on The Meteoritical Society's Meteoritical Bulletin Database (this latter database provides additional information such as meteorite images, links to primary sources, etc.).


### Data Structure

*Note:* Some column names start with "rec". These are the recommended values of these variables, according to The Meteoritical Society. In some cases, there were historical reclassification of a meteorite, or small changes in the data on where it was recovered; this dataset gives the currently recommended values.

The dataset contains the following variables:

    - name: the name of the meteorite (typically a location, often modified with a number, year, composition, etc)
    - id: a unique identifier for the meteorite
    - nametype: one of:
    -- valid: a typical meteorite
    -- relict: a meteorite that has been highly degraded by weather on Earth
    -recclass: the class of the meteorite; one of a large number of classes based on physical, chemical, and other characteristics (see the Wikipedia article on meteorite classification for a primer)
    - mass: the mass of the meteorite, in grams
    - fall: whether the meteorite was seen falling, or was discovered after its impact; one of:
    -- Fell: the meteorite's fall was observed
    -- Found: the meteorite's fall was not observed
    - year: the year the meteorite fell, or the year it was found (depending on the value of fell)
    - reclat: the latitude of the meteorite's landing
    - reclong: the longitude of the meteorite's landing
    - GeoLocation: a parentheses-enclose, comma-separated tuple that combines reclat and reclong




## Data Visualisation


