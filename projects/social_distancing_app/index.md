---
layout: page
title: Social Distancing App
---

![](/images/projects/smartphone_listening.png "Social distancing smartphone app")


### Background

As we take a thoughtful approach to progressively reopen businesses in our region, there needs to be a way to ensure compliance of social distancing ordinances for the safety of the citizens. Social distancing and limiting crowds will continue to be a key part of controlling the spread of the coronavirus.

![](/images/projects/crowd.jpg "Crowd not practicing social distancing")

Knowing how many people are in an establishment at a given time is a simple metric that can be utilized for public health at a county level. This is possible through the use of commodity smartphones and done in a privacy-preserving way.

### Smartphone App

We are developing a smartphone app that can ensure local businesses are following social distancing protocols. Each business could be asked to use a smartphone that is plugged in and running a special app that monitors how many people are in a given space and how often they are coughing. We would estimate the number of people nearby the phone by detecting the number of unique speakers and how often they are coughing by determining personalized cough frequency.  The statistics would then be sent to our remote server for general reporting or to provide a real time dashboard. 

This technology has been utilized for other infectious diseases such as TB in regions outside of the US. More than just compliance, this could give patrons peace of mind on knowing that a local business has been following proper protocols. The contract tracing APIs being developed by Google/Apple would also be used to estimate co-location in addition to the audio.

### Technology

#### Detecting Speakers

Modern speaker identification algorithms can estimate how many unique voices are in earshot of the speakerphone mic of a smartphone (i.e., 15-20 ft) by using a process called speaker diarization. [https://ai.googleblog.com/2018/11/accurate-online-speaker-diarization.html](https://ai.googleblog.com/2018/11/accurate-online-speaker-diarization.html). The smartphone would first listen to audio and identify when speech is heard. Next, it would use speaker diarization to identify the person speaking so the number of unique speakers could be determined.

#### Detecting Coughers

The UW UbiComp Lab recently published a method for determining the identity of a cougher. [https://ieeexplore.ieee.org/document/9053268](https://ieeexplore.ieee.org/document/9053268). Similar to detecting speakers, our app would first determine when a cough is heard. Next, it would estimate the identity of the person who produced the cough so a table of coughs per person could be provided.

#### Privacy

In both cases, this analysis would only run on the phone so no audio data is ever stored or leaves the phone.

### Get Involved

Interested in getting involved with this project? Please contact Matt Whitehill at mattw12@uw.edu.
