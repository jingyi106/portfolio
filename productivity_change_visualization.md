# Data Visualization - Productivity in manufacturing and mining industries

## Part 1: Visualization Background
On April 28, 2022, The U.S. Bureau of Labor Statistics released a news report regarding productivity and cost in manufacturing and mining industries in 2021 https://www.bls.gov/news.release/pdf/prin.pdf
With news released chars https://www.bls.gov/charts/productivity-mining-manufacturing/percent-change-in-productivity.htm#

The charts focus on two parts: productivity percent change in 2021 and productivity percent change in a long-term. They included 22 sectors in the visualizations. There are two visualizations shown in the news released charts

<img width="500" alt="image" src="https://user-images.githubusercontent.com/100049171/190945305-43ba9c6c-fc61-4869-a325-c76ba27cbd36.png">

Figure1: productivity 1-year percent change in 2021




<img width="500" alt="image" src="https://user-images.githubusercontent.com/100049171/190945623-a6803090-5f35-46dc-b4b4-e628099fd8c7.png">

Figure2: productivity average annual percent change from 1987 to 2021


## Part 2: Critique this data visualization
### Usefulness:Is it useful for the intended audience? Does it communicate valuable information?
Overall, I think it’s useful for the intended audience. The audience group would be government agencies and companies in those domains. From those visualizations, the audience can capture the information they want, for example, the productivity of beverage and tobacco products decrease by nearly 15% in 2021, and the decreased percentage is the most significant among all involved sectors. However, it’s hard for the audience to understand if they want to know the rank of those sectors.

### Completeness: Does the visualization have everything necessary to make it understandable?
There are two parts that I think the visualizations lack to convey all the information that the audience needed. One is the rank of those sectors according to productivity change, and the other one is that there is no comparison between percent change in 2021 and percent change from 1987 to 2021. 

### Perceptibility: Can the reader understand the information with minimal effort? Is the visualization type appropriate? Does it use illogical comparisons?
Bar charts are used to visualize the percent change. I think it’s very easy to understand

### Truthfulness. Is the visualization accurate, reliable and valid? 
The data is pretty straightforward. There are only 3 columns: name of sectors, productivity 1-year percent change in 2021, and productivity average annual percent change from 1987 to 2021. The bar charts are presenting those values in each sector, so it’s correct and trustful.

### Intuitiveness. Is it easy to understand and clearly communicates the information? If unfamiliar, does it include easy to understand instructions on how to interpret it? 
The visualizations are easy to understand. The titles are clear enough for the audience to understand the information, so there is no use to add any other description.

### Aesthetic: It is interesting / enjoyable to look at? Is it a good example of what a beautiful data visualization might look like? Is it somewhere in the middle - pleasing but otherwise not distracting to look at?
There are two parts that I think need changes. One is the color use: it’s not necessary to use different colors to represent different sectors, and the other one is the bars are not sorted, which is no enjoyable. 

### Engagement: Does it lead the audience to learn more about the topic? Does it inspire the audience to talk about the data or share it with others?
From the visualizations, the audience can learn about the productivity percent change in different sectors in the manufacturing and mining industries, which is valuable information. It inspires the audience to share the information with others, especially shareing with domain experts for further analysis. 

### Overall Observation
The visualizations clearly show the productivity percent change of different sectors in the manufacturing and mining industries (one visualization for 2021, and the other for 1987-2021). 
The visualizations work well in the following aspects:
  1.    The use of bar charts is very clear and easy to understand
  2.    Clear title and labels
  3.    The information contained in the visualizations is useful, especially for domain experts  
  
The visualizations don’t work well in the following aspects:
  1.    The use of color is confusing and there is no need to use different colors to represent different sectors
  2.    The bars are not sorted, which doesn’t look good
  3.    There is no comparison between the two charts
  
Suggested changes:
  1.    Change the color: make it red-blue diverging
  2.    Sort the bars in a descending order
  3.    Produce another chart that shows the difference between productivity percent change in 2021 and annual average productivity percent change from 1987 to 2021. Compare the percent change in 2021 with the average level for the past 34 years.

### Primary Audience
The primary audience for the visualizations would be officials in government agencies who are responsible for managing manufacturing and mining industries. They can learn about the development of each sector recently from the visualizations. 
This visualization is effective for reaching that audience. Firstly, it’s easy to understand for everyone and the results are precise and accurate.

### Recommendations
Overall, the visualization is complete. Additional information I would add is representing the difference between productivity percent change in 2021 and annual average productivity percent change from 1987 to 2021. Comparing the percent change in 2021 with the average level for the past 34 years would be useful for the audience to know what sectors’ productivity changed a lot in 2021. Comparing figures with some baseline values are good for reaching meaningful insights. I will continue using bar charts with rank to show which sector’s productivity changed most in 2021 compared with the average level in the past 34 years.


## Part 3: Sketch a solution
I made two changes in the new design
1.	Change the color: make it red-blue diverging
2.	Sort the bars in a descending order

<img width="500" alt="image" src="https://user-images.githubusercontent.com/100049171/190946275-3f0ec9d8-d792-486b-b978-d7abec408ae9.png">


## Part 4: Test the solution
I have shared the sketches with two people. My questions are below:
  1.	Can you describe what this is telling you?
  2.	Is there anything you would change?
  3.	Do you think the colors look good?

I got some feedback from them:
  1.	It would be better to show the number near each bar
  2.	It would be better to left align the industry name
  3.	The diverging color looks good, which is much better than the original plots
  4.	The visualization is clear enough to convey necessary information

## Part 5: Build a new visualization (Tableau)


<div class='tableauPlaceholder' id='viz1663443990121' style='position: relative'><noscript><a href='#'><img alt='Productivity 1-year percent change in 2021（Manufacturing and Mining Industries) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;Productivity1-yearpercentchangein2021&#47;2021&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Productivity1-yearpercentchangein2021&#47;2021' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;Productivity1-yearpercentchangein2021&#47;2021&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1663443990121');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Figure 1: productivity 1-year percent change in 2021



<div class='tableauPlaceholder' id='viz1663446048151' style='position: relative'><noscript><a href='#'><img alt='Productivity average annual percent change(1987-2021, Manufacturing and Mining) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pr&#47;productivityaverageannualchange1987-2021&#47;1987-2021&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='productivityaverageannualchange1987-2021&#47;1987-2021' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pr&#47;productivityaverageannualchange1987-2021&#47;1987-2021&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1663446048151');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Figure 2: productivity average annual percent change from 1987 to 2021


<div class='tableauPlaceholder' id='viz1663445926692' style='position: relative'><noscript><a href='#'><img alt='Difference of productivity percent change between 2021 and average annual level(Manufacturing and Mining) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pr&#47;productivitydifference&#47;difference&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='productivitydifference&#47;difference' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pr&#47;productivitydifference&#47;difference&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1663445926692');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Figure 3: Difference of productivity percent change between 2021 and average annual level

## Assumption about the difference plot (Figure 3):

We assume there is no significant fluctuation in percent change from 1987 to 2021, which means the annual percent change from 1987 to 2021 is stable. In this case, the average annual percent change from 1987 to 2021 reflects the average change level for the past 34 years.

By subtracting percent change in 2021 by average percent change in the past 34 years, we can know about the change in 2021 compared with the average level. 

## Reference
News report regarding released by the U.S. Bureau of Labor Statistics in 2021
https://www.bls.gov/news.release/pdf/prin.pdf 

News released chars
https://www.bls.gov/charts/productivity-mining-manufacturing/percent-change-in-productivity.htm# 




