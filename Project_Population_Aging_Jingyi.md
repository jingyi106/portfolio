# Population Aging Analysis

## Outline and Background
The population aging is a serious social problem in the world. 
The global population is aging. The proportion of older people in almost every country in the world is increasing, which is likely to be one of the most important social trends in the 21st century. Many aspects will be impacted, for example, labor force, social insurance, family structure, and generation relationship. Aging will cause political and financial pressure on governments regarding the public health system, pensions, and labor market.

Different countries face different aging population problems, for example, in South Korea, one of the counties with the most serious aging of the population, the portion of the elderly population is projected to grow at the fastest pace in the world from 14.9 percent in 2019 to 46.5 percent in 2067. 
Different policies are formulated to relieve the problem. The three-child policy in china is released in 2020 to address the more serious aging problem.

The problem of supporting the elderly is serious with the increase in the elderly population. For this project, I would analyze the aging of the population all over the world, mainly focusing on the share of the dependent population, which is calculated as the total elderly (>65) and youth population (15-64) expressed as a ratio of the total population.


## Sketches
Visualization 1: Line charts to compare the change of aging population proportion among 5 counties with the most serious aging population problem

![1](https://user-images.githubusercontent.com/100049171/192169170-30128a4e-dc63-4df9-b98c-6c94d1e8140e.jpeg)

Visualization 2: Sorted bar charts to compare the aging population proportion in 2021 among all counties in 2021

![2](https://user-images.githubusercontent.com/100049171/192169222-f40e0fea-3abd-4820-9477-b3caefea3ac9.jpeg)

Visualization 3: With a world map background, each circle represents the share of the dependent population of a country. The larger the circle is, the more serious supporting the elderly will be.

<div class='tableauPlaceholder' id='viz1664920104877' style='position: relative'><noscript><a href='#'><img alt='Top 50 Countries With the Largest Percentage of Older Adults ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;Map-Top50CountrieswiththelargestPercentageofOlderAdults&#47;map&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Map-Top50CountrieswiththelargestPercentageofOlderAdults&#47;map' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;Map-Top50CountrieswiththelargestPercentageofOlderAdults&#47;map&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
 var divElement = document.getElementById('viz1664920104877'); 
 var vizElement = divElement.getElementsByTagName('object')[0];    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
 var scriptElement = document.createElement('script');
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
 vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Visualization 4: Comparison between counties with the most serious and least serious supporting the elderly problem.

![4](https://user-images.githubusercontent.com/100049171/192169260-39aecc85-ce68-43d8-9932-2b64d79de0a8.jpeg)

## Data
Data source:[https://data.oecd.org/pop/elderly-population.htm](https://data.oecd.org/pop/elderly-population.htm)

The data is from the public website of Organization for Economic Cooperation and Development (OECD). There are 5 datasets available for the analysis of aging of the population
Dataset1: Population
Dataset2: Young population
Dataset3: Elderly population
Dataset4: Fertility rate
Dataset5: Working age population
Dataset6: Old-age dependency ratio

There are two reasons for choosing this data source: firstly, it’s publicly accessible. It’s official data from Organization for Economic Cooperation and Development, so it should be accurate and trustable. In addition, not only data for the elderly population is provided, but also data for the young population and working age population, which is comprehensive for comparison and analysis. 

For this project, I will mainly use datasets 2,3,6 to address the problems of supporting the elderly. For each dataset, 55 countries are included. The data from 1950 to 2021 is provided, which enables us to analyze from both a time-series perspective and a country-comparison perspective. 


## Method and medium:
I will use Tableau as the visualization software. The thoughts of visualization are provided as follows:
1.	Select the top 5 counties with the highest proportion of the elderly population in 2021, and visualize the change of proportion from 1950 to 2021
2.	Select the top 5 countries with the lowest proportion of the elderly population in 2021, visualize the change of proportion from 1950 to 2021
3.	Calculate the share of the dependent population of each country, visualize and compare the results
4.	Select counties with both the most serious and least share of dependent population, and go deep into related public policy to analyze the reasons behind those visualizations
5.	Provide policy suggestions to address elderly people's supporting problems.

To present, shorthand will be the medium because it’s user-friendly for people with no UI/UX background, and the visual web created by shorthand is easy to share.





 

