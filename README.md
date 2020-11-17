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



<b>Assignment 3 & 4</b><Br>
<i>Original Graphic</i><Br>
This graphic shows the different types of food allergies adults have, broken into age groups. It's based on an online survey with over 2,400 respondents. As someone who is impacted by food allergies, this type of data is interesting to me. The data is easy to understand and straightforward. Ultimately, I chose this graphic specifically because I felt like I could improve it.<br>
https://www-statista-com.proxy.library.cmu.edu/statistics/1060408/share-of-us-adults-with-allergies-to-select-foods-by-age/<Br><br>
<img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/statistic_id1060408_share-of-us-adults-with-allergies-to-select-foods-as-of-2018-by-age.png?raw=true" width="550">
<Br><Br>
<i>Final Graphic </i><Br>
 I went back and forth quite a bit on this visualization. First, I sketched a wireframe that consisted of a bar chart with the ages grouped together (see below). I thought this would make the graphic easier for the audience to digest while still properly communicating the data. I also grouped some of the similar categories together. It seemed like grouping similar foods together (for example, strawberries, mangos, kiwis as fruits) would simplify the visualization without taking away from the data. One of the challenges I ran into was determining how to incorporate the large chunk of people in the 'N/A' or 'none' category. I knew this was something I wanted to change based on the source graphic. I considered excluding it until I showed my friend my initial wireframe. She understood the basics, but questioned where the rest of the percentages were. She pointed out that if I'm going to show percentages, instead of showing just a piece, I should show the "full pie." At this point, I decided to completely redo my wireframe. If I exclude a percentage of the pie, the visualization may lose reliability and seem incomplete. I showed another one of my friends my second wireframe. This wireframe was completed in Balsamiq. Instead of a bar chart, I created a stacked barchart. The similar categories are still grouped together and I combined the ages into one. She was surprised that the "wheat" was smaller than the "shellfish" category, but overall she seemed to understand the graphic. She recommended trying some different color combinations. 
<br>
After evaluating the feedback from my friends, I started creating my re-design in Tableau. First, I cleaned up the data file by deleting blank rows. Next, after connecting to the data, I created groupings in Tableau to combine the values into the appropriate categories (as noted on the bottom of the final graphic). Then, I altered the data types so values display properly in Tableau. I took my friend's recommendation and tried different color schemes. I ultimately went with shades of green because it's a color that's often related to health and food. I started creating my single stacked bar chart but I decided I should try to create a stacked bar for each age group. I felt hesitant about grouping them into 1 age category in the first place. Displaying it this way brought different things about the data to my attention. First of all, the two younger groups have over 100%. This must mean that some respondents reported more than one allergy. Next, I realized that the oldest age group has over 10% more people without allergies compared to the other groups. I completely missed that with my wireframes. Also, I added a tooltip and highlight filter to make comparing specific allergy types between the age groups easier. If you hover over an area of a chart, the tooltip shows the category name and percentage from each group. Also, the highlight tool can be used to isolate a specific allergy type across the age groups.
Compared to my inital sketched wireframe, my Balsamiq wireframe, and the source graphic, my final visualization is pretty different.
The feedback from my friends was valuable and guided me towards a better design. I am glad I did not combine the age groups and created seperate stacked bars. After seeing the data displayed differently, I realized that comparing the age groups is an important part of the data. Overall, my goal was to show the data in a more organized and simplified way. I wanted readers to understand what was going on immediately without having to ask questions.
<iframe src="https://public.tableau.com/views/Book1_16056288889290/Dashboard1?:showVizHome=no&:embed=true" width="95%" height="1100" seamless frameborder="0" scrolling="yes"></iframe>
<i>Wireframes: initial and Balsamiq</i>
 
Initial sketch<br>
<img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/wireframe1.JPG?raw=true" width="550">
<br><br>
Balsamiq Wireframe<br>
<img src="https://github.com/stburke-cmu/burke-samantha-portfolio/blob/main/images/wireframe2.JPG?raw=true" width="650">

