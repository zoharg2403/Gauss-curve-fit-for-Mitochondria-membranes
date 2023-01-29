# Gauss-curve-fit-for-Mitochondria-membranes

In this project, we aim to separate the 2 Mitochondria membranes, using a confocal fluorescence microscope

One membrane was stained by GFP, the second by mCherry. The images were taken using confocal fluorescence microscope.
Using Fiji, a line was drawn across the mitochondria, and the pixels intensity alog this line was exported
The data folder contain the pixels values in the 488nm (GFP) and 561nm (mCherry) along the line (distance from 0 - the starting point of the line)
This data has a gaussian shape to it. We aim to quantify the difference in width between the GFP and mCherry curves.
We fitted the data to a gauss curve, and then deffined the width of the curve as 2*sigma (standart diviation)
More information in the jupiter notebook file



