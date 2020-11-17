# burke-samantha-portfolio
CMU Fall 2020 - Telling Stories with Data 
<br>
# About Me
My name is Samantha Burke (she/her/hers). I am a part-time graduate student in the Heinz College pursuing a Masters of Science in Information Technology on the Business Intelligence and Data Analytics track. I moved from Colorado to the Pittsburgh area in January 2020. I am currently a full time Data Engineer at Tinuiti, a digital marketing agency. I integrate data from various marketing platforms (Google Ads, Bing, Google Analytics, Facebook Ads, Pinterest, etc) and build datasets for analysts to use for client reporting. I also build adhoc reports to summarize data across digital marketing channels to track high level performance. 
Fun fact about me - I have a Shiba Inu and he's the goodest of boys. He loves the snow and going hiking. He's been to the top of more 14,000ft+ mountains than most people!
<br>

<img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/about_me.JPG?raw=true" width="250">

# What I hope to learn
I hope to learn new strategies for visualizing data that I can utilize in my current role. I want readers to understand the point I'm trying to make without putting too much thought into it. I want to practice designing more creative and visually appealing graphics. The reports I've built in the past definitely need some spice!  
<br>

# Portfolio

<B>Assignment 2</B>
<Br>
<i>General Government Debt from OECD</i>
<iframe src="https://data.oecd.org/chart/69FP" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/69FP" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2015</a></iframe>
<Br>
<i>Graphic 1</i>
<div class="flourish-embed flourish-chart" data-src="visualisation/4266628"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<Br>
<i>Graphic 2</i>
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/4282157"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
The purpose of the graphic is to show how the USA's debt ratio compares to other countries for a given year. I chose to vizualize the data using a treemap because it's immediately apparent which countries have a larger or smaller debt ratio in comparison to the others. We emphasize the USA by coloring it differently than the other countries. All of the other countries are colored the same to because they are not the focus. Graphic 1 does not use coloring to emphasize specific countries. By changing the coloring to emphasize the US, I modified the intended audience. The audience for this graphic is more specific compared to the other graphic. Also, instead of looking at the data by year, like Graphic 1, this graphic highlights the debt ratio by country for a single year. Users can filter between years to see how countries compare to each other. The specific GDP-to-debt ratio values aren't as important in this scenario because we're trying to highlight how they compare generally.
<br>
<br>
 <b>Assignment 3 & 4 </b>
 <br>
 <i>Original Graphic</i><br>
 https://www-statista-com.proxy.library.cmu.edu/statistics/1060408/share-of-us-adults-with-allergies-to-select-foods-by-age/<br>
 <img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/statistic_id1060408_share-of-us-adults-with-allergies-to-select-foods-as-of-2018-by-age.png?raw=true" width="550">
 <br>
 <br>
 <i>Wireframes: initial and Balsamiq</i>
 <br>
 Initial sketch<br>
<img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/wireframe1.JPG?raw=true" width="550">
<br><br>
 Balsamiq Wireframe<br>
   <img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/wireframe2.JPG?raw=true" width="650">
<br><br>
 <i>Final Graphic </i>
 <br>
 <iframe src="https://public.tableau.com/views/Book1_16056288889290/Dashboard1?:showVizHome=no&:embed=true" width ="100%" seamless frameborder="0" scrolling="no"></iframe>
<br><br>
 
 <div class='tableauPlaceholder' id='viz1605634704345' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16056288889290&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_16056288889290&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16056288889290&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>
 
 
I went back and forth quite a bit on this visualization.
First, I sketched a wireframe that consisted of a bar chart with the ages grouped together (see above). 
Initially, I took an average of all the age groups to combine them together. I questioned whether this would be okay, but determined the values are still representative of the dataset. I also grouped some of the similar categories together. If I was comparing allergies within specific food groups, it would make sense to separate them all out, but in this case, I think they are fine together. Afterall, the audience is likely trying to get a summary, not exact figures.
This made the graph simple and easy to interpret. I still wasn't sure how to incorporate the large chunk of people in the 'N/A' or 'none' category. 
I considered excluding it until I showed my friend my initial wireframe. She understood the basics, but pointed out that if I'm going to show percentages, instead of showing just a piece, I should show the "full pie." At this point, I decided to completely redo my wireframe. Since I am showing a 100% of something, I decided to do a stacked bar. If I exclude a percentage of the pie, the visualization may lose reliability and seem incomplete. I showed another one of my friends my second wireframe. She was surprised that the "wheat" was smaller than the "shellfish" category, but overall she seemed to understand the graphic. She recommended trying some different color combinations. 
<br>
Compared to my inital sketched wireframe, my Balsamiq wireframe, and the source graphic, my final data visualization is pretty different.
If I did not get feedback from my friends, I wouldn't have considered a stacked bar. I chose the green color combination because it's a color that is typically used for health and food. I ended up showing 3 stacked bars instead of 1 to visualize each age group. I decided that comparing the age groups is an important part of the data.
My goal was to show the data in a more organized and simplified way. I wanted readers to understand what was going on immediately without having to ask questions.
