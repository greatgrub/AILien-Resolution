# AILien-Resolution
Sorting out intelligence from the noise

Final project for the Building AI course

## Summary

Many signals in the radio spectrum will at first look be mistaken for noise. Low signal energy at the receiving end can be remedied by comparing recorded IQ data to the data from one or more nearby receivers. When picking out the parts that are common to them even very weak signals will stand out against background noise.


## Background
Identifying weak signals is today mostly done at the single receiver and by "lowering" the noise floor with mechanical and electrical means. A signal weaker than background noise cannot be detected unless the modulation and digitilization is know beforehand. Finding new signals is a challenging task. But when using multiple receivers at different locations, it is possible to only consider signals common to them for identification, thus seperating away local energy. This can be compared to how the first photograph of a black hole was taken; with several telescopes at different locations: https://www.nasa.gov/mission_pages/chandra/news/black-hole-image-makes-history

Eliminating noise and identifying signals can act as a feedback loop. By removing the identified signals it is poossible to lower the noise even further. The practical limit for how weak signals that can be detected can be many orders of magnitude lower than possible using only one receiver. This is an important way to identify how natural phenomena is related to radio transmissions - i.e. cosmological effects and even possible alien intelligence.

## How is it used?
Participants will use radio receivers to record signals in IQ-format with GPS timestamps (Vita49 format or similar). IQ-data will be uploaded to a server and data from nearby receivers will be compared to each other. Common elements will be detected and compared to already know signals by the ML algorithm. Identified signals will be used as additional classifiers. The iteration will run until no common IQ data is found for any data pair but will be constantly fed with new data.

Identified signals will be compared to known list of regular occuring signals: Cellphone towers, FM-radio, communication radios etc. Identified signals that can not be matched will be classed as of "Unknown Origin" and will  hopefully be resolved in the future.


## Data sources and AI methods
Data needs to be collected from different locations, and at the same time. IQ data files will be recorded to the same standard. That is to say: the byte size, resolution bandwidth, central frequency, floating-point format and other parameters should be the same for all IQ-files. Supervised AI can be used for testing against known signals, and unsupervised can be used to identify previously unknown signals.


## Acknowledgments

* list here the sources of inspiration
PENDING
