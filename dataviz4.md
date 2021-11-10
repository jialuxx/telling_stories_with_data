# 11/09 Assignment 3&4: Critique by design
[**Back to content**](/README.md)  
## Initial Dataviz
Here is a data visualization coming from [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations_vacc-total-admin-rate-total), which demenstrates amounts of people recieving primary covid vaccine series doses and booster doses from different manufactures.   
  
![Covid-19 Booster Dose Type by Primary Series Type](/images/Number-of-People-with-Booster-Dose-in-the-U.S.-by-COVID-19-Vaccine-Primary-Series-Chart.png)  
  
A brief annotation is attached under the initial paragraph:  
> **COVID-19 Booster Dose Type by Primary Series Type**:  
> This graph is limited to people who are fully vaccinated and have received a booster dose. It illustrates the vaccine manufacturer (i.e., vaccine type) of the COVID-19 primary series received, as well as the manufacturer of the booster dose received. The graph demonstrates that while some vaccine recipients received the same vaccine type for their primary series and booster dose, others received one type for their primary series and a different type for their booster dose.  
  
The reason why I choose this data visualization is that I did not understand it untill I spent 10 minutes readind its contexts. Actually it talks about a very interesting topic about how people choose their booster vaccines after they're fully vaccined with their primary doses. But this diagram might complicate the information and somewhat confuse the audience. What a great material for critique!  
## Critique
**What visualization are you ranking? Provide the title and web-accessible URL.** 
  
Covid-19 Booster Dose Type by Primary Series Type  
Source: https://covid.cdc.gov/covid-data-tracker/#vaccinations_vacc-total-admin-rate-total  
  
**Describe your overall observations about the data visualization here. What stood out to you? What did you find worked really well? What didn't? What, if anything, would you do differently?**    
  
I was first confused by the chart. It looked so complicated! There were so many colors and numbers that I didn't know where to focus my attention. I spent a lot of time trying to figure out what the indicators represented and then trying to figure out where they corresponded in the chart. This took a lot of eye travel. If I were a casual audience and took a glance at this chart, I wouldn't have much patience to try to understand it.  
  
However, this chart did give me some insight on how to compare percentages across categories. If there are only two categories (e.g., a comparison between Pifzer and Moderna), a proportional bar chart might be more effective.  
  
If I were a designer, I would consider leaving only the percentage numbers on the chart. There is no need to place both amounts and percentages. This repetition would be distracting. Then, I would remove those colored blocks on the Y-axis, leaving only the black font there. The other thing I'll do is delete the X axis. The percentages are already placed on the bars. the scale on the X-axis is not necessary.
  
**Who is the primary audience for this tool? Do you think this visualization is effective for reaching that audience? Why or why not?**  
  
I think the target audience is broad. Marketers for manufacturing companies, government officials involved with the vaccine, doctors, professors at public health schools, and the folk who intends to get the Covid vaccine are all likely to search for the information.  
  
I don't think it communicates the message effectively. There are too many distracting elements in the diagram that make it difficult to highlight key information. Even though I have some knowledge about data visualization and some practice, I was confused the first time I looked at it. Most importantly, understanding this complex diagram consumes a lot of time, and not every audience has that kind of patience.  
  
**Final thoughts: how successful what this method at evaluating the data visualization you selected? Are there measures you feel are missing or not being captured here? What would you change? Provide 1-2 recommendations (color, type of visualization, layout, etc.)**  
  
I think this method succeeds in recording the first impressions we get when looking at data visualizations. The benefit is that it helps designers put themselves in the shoes of their target audience. Reflecting on how to better convey the message is key to designing an effective data visualization. However, this method focuses more on the use of data and the effectiveness of the information, and somewhat neglects the analysis of visualization elements, such as colors and texts. It would be more helpful if it could be combined with Good Charts method to analyze data visualization. I would suggest adding some questions like." How do you feel about the elements in the chart, and do those that stand out accurately convey the most important information?"  
## Wireframe My Solution
  
![Redesign draft](/images/IMG_0352.PNG)  
  
I choose treemap to redesign the initial visualization.  
  **The Advantage of using treemap**:  
1. it is more inclusive for complex information, especially those containing more than 2 categories;
2. I can transform the base of the proportion(the number of people who receive Pfizer/Moderna/J&J/Unknown) to different sizes of rectangles so that I can avoid placing amount figures on the graph which might distract the audience;
3. it can more directly demonstrate the comparison of different proportions.  
**Changes**:
5. I do not want "Pfizer" to appear repeatedly and want to avoid redundancy of text. Therefore, I keep the original color scheme to distinguish the different booster types and put only percentage figures on the graph.
6. I also changed the original title "Covid-19 Booster Dose Type by Primary Series Type" to the current "How people choose vaccine booster after they receive primary doses". I hope this shift will help the audience better understand what this chart is trying to say.
## Test My Solution
Here are some feedbacks from my friends:  
**Q: Can you tell me what you think this is?**   
A1: something data about Covid vaccine, I notice there are "Pfizer" and "Moderna".  
A2: agreed. Besides, your header helps me recognize the information.  
**Q: Can you describe to me what this is telling you?**  
A1: Pfizer and Moderna are the top 2 choices.  
A2: Yeah, almost the entire diagram are yellow and green. J&J and unknow receivers also trun to Pfizer and Moderna.  
**Q: Is there anything you find surprising or confusing?**  
A1: maybe it's colors of J&J and unknown primary receiver. You can look at your keys. they are a little hard to distinguish.   
A2: I'm okay with that. But I'm a little cofused by your rectangle sizes. It seems not very consistent.   
**Q: Who do you think is the intended audience for this?**  
(They already know the data are from CDC website)  
A1: Audience of an seminar, like students or someone intersted in vaccine selections.  
A2: It can also be bussiness use. staff in Pfizer/Moderna companies disuss those information to promote/advertise their vaccine types.  
**Q: Is there anything you would change or do differently?**    
A1: Your color scheme looks okay. Maybe consider changing the format of your rectangles? The color arrangements looks a little bit messy now.  
A2: agreed. also you'd better add data sources to increase your credibility.    
**My Reflections:**     
Both of my friends gave me valuable suggestions which I will take on board as follows:  
* Adjust the color arrangement because both of my friends think this sketch looks a bit messy. I will try to adjust the placement of the rectangles to see how I can make them look neater;
* The rectangles are not very consistent in size, and I need to adjust them to its scale;
* Add the data source to the final version.  
In response to a friend's question about the difficulty of distinguishing between the two key colors, I'll still consider changing them to avoid the risk of misdirection, although I think this is a rather subjective feeling, as another friend said she was well clear.
## Final Dataviz
Here is the final edition of my data visualization. 
<div class='tableauPlaceholder' id='viz1636513049286' style='position: relative'><noscript><a href='#'><img alt='People who are fully vaccinated turn to Pfizer and Moderna for their booster vaccinesSource: CDC, covid-19 vaccinations in the united states ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CD&#47;CDCboosterdata&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CDCboosterdata&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CD&#47;CDCboosterdata&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' />
</object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1636513049286');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>  
   
**Some thoughts**
1. The rectangle size is determined by the number of people in each group, so that we directly see the population differences and and easily recognize biggest groups;
2. The color is determined by the type of primary vaccines rather than the booster type, which I used in the sketch. Instead, the booster type is directly placed in the graph with its percentage under the category of primary type. I think this color arrangement looks neater to the audience. 
3. Though none of my friends suggest the change, I transform the title to the conclusion that people tend to choose Pfizer and Moderna as their booster vaccine type, because I think it's the essential information the graph talks about and I want the audience directly know it from the title.
