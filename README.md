# Sand_Engine_Surface
This repository contains a MATLAB based application _SandEngineSurface_, which is a part of the manuscript "Exploring Mega-Nourishment Interventions Using Long Short-Term Memory (LSTM) Models and the Sand Engine Surface MATLAB Framework", published in the Geophysical Research Letters journal (https://doi.org/10.1029/2023GL106042). Technical specifications, usage instructions, and component descriptions are provided in the "Description" file. Installation and usage demonstrations are available in the "Installation" and "Usage" video files.

## App Description
The Sand Engine Surface application includes LSTM models developed to predict surface level (bathymetry) variations of the sand engine over time. The sand engine is a coastal protection scheme where a large amount of sand is deposited near the beach. Waves then distribute this sand to nearby beaches, aiding in their nourishment. Over time, waves erode the sand engine and alter its shape. This application predicts the amount of sand eroded and the bathymetry at different locations on the sand engine over time, based on varying wave conditions. The app also presents simulated data for comparison. 

Based on the configuration of the sand engine, waves, and tides provided by the user, this application selects the simulation data that closely matches the given configuration. The selected simulation configuration is presented in a table below the bathymetry variation graph, as shown in the image below.

![Screenshot 2023-07-03 at 1 11 39 pm](https://github.com/pavitra979/Sand_Engine_Surface/assets/118841277/257209cd-a653-4de6-9ab6-d93434912ad9)

The readme section of this application is equipped with features to visualize the simulated erosion of the sand engine over time. This data can be exported in video, GIF, image, and MATLAB formats. Results can also be played and visualized in 3D. The app downloads the required simulated data from a GitHub repository. If there is no internet connection, the simulated data will not be visualized; however, the prediction models can still be used.
![Picture 1](https://github.com/pavitra979/Sand_Engine_Surface/assets/118841277/6ed58f1a-8423-4fb2-987d-ef99ab097fbc)
