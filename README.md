# Data sets of volunteer task execution events in Galaxy Zoo and The Milky Way Project between 2010 and 2012

## Context of the data sets

Galaxy Zoo and the Milky Way Project were hosted on the Zooniverse platform (www.zooniverse.org). The Zooniverse has successfully built a large community of volunteers contributing to citizen science projects. 

The original Galaxy Zoo project was launched in July 2007 but has since been redesigned and relaunched three times, building each time on the success of its predecessor. In 2010, the Zooniverse launched the third iteration of Galaxy Zoo, called Galaxy Zoo: Hubble, but for simplicity, we use the term Galaxy Zoo throughout this text to refer to this project. Each volunteer classifying on Galaxy Zoo is presented with a galaxy from the Sloan Digital Sky Survey (SDSS) or the Hubble Space Telescope as well as a decision tree of questions with answers represented by a fairly simple icon. The task is straightforward, and no specialist knowledge is required to execute it. 

Tasks in the Milky Way Project exhibit a larger cognitive load than those in Galaxy Zoo. Volunteers are asked to draw ellipses onto the image to mark the locations of bubbles. A short, online tutorial shows how to use the tool, along with examples of prominent bubbles. As a secondary task, users can also mark rectangular areas of interest, which can be labeled as small bubbles, green knots, dark nebulae, star clusters, galaxies, fuzzy red objects, or “other.” Users can add as many annotations as they wish before submitting the image, at which point they’re given another image for annotation.


## Description of the raw data

In this repository, each file is a project, each line on a file is one classification record. The lines contain three pieces of information separated with commas (","). The first information is the `classification id`, which uniquely identifies the classification in the data set. The second information is the `volunteer id`, which uniquely identifies in the data set the volunteer who carried out the classification. The third information is the `data and time` in which the classification was carried out.

The data set from the Galaxy Zoo project consists of records of 9,667,586 tasks executed by 86,413 volunteers over 840 days, starting on 17 April 2010. The data set from the Milky Way Project consists of records from 643,408 tasks executed by 23,889 volunteers over 670 days, starting on 3 December 2010. 

These datasets were provided by Arfon Smith and Robert Simpson, from the Zooniverse platform, in October, 2012. To understand how volunteers make their contributions in these citizen science projects, [Ponciano, Brasileiro, Simpson and Smith (2014)](https://doi.org/10.1109/MCSE.2014.4) analyzed both data sets considering a volunteer engagement perspective. 


## Metrics derived from the data set

[Ponciano, Brasileiro, Simpson and Smith (2014)](https://doi.org/10.1109/MCSE.2014.4) proposed and computed the following metrics on the data set: _Frequency_, or the number of days in which the volunteer was actively executing tasks in the project. _Daily productivity_, or the average number of tasks the volunteer executed per day in which he or she was active. _Typical session duration_, or the short, continuous period of time the volunteer devoted to execute tasks on the project. A session begins when a volunteer starts a task execution, but it may end for a variety of reasons, such as the volunteer achieving the time he or she wanted to devote to the project, or that person getting tired or bored because of something related to the task performed. The typical session duration is the median of the duration of all the volunteer’s contribution sessions. _Devoted time_, or the total time the volunteer has spent executing tasks on the project. It's calculated as the sum of the duration of all the volunteer’s contribution sessions.

They generate statistical probability distributions to the volunteer engagement characteristics that fit the parameters of  Zipf and Log Normal. The results reported in the study reveal many characteristics of the distributions of volunteer participation in the projects. For example, they show that the majority of the volunteers perform tasks in just one day and do not come back, but those who come back contribute the larger proportion of tasks executed. For more information about methods and results of the first study that analysed the data set, please, see [Ponciano, Brasileiro, Simpson and Smith (2014)](https://doi.org/10.1109/MCSE.2014.4).

In a subsequent study, [Ponciano and Brasileiro (2014)](https://doi.org/10.15346/hc.v1i2.12) deepened the study by considering a new framework to study volunteer engagement. In this new study, new metrics and a clustering approach were used to identify groups of volunteers who exhibit a similar engagement profile. A new set of metrics is designed to measure the engagement of participants that exhibit an ongoing contribution and have contributed in at least two different days, so they focus on participants that are more likely to fit into the voluntarism definition. In this perspective, they formalyzed the following metrics: _Activity ratio_, _Daily devoted time_, _Relative activity duration_, and _Variation in periodicity_. Their results show that the volunteers in such projects can be grouped into five distinct engagement profiles that we label as follows: hardworking, spasmodic, persistent, lasting, and moderate. For more information about the method and results on the engagement profiles see [Ponciano and Brasileiro (2014)](https://doi.org/10.15346/hc.v1i2.12).

## Reporting the use of the data set

The data sets stored in this repository are freely available to be used at the Creative Commons Attribution licence. In case you use the data set, please, include in your work a citation of the previous studies [Ponciano, Brasileiro, Simpson and Smith (2014)](https://doi.org/10.1109/MCSE.2014.4) and [Ponciano and Brasileiro (2014)](https://doi.org/10.15346/hc.v1i2.12) that were the first to characterize the data from Galaxy Zoo and the Milky Way Project in a volunteer engagement perspective. After that, you may also inform the Zooniver platform that you have used data from Galaxy Zoo and the Milky Way Project. To do so, you can use [this form](https://docs.google.com/forms/d/e/1FAIpQLSdbAKVT2tGs1WfBqWNrMekFE5lL4ZuMnWlwJuCuNM33QO2ZYg/viewform) indicated by the platform at the [publication page](https://www.zooniverse.org/about/publications).


## References

Lesandro Ponciano, Francisco Brasileiro, Robert Simpson and Arfon Smith. "Volunteers' Engagement in Human Computation Astronomy Projects". Computing in Science and Engineering  vol. 16, no. 6, pp. 52-59 (2014) DOI: [10.1109/MCSE.2014.4](https://doi.org/10.1109/MCSE.2014.4)

Lesandro Ponciano and Francisco Brasileiro. "Finding Volunteers' Engagement Profiles in Human Computation for Citizen Science Projects". Human Computation  vol. 1, no. 2, pp. 245-264  (2014). DOI: [10.15346/hc.v1i2.12](https://doi.org/10.15346/hc.v1i2.12)
