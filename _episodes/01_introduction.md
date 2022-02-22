---
title: "Overview to Workshop and Introduction to Climate Science"
teaching: 10
exercises: 0
topics:
- "Motivation" 
- "Introduction to Climate Science"
- "Current Methods of Understanding Climate Science"
questions: 
- "What is a Climate Science?"
- "What is climate vs. weather?"
objectives:
- "Understand the current advancements and limitations of climate research"
keypoints:
- "Climate science is largely limited by the minimal data collected on timescales necessary to assess long-scale patterns."
- "Understanding and prediction of climate is very computationally expensive and still very limited."

---

| Lesson        | Teaching | Lesson | Main Questions                  | Objectives                       |
| -----------   | -------- |------- |-------------------------------- |--------------------------------- |
| Machine Learning | X mins | 0 mins | What is machine learning? What are some powerful applications of these tools? | Establish background context for machine learning models| 
| Climate  | 5 mins | 0 mins | What does it mean to study climate? What is climate vs. weather? | Establish a basic understanding of the field of climate|
| Climate Obstacles | 5 mins | 0 mins | What are the biggest barriers to climate science? How can we establish context with little data, train models in a changing world? | Establish important context for obstacles in the field of climate|
| The El Nino Southern Oscillation | 5 mins | 5 mins | What is ENSO? Why is it important to our understanding of climate/climate change?| | 
| Machine Learning in Climate: Resources | 5 mins | 5 mins | What are some resources with climate time-scale data? | List of websites and archives that contain large, publicly available data|
| Machine Learning in Climate: Data Processing | 5 mins | 5 mins | Best methods of data processing? | Dealing with missing data, outliers, time scale variability|
| Machine Learning in Climate: LSTM Models | 15 mins | 15 mins | What is a Long-Short Term Model? How can we use this for time-series analysis?| Using buoy data within the ENSO 3.4 index, we'll train, test, and then assess an LSTM model |

---

## Motivation
"Climate change" is the phrase of the decade, and is rapidly shaping the future of humanity. But what is climate, say, versus weather? And how are they connected? Weather is the state of the atmosphere at a place and time with regards heat, dryness, sunshine, wind, rain, and other conditions. Weather describes the immediate state of these conditions, or the state of the atmosphere at a specific place and time. For example, today's weather (02/25/22) is supposed to have a high of 80 degrees F, around 60% relative humidity, scattered cumulus clouds and a minimal chance of rain. Climate, on the other hand, is the long-term description of typically a more broad region. Climate describes the generalized patterns experienced over a larger geographic region. Hawaii's climate, for example, is around 85 degrees F with scattered trade-wind rain showers in the summer time, and around 75 degrees F with broader, more less weaker trade winds and more substantial rain in the winter. Climate does not describe every day perfectly, however. 

## What is Climate Science?

Climate science, therefore, is not the study of individual weather events, but the study of long-term patterns and changes of patterns in weather and atmospheric conditions. Typically, climate science refers to the study of global climate and how the world as a whole is changing, however, climate scientists can often have specific regions of study as well. When we refer to climate change, we assess how the long term patterns across the world are changing compared to typical, historical values. Climate change can be described as changes in average seasonal temperatures to changes in precipitation, changes in sea ice coverage, changes in cloud coverage, etc. Anything large geographic and time scale change with relation to weather can be described as climate change if there is long term data to support the identified changes. 

One of the most important concepts of cliamte science is that singular weather events do not define, confirm, or negate the evidence of changing climate. 
<a href="{{ page.root }}/fig/01climatevsweather.jpg">
 <img src="{{ page.root }}/fig/01climatevsweather.jpg"/>
</a>
(Source: Australian Climate Education Office) 

---
## What are current methods we use to understand climate? 
- Observations and Statistical Trends: 
<a href="{{ page.root }}/fig/01c_climatestatistics.png">
 <img src="{{ page.root }}/fig/01c_cliamtestatistics.png"/>
</a>
(Source: NOAA) 

<a href="{{ page.root }}/fig/01d_oceantemps.png">
 <img src="{{ page.root }}/fig/01d_oceantemps.png"/>
</a>
(Source: Statista) 


- Climate Models: 
<a href="{{ page.root }}/fig/01b_gpawg-climate-earth-systems-models.png">
 <img src="{{ page.root }}/fig/01b_gpawg-climate-earth-systems-models.png"/>
</a>
(Image courtesy of Paul Ullrich, University of California, Davis) 

{: .callout}




Citations
- Figure 1: https://www.australianenvironmentaleducation.com.au/education-resources/climate-vs-weather/
- Figure 2: https://www.climate.gov/news-features/understanding-climate/climate-change-global-temperature
- Figure 3: https://www.statista.com/chart/19418/divergence-of-ocean-temperatures-from-20th-century-average/
- Figure 4: Image courtesy of Paul Ullrich, University of California, Davis

{% include links.md %}
