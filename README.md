<h1 align = "Center"> Surfs Up!
</h1>

<p align = "center">
<img src = "https://assets.simpleviewinc.com/simpleview/image/upload/c_fill,h_560,q_50,w_1680/v1/clients/hawaii/Oahu_05e3bc0f-f7ef-4889-92fd-5b1b3a4ad0fe.jpg"
     width="700" height="300">
 </p>
 
<h2>Overview of the analysis</h2>

My client tapped me to do an analysis of temperature statistics of the Hawaiian island of Oahu. He wants to see if it's feasible to run his surf shop and ice cream business all year round. By taking the temperature data, we filtered two seperate queries for the months of June and December. The data was then stored into lists and converted into dataframes. Then, I created statistical summaries for each month by using the .describe() method.

<h2>Results</h2>
<br/>

**June Results** <br/>
<img src = "https://github.com/JoseCalucag/Surfs_Up/blob/main/June_describe.png" width="200" hieight="400">


**December Results** <br/>
<img src = "https://github.com/JoseCalucag/Surfs_Up/blob/main/Dec_describe.png" width="200" hieight="400">                                                        
<br/>

As we look at the summaries for both months, we can point out some key differences:
* The count is lower in December by 183 days. As we would like to have our datasets to be fairly the same, we should account that the difference can be cause two ways: 1) December has an extra day than June and 2) there may be incomplete or missing data.
* Obviously, we are seeing lower temperatures in December; but not as drastic considering we're in a fairly tropical environment. For instance, we're seeing a 8 degree difference in the lower quartile (25%) while we're seeing only a 3 degree difference in the high quartile (75%).
* The Standard Variation is .5 higher in June. So, we're seeing more variation in temperatures in June where we're seeing more constant temps in December.

<h2>Summary</h2>
Simply, we can see that the temperatures are fairly even keel without so much deviation. Like, you are in a tropical city! You are generally going see the same temperature all year round. For future analysis, my client should consider looking at other weather factors like precipitation and humidity  to see how it they can effect consumer traffic. Furthermore, my client should also consider seeing data from hotel and airlines to see if there was an influx of tourists coming in for June and December.
