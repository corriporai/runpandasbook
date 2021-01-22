![Picture of art running team](_static/images/running_team.jpg)

# Overview

Running is becoming a quite popular sport around the world. It's free, requires very little equipment and is simple to get started. Plus, with regular practice, you can improve quickly. Whether you are new to running, have been running for years or are a world-class race, knowing what running metrics to pay attention can be intimidating. As technology improves, it gets more complex, since data that once was only available in a lab setting is now at our fingertips. With advent of GPS-based smartwatches and social running applications such as Strava, MapmyRun and NikePlus Club, more runnners are collecting dozens of activities data, but then not actually using that information or is limited to the features that those apps can offer.

```{warning}
This book is continuously being revised. Found a mistake? [Go here](https://github.com/corriporai/runpandasbook/issues).
```

In this book, we will take a closer look at what your favorite tracking app or watch is telling you, by exploring the activity data and introduce you to some of the very popular running metrics such as heart rate, cadence, distance, mean speed and to advanced ones such as vertical ratio, power stress and heart rate zones.

Running metrics are becoming more and more popular, and since you own this data, let this book be a start guide for anyone interested in learning sports analytics, data science concepts and of course start running!
## Language Choice

Recent technological advances to GPS-enabled tracking devices is transforming the aspects of training and competition in fitness activities such as running, cycling and swimming. Those devices produces detailed tracking data among several sports data available for anyone interested at its analysis. This enables a descriptive analysis associated with the related data, such as performance, impact of volume of training or just reviewing the historical activities. There are several devices or applications for sports tracking offered by manufacturers of the tracking devices, such as Garmin, Polar, and through a wide range of applications for devices such as smartphones and smartwatches, e.g., Strava, Endomondo, and Runtastic Running GPS Tracker.

Limiting to range of data science open-source packages available, there is only a handful of packages specific to sport data and their analysis. Within Python ecosystem, one of the most popular programming languages for data science, there is a gap to fill between the collection of tracking data and the analysis of such data. Pandas is a popular package for data analysis, and several specific domain libraries as built on top of it. At my research at time, I didn’t find many sports data analysis package within the Python + Pandas ecosystem.

As a possible alternative, `runpandas` package comes as a set of utilities to import sports data from GPS-enabled devices or even track activities applications, and, after careful processing, organises them in data frames which can provide information about the units of measurement (e.g. distance and speed units) as well of any data operations that have been carried out (e.g., personal best records, heart efforts, elevation gain).

In this book, I use `runpandas` with `pandas` data analysis package to dive in into our running activities data, explore some running metrics and teach you more about the data behind them and what they are really telling us about our running.

## Table of Contents

```{tableofcontents}
```

## Progress Bar

Chapter Goal: 18

To come:

1...

<div class="wh-wrapper">
    <div class="wh-progress-bar">
        <span class="wh-progress-bar-fill" style="width: 1%;"> 1% </span>
    </div>
</div>

## Citation

Please cite as

> Caraciolo, Marcel P. *Running with Runpandas*. 2021.

## Contributors

Thank you to contributions:

1. Dyego Carlos