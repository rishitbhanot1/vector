# VECTOR : VELOCITY EXTRACTION & CALCULATION FROM TEST OBSERVATION RECORDS

## Rocket-mounted sled velocity analytics platform powered by a custom processing algorithm & operator-centric GUI 

* The VECTOR application was developed to process multi-channel coil sensor data and estimate the velocity of a moving object across a known sequence of physical coils. 

* The recorded signals may contain noise, baseline variation, false peaks, missing samples, and missed detections, making direct interpretation unreliable.
* To address these issues, the application applies structured signal processing and sequence reconstruction.

* It converts raw ADC data into signed signals, extracts likely transient events using the Teager–Kaiser Energy Operator, aligns those events with the expected coil sequence using dynamic programming, and estimates both measured and fitted velocity profiles.

* The complete system consists of three main parts: the backend processing algorithm, the frontend user interface, and the result and report generation module. 

* The backend code forms the core of the application and performs all signal analysis, event classification, timing reconstruction, and velocity estimation
