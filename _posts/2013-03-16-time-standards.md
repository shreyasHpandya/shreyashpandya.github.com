---
layout: post
title: "Time Standards"
tagline: "confusion that never stops"
description: "explanation of common time standards and relation between them"
category: 
tags: ["time standards", "science"]
---
{% include JB/setup %}

We humans have this sick compulsion to keep track of time. Many time standards have emerged while trying to come up with standard ways to measure time in due course of existence of human civilization. Some independently and others successively.

There are so many time standards in use for various purposes. I have tried to simplify (ok I over simplified it) and present what you might just want to know.

Wikipedia defines time standard as

> *Time standard is a specification for measuring time: either the rate at which time passes; or points in time; or both.*  
> *-wiki*

Usually the time standard gives their own version of Second or Day or both. So in order to compare each time standard we just have to see what a Day or Second means according to that standard. What follows is the list of few often mentioned time standards and its exact details.

1. International Atomic Time (TAI):  
    It is very straight forward standard. It tics at the rate of [SI Second ](http://en.wikipedia.org/wiki/Second). It defines day as exactly 86400 seconds. So it increments a date exactly after span of 86400 seconds. Counting of days is as per Gregorian calendar.
    
2. Greenwich Mean Time (GMT):  
    Perhaps the first formal time standard. However it was originally not meant to be a time standard. Its purpose was to help maritime transport navigate by broadcasting accurate time at Greenwich Meridian. But gradually *everybody* started setting their clocks to [GMT time signal](http://en.wikipedia.org/wiki/Time_signal).  
    GMT specifically keeps track of mean solar day. Date is changed at noon when the Sun* crosses Greenwich meridian. However mean solar day is inherently longer than 86400 SI Seconds, put it another way, "GMT Seconds" are longer than SI Seconds.

3. Universal Time(UT1):  
    Successor of GMT and supersedes it. Only difference from GMT is that day changes at mid night, while in GMT day changes at noon. GMT now means UT1 implicitly.

4. Coordinated Universal Time (UTC):  
    This also tics at the rate of SI Seconds. Day is 86400 seconds long normally but sometimes 1 second longer or shorter to keep in sync with UT1. It is basically a *hack* to track mean solar day with SI Second. Since all the computer clocks and watches tics at SI second and we humans being diurnal animal want to track mean solar day, this UTC was introduced as civil time.

###Leap Second  

UTC tracks mean solar day with SI seconds. normally a day is changed after 86400 seconds. But mean solar day is slightly longer than that (2 ms). So at some predefined date, day is made 86401 seconds long to adjust the drift in day from mean solar day. It is not fixed when leap seconds are introduced. This is because mean solar day depends on earth's rotational speed which is unpredictable. So it is introduced as needed to keep UTC in sync with UT1 (essentially mean solar day)

<sub> * fictitious sun not the actual sun. See <a href="http://en.wikipedia.org/wiki/Solar_day">solar day</a></sub>