# Book-notes-Think Stats Exploratory data analysis
Notes from the book: *Think Stats Exploratory data analysis* by Downey

## Chapter 3 Probability Mass Functions  
Mot much detail is given, but PMFs are great way to summarize data distribution. Basically a histogram that is normalized
to the probability of the continuous values occurrence. Need to see how this differs from Probability density function!  

## Chapter 4 Cumulative Distribution Functions  
Remember the CDF is the same as the ECDF (We had a video on this way back on the InTO data science team)! It is really powerful
to use both a histogram in conjunction with a CDF plot! While the histogram can change depending on bin size, 
the ECDF will be constant.  
**CDF != ECDF**:  
The ecdf is taken as an empirical sample from the population, thus resulting in the value of a given variable ***x***
as a real value taken from the population; The empirical CDF is built from an actual data set (in the plot below, 
I used 100 samples from a standard normal distribution). The CDF is a theoretical construct - it is what you would see 
if you could take infinitely many samples

### Notes 12/23/2022 19:00 from DCA :) BEGIN
## Chapter 5 Modeling Distributions  
**Exponential distributioin**:  
In the real world, exponential distributions come up when we look at a series of events
and measure the times between events, called interarrival times. If the events are equally
likely to occur at any time, the distribution of interarrival times tends to look like an
exponential distribution  

**Normal probability plot**:  
For testing whether   

**Lognormal Distribution**:  
If the logarithms of a set of values have a normal distribution, the values have a log‐
normal distribution. The CDF of the lognormal distribution is the same as the CDF of
the normal distribution, with logx substituted for x.  

### Notes 12/23/2022 22:00 from DCA :) END
