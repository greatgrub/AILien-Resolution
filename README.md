# AILien-Resolution
Sorting out intelligence from the noise

Final project for the Building AI course

## Summary

Many signals in the radio spectrum will at first look be mistaken for noise. Low signal energy at the receiving end can be remedied by comparing recorded IQ data to the data from one or more nearby receivers. When picking out the parts that are common to them even very weak signals will stand out against background noise. This


## Background
Identifying weak signals is today mostly done at the receiver and by "lowering" the noise floor with mechanical and electrical means. A signal weaker than background noise cannot be detected unless the modulation and digitilization is know beforehand. Finding new signals is a challenging task. But when using multiple receivers at different locations, it is possible to only consider signals common to them for identification, thus seperating away local energy. This can be compared to how the first black hole was photographed with several telescopes at different locations: https://www.nasa.gov/mission_pages/chandra/news/black-hole-image-makes-history

Eliminating noise and identifying signals will act as a feedback loop to remove the identified signals and lower the noise even further. The practical limit for how weak signals that can be detected will be many orders of magnitude lower than today. This is an important way to identify new natural phenomena and how it is  causing radio transmissions -i.e. cosmological effects and even possible alien intelligence.

## How is it used?
Participants will use radio receivers to record signals in IQ-format with GPS timestamps (Vita49 format or similar). IQ-data will be uploaded to a server and data from nearby receivers will be compared to each other. Common elements will be detected and compared to already know signals by the ML algorithm. The amount of data requires algorithms to process and identified signals will be used as additional classifiers. The iteration will run until no common IQ data is found for any data pair but will be constantly fed with new data.


## Data sources and AI methods
Data needs to be collected from different locations, and at the same time. Server needs hosting. 

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |



## Acknowledgments

* list here the sources of inspiration 
