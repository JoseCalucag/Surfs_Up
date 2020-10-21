<h1 align = "Center"> Surfs Up!
</h1>

<p align = "center">
<img src = "https://assets.simpleviewinc.com/simpleview/image/upload/c_fill,h_560,q_50,w_1680/v1/clients/hawaii/Oahu_05e3bc0f-f7ef-4889-92fd-5b1b3a4ad0fe.jpg"
     width="700" height="300">
 </p>
 
<h3>Overview of the analysis</h3>
The purpose of this analysis is to look at temperature statistics from the Hawaiian island of Oahu. With this data, my client wants to see if it's feasible to run their surf shop and ice cream business all year round. So, by taking this dataset, I took the raw temperature data and filtered it into two seperate queries, one for June and the other for December. Once the queries were created, I stored them into lists, converted them into dataframes and then created statistical summaries of the targeted months by using the .describe() method.

<h3>Results</h3>
There is a bulleted list that addresses the three key differences in weather between June and December. (6 pt)
Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

<br/>
<br/>
**June Results** <br/>
<img src = "https://github.com/JoseCalucag/Surfs_Up/blob/main/June_describe.png" width="200" hieight="400">


**December Results** <br/>
<img src = "https://github.com/JoseCalucag/Surfs_Up/blob/main/Dec_describe.png" width="200" hieight="400">                                                        
<br/>

As we look at the summaries for both months, we can point out some key differences:
* The count is low in December by 183 days. That is possible because December has an extra day than June. Outside of that, we can conclude that possible missing data due to NaN and incomplete data.
* Obviously, we are seeing lower temperatures in December; but not as drastic considering we're in a fairly tropical environment. For instance, we're seeing a 8 degree difference in the lower quartile (25%) while we're seeing only a 3 degree difference in the high quartile (75%).
* The Standard Variation is .5 higher in June. So, we're seeing more variation in temperatures in June where we're seeing more constant temps in December.

<h3>Summary</h3>
Simply, we can see that the temperatures are fairly even keel without not so much deviation. Like, you are in Oahu with tropic weather fronts! So, temerature wise, you're gonna see basically the same weather all year round. For future analysis, we should see other weather data like precipitation and humidity levels annually to see how it would effect customer traffic. Furthermore, I would also see tourist data from hotel and airlines to see if this can also effect your business.
