---
layout: post
title: Beyond the Headlines with Data Science
subtitle: How transparency builds trust
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [modeling, healthcare, transparency]
---

On March 18th, 2020, California Governor Gavin Newsom declared that his **model** indicated that 56% of California’s population, or 25.5 million people, would be infected with COVID-19 over the next eight-week period. While the numbers (fortunately) did not meet the forecast of his **model**, the doomsday headline no doubt contributed to fear, unease and restlessness among California residents. And it is easy to see why.  Let's assume (for argument's sake) the average citizen reads that headline. I believe he or she might have two assumptions:
1. Government agencies have well-trained statisticians and real-time access to comprehensive data on cases, hosptializations and deaths. 
2. The govenment wants use this data for decision making to ensure the safety of its citizens.

So as the **model** (and a multitude of others) proves over time to be substantially inacccurate, is there any doubt as to why statistical models and forecasts are increasingly scoffed and ignored by much of our population?

The journalist in me recognizes the need to be "first and loud" when it comes to selling news, but let's set aside the journalistic intent and delve into why early modeling using inconsistent data is likely more damaging than admitting, "We don't know enough yet".

The issue with models is that in most cases there is little **transparency** as to how a model is built. Models (even AI models) are generally driven from:
1. Manual inputs (parameters, rules, thresholds, etc.) and/or
2. Pattern recognition and refinement 

I would contend that in the case of California's early declaration on the forecast of COVID-19, the challenge of transparency stems from issues with both. First, with respect to inputs, models are generally built with Subject Matter Experts (SMEs) that have deep knowledge and experience with the factors supporting the model's intent. I'm not sure on March 18th, there were any organizations (i.e. CDC, NIH, WHO) that were experts on COVID-19. In fact I find it less likely that any individual medical professionals in California knew enough to accurately declare specific figures on variables like probable infection rates, most critical comorbidities, viral load implications, etc. 

Furthermore, if those particular variables were used to estimate the *infection of 56% of California's population in an 8 week period*, shouldn't the state's forecasting analysts explain how they are used in modeling the forecast? I can still hear my Algebra teacher harping on "show your work!".  That concept is never more relevant than when explaining the factors and formulas that drive a forecast affecting the psyche of 26 Million people.   

Secondly, machine learning techniques that could continually improve the model need alot of data (the more the better) that is both accurate and consistent. When we were early in the Pandemic, unfortunately many Health Systems were inconsistently recording infections, testing, hospitalizations and mortalities. Data was sparse and unreliable providing little help in improving an already shaky forecast model.   

Certainly with COVID-19, we were all glued to the news and rightfully concerned. However, perhaps we should more consistently err on the side of accuracy and more consistently provide detailed explanations of how specific predicitions were arrived upon. Particularly when it comes to life and death. Models will never be 100% accurate but knowing the foundations of how they were built (**Transparency**) provides everyone a chance internally sanity check the pillars on which a forecast sits. Anything else will more and more frequently be viewed as another 'Black Box' model that can't be trusted.
