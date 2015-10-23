Copy Move Forgery Detection-SIFT 
=====================================

The code takes in the the SIFT algorithm into different components of the SCALE INVARIENT FEATURE TRANSFORM, then it divides the image ino several pairs of possible smaller image and tries to detect same object image.
And finally highlights the similar objects.

Package contents
----------------
This package contains the following
MATLAB functions:

* `findNeighbours.m`: Match features based on their descriptors.
* `geometricVerification.m`: Geometrically verify feature matches.
* `getFeatures.m`: Extract features from an image.
* `getHistogramFromImage.m`: Get a feature hisotgram from an image.
* `getHistogram.m`: Get a feature histogram from quantised features.
* `loadIndex.m`: Load an image datbase with an inverted index.
* `plotbox.m`: Plot boxes.
* `plotMatches.m`: Plot feature matches.
* `plotRetrievedImages.m`: Plot search results.
* `plotQueryImage.m`: Plot the query image for a set of search results.
* `search.m`: Search an image database.
* `setup.m`: Setup MALTAB to use the required libraries.



