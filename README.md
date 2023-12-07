**Final Project for AOS C111: Machine Learning Jack Skari** <img align="right" width="220" height="220" src="/assets/IMG/hurri.jpeg">

In this project, I created a support vector machine (SVM) algorithm to classify the averaged values of convective available potential energy in the lower free troposphere (CAPE$_L$), subsaturation in the lower free troposphere (SUBSAT$_L$), and minimal pressure by whether they are inside or outside of the tropical cyclone's tropical storm force wind swath.

I used a subset of ERA5 reanalysis data called TempestExtremes (by the research group led by Paul Ulrich) which detects tropical cyclones by a large drop in pressure and a the presence of a warm core. Due to the TempestExtremes data I am using not having the radii of each tropical cyclone, I had trouble in my main research determining the tropical cyclone or its environment. This is a curcial problem as I had to generalize what was the inside or outside of a tropical cyclone, leaing to potentially inaccurate data.

To tackle this issue, I used another dataset of detected windswaths from "Dataset of outer tropical cyclone size from a radial wind profile" by Albenis Pérez-Alarcón, Rogert Sorí, José C. Fernández-Alvarez, Raquel Nieto, and Luis Gimeno. Applying this to *will inset soon*, I pulled out another data file found in *will insert soon*. I applied this to *will insert soon* and pulled out an equation for a decision boundary. In this SVM decision boundary, average CAPE$_L$ and SUBSAT$_L$ values are tied to a minimal pressure. If the minimal pressure of a storm at a certain time step is less than what the equation of algorithm predicts, it is classified as being inside of the storm. The opposite is true for values outside of the storm. The classifier has an accuracy of about 81%, making it fairly relaible. 

More detail can be found in *will insert soon* in the assets directory.


