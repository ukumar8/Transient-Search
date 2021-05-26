# Transient-Search

Key codes I wrote or developed from the TraP and VLITE Transient Search project to conduct research under the guidance of my advisor, Dr Alexander van der Horst, at The George Washington University in Washington, D.C. I give sincere gratitude to Antonia Rowlinson and Sarah Chastain for ther immense support during this project. 

Abstract

The detection of low-frequency radio transients can help pinpoint high-energy events in
our sky such as supernovae or gamma-ray bursts. We use data from the VLA Low Band
Ionospheric and Transient Experiment (VLITE) to search for such transients. By running
VLITE images through the LOFAR Transients Pipeline (TraP), an algorithm that measures
the fluxes and positions of sources that it finds in images, and quantifies each sources’ variation
in flux over time into two variability parameters, Eta and V, we can begin to search for
such transients. To do this, we employ two machine learning strategies, anomaly detection
and logistic regression, to classify these sources into stable sources and transient candidates.
We find the logistic regression strategy to yield more promising results for VLITE data and
we also provide an estimate of approximately 40% systematic flux uncertainty for future VLITE transient
searches.
