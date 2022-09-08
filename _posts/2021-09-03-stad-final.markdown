---
layout: post
title:  "Creating Tools in R for Analysis and Visualization of Spatio-Temporal Air Quality Data"
date:   2021-09-03 07:54:21 -0700
tags: [data visualization, shiny, chemistry, STAD project]
---

## Highlights

### Code
<li> <code>PurpleAir_Portland_2021</code> <a href = "https://github.com/gmcginnis/PurpleAir_Portland_2021" target="_blank" rel="noopener noreferrer">GitHub repository</a> and handout report of preliminary research focusing on the September 2020 Oregon wildfires
<li> <code>AirVizR</code> <a href = "https://github.com/gmcginnis/AirVizR" target="_blank" rel="noopener noreferrer">R package</a> for spatio-temporal atmospheric data wrangling and visualization tool package
<li> <code>AirVizViewR</code> live <a href = "https://gmcginnis.shinyapps.io/AirVizViewR/" target="_blank" rel="noopener noreferrer">Shiny dashboard</a>, <a href = "https://github.com/gmcginnis/AirVizViewR" target="_blank" rel="noopener noreferrer">R code</a> for local use, and instructional handout
<li> Poster and mini-handout for Reed College presentation session

### Project Poster

<a href = "https://drive.google.com/file/d/1mbFkM7Cz5nenoNzb-1y1pSNx7hLEKmbX/view?usp=sharing" target="_blank" rel="noopener noreferrer">![Poster](/assets/handouts/2021-09-session-poster.png)</a>

<hr>
<hr>

## Oregon Wildfire Analysis

In late December 2020 through February 2021, I began working with my analytical chemistry professor and two fellow students to quantitatively analyze the impact of the <a href = "https://en.wikipedia.org/wiki/2020_Oregon_wildfires" target="_blank" rel="noopener noreferrer">September 2020 Oregon wildfires</a> on air quality in Portland using <a href = "https://www2.purpleair.com/" target="_blank" rel="noopener noreferrer">PurpleAir</a> and Oregon Department of Environmental Quality (<a href = "https://www.oregon.gov/deq/pages/index.aspx" target="_blank" rel="noopener noreferrer">DEQ</a>) data, as well as to compare the accuracy of the different qualities of the respective sensors. My role involved downloading, preparing creating visualizations for, and conducting statistical analyses on PurpleAir data.

Some of my work can be found on my <code>PurpleAir_Portland_2021</code> repository <a href = "https://github.com/gmcginnis/PurpleAir_Portland_2021" target="_blank" rel="noopener noreferrer">here</a>.

<b>A project overview is available here.</b>

<hr>

## Summer Work

During the summer of 2021, I worked full-time with NCA and Reed College for the fellowship-supported BREATHE Oregon. In addition to occasional field work, I conducted research in order to create a series of online, publicly-accessible data visualization tools for atmospheric air quality data. This was a collaborative effort with NCA monitor hosts, my chemistry professor, and government workers in the environmental arena.

Much of my research was focused on the different methods of data correction factors. A handout presented to an Advisory Committee on Sustainability and Innovation (ACSI) Air Toxins Subcommittee meeting can be found <a href="/2021/06/14/stad-intro.html">here</a>.

I developed an R package which allows for the wrangling and visualization of PurpleAir, federal reference monitor (FRM), and <a href = "https://www.dstech.io/" target="_blank" rel="noopener noreferrer">ObservAir</a> data.

<b>The package, called "<code>AirVizR</code>", can be downloaded for personal use <a href = "https://github.com/gmcginnis/AirVizR" target="_blank" rel="noopener noreferrer">here</a>.</b> It contains extensive vignettes with explanations for each function, as well as real examples on its <a href = "https://github.com/gmcginnis/AirVizR#readme" target="_blank" rel="noopener noreferrer">README</a>.

In July, I created another handout with new visualizations relating to the recent changes in air quality as a result of Independence Day celebrations; it can be found <a href="/2021/07/07/stad-july.html">here</a>.

Furthermore, I developed a Shiny dashboard to allow non-R users to interact with data (within certain limitations). It is recommended that large-scale data comparisons (as well as FRM cross-comparisons) use the <code>AirVizR</code> package in a local install of RStudio.

<b>The Shiny dashboard is available for use <a href = "https://gmcginnis.shinyapps.io/AirVizViewR/" target="_blank" rel="noopener noreferrer">here</a>.</b> The dashboard source code, known as "<code>AirVizViewR</code>" can be found <a href = "https://github.com/gmcginnis/AirVizViewR" target="_blank" rel="noopener noreferrer">here</a>.

<hr>

## Post-Project Cohort Presentation

Once my school year resumed, I continued to work part-time with NCA to expand collaboration with community groups and individuals. I presented the digital tools to community members through a live, remotely conducted demonstration.

<b>The corresponding instructional handout can be found below and is available <a href="/2021/08/02/stad-cohort.html">here</a>.</b>

<hr>

## Reed College Poster Presentation

On September 3, 2021, I was able to present my tools at the Reed College summer poster session.

<b>The poster can be found below and is available <a href = "https://drive.google.com/file/d/1mbFkM7Cz5nenoNzb-1y1pSNx7hLEKmbX/view?usp=sharing" target="_blank" rel="noopener noreferrer">here</a>.</b>

<a href = "https://drive.google.com/file/d/1mbFkM7Cz5nenoNzb-1y1pSNx7hLEKmbX/view?usp=sharing" target="_blank" rel="noopener noreferrer">![Poster](/assets/handouts/2021-09-session-poster.png)</a>

<hr>
<hr>

## Related posts

<li> <a href="/2021/06/14/stad-intro.html">Introduction</a>
<li> <a href="/2021/07/07/stad-july.html">July updates</a>
<li> <a href="/2021/08/02/stad-cohort.html">Cohort instructions</a>

<hr>

## Special thanks
<li> Dr. Juliane Fry, Reed College
<li> Mary Peveto, NCA
<li> Micah Bishop, NCA
<li> Dr. Christine Kendrick, City of Portland
<li> Lance Giles, Lane Regional Air Protection Agency (LRAPA)
<li> ACSI Air Toxins Subcommittee, Multnomah County
<li> John Wasiutynski, Multnomah County
<li> Knowledge Murphy, Multnomah County