# Gauss curve fit for Mitochondria membranes seperation

In this project, we aim to separate the 2 Mitochondria membranes, using a confocal fluorescence microscope

One membrane was stained by GFP, the second by mCherry. The images were taken using confocal fluorescence microscope.

Using Fiji, a line was drawn across the mitochondria, and the pixels intensity alog this line was exported:
Each data file contain the pixels values in the 488nm (GFP) channel and 561nm (mCherry) channel, along the line (distance from 0 - the starting point of the line)

This data has a gaussian shape to it. We aim to quantify the difference in width between the GFP and mCherry curves.
We fitted the data to a gauss curve, and then defined the width of the curve as 2*sigma (standart diviation).

We used R^2 value to test our fit.
to improve R^2, we tried using a rolling averaging window.

More st information in the jupiter notebook file



