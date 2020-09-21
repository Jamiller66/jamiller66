---
layout: post
title: Tableau Visualizations
subtitle: Some recent work using the Tableau platform
tags: [tableau, visualization, crime]
comments: true
---

I have been spending some time familiarizing myself with Tableau 2020.2 and thought I'd take a look at per capita crime rates in the State of Florida over the last few years.  I was able to gather multiple spreadsheets (1 per year for 2019, 2018 and 2017) from the FDLE website (https://www.fdle.state.fl.us/FSAC/Data-Statistics/UCR-Offense-Data.aspx) I chose to join the data and rank the counties with respect to **rates** of traditional criminal felonies (Murder, Rape, Burglary, Robbery, Larceny, Motor Vehicle Theft). As a Floridian, I've always read about the crime in South Florida (Miami-Dade, Broward and Palm Beach counties) but I wondered if they are truly the most dangerous based on population. While sparsely populated there are some counties with higher incidents of crime per 100K residents. Should we all avoid Bay County? 

Here is a link to my [Florida Crime Visualization](http://CuriosityData.com/CrimeMap.html)





How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
