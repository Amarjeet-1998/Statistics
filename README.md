# Statistics


# Central tendency -  

It is the single value that attempts to describe a set of data identifying the central position. 

The 3 measures of central tendency are the mode, median, and mean. 

 

Mean: 

As we know, it is the arithmetic average of our data series. It is one of the most effective measures of “center” of the data.  

But what is the practical application of this term in data science and analyzing data? 

 

Let's see we have: -  

“Age” data series as follows - {24, 28, 29, Nan,31, 36, Nan} 

Nan: Not a number 

Now while performing various operation on this data series, we will get issue and errors because of presence of Nan Values. 

So how do we resolve this. Here comes the mean. What we do is we find the mean of actual values and replace the Nan values with mean. 

Replace the Nan values with mean. 

Mean of Age data group -> (24+28+29+31+36) /5 = 29.6 

Now we replace Nan values with this mean. Now out data series looks like this: {24,28,29,29.6,31,29.6,36} 

 

But there is one issue with this approach. Mean is greatly influenced by outliers (values that are very much larger or smaller most of the values). 

E.g. - Let’s add one more value which is much larger than most of the value to our Age data series. Now it looks like -> {24,28,29, Nan,31,36, Nan,80} 

Now if we find the mean of the series we get -> (24+28+29+31+36+80)/6 = 38 

We can see the change in mean just because of one value, 80, thus in this case 80 was outlier. 

So how do we resolve this situation. Median whenever we get outlier values on our data series, we should go for median. 

 

What is median now? 

The middle number in an ordered dataset. So how we find median? 

Step1. Sort the data series. 

Step2. Find the central number. That central number is the median. 

Central number – Depends on the total number of elements present in data series. 

If total number are odd then central element is the median. 

E.g. {1,2,3,4,5,6,7,8,100,120} 

Median -> (5+6)/2 = 5.5 

If total number are odd then average of central elements is the median. 

E.g. - {0,1,2,3,4,5,6,7,8,100,120} 

Median-> 5 

 

At this point if we come to this last term, mode  

Mode – The most frequent value present. We generally use mode with categorical data as well as numerical data. A data set can often have no mode, one mode or more than one mode. 

It all depends on how many different values repeat most frequently. 

 

 

 

 
