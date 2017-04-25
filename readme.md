Fan Shi
========================================================
References:
https://github.com/rstudio/rmarkdown/blob/master/README.md
http://alignedleft.com/tutorials/d3/using-your-data/
The World Cup visualization coding used in the tutoring of this project
http://codepen.io/adamaoc/pen/ONvEKJ
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.legend
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.series#getTooltipText
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis#title
http://www.w3school.com.cn/html/html_paragraphs.asp
http://www.jianshu.com/p/b417230de1a0

##Introduction to the data in this study
In this project I use the Titanic data to create the plots and perform the analysis. 
As I used the Titanic data in the project 2, I am more familiar with it than with other optional data sets. Besides, I am a big fan of Titanic historical event, interested in the cause and result of it. Thus, I would still like to explore more on the Titanic data, and share my finding with more people to let them understand more deeply of about this historical event.

In my analysis for project 2, I noticed that people with different genders and classes have obvious variances in survival rate. This time, I will further study on these differences with more powerful data visualization tool, provided by HTML dimple.js. 

####The HTML tool
Here I used the RStudio to perform the HTML editing and running tasks. 

##Data Visualization


####Java script choice
Out of the two options, D3.js and dimple.js, I chose the latter one, as the in-class project that I learned in this project on the World Cup data analysis, was also coding with dimple.js. I referred to this HTML coding, and thus would like to choose dimple.js.

####Interactive data visulizatin
Following the basic ideas from the project 2, which initially analyze and visualize the Titanic data, to show the correlation between class, gender and survival rate, here I take advantage HTML and dimple.ds to make the data visualization more interactive and more informative. 

####Chart style choice
I choose the bar charts to demonstrate the correlations between each pair of variables that I am interested in. I will include the legend and color to distinguish the survival and death rate. I put the survival and death rate together on the same bar to let readers easily understand and find out (by the interactive function) of each value of rate they care about.

##Feed backs
1. You've done a fantastic job so far - as I've said you've taken on an ambitious project. There are quite a few changes for you to think about but please don't despair. the review process is all part of the learning curve.

There are various things you need to do before you resubmit:

add your key findings to the graphic with the help of titles and lead paragraphs
have a look at the comments on design choices - I'd strongly recommend showing survival rate instead of a graph for both survived and died. There are also some issues with colour coding and readability for the 2nd and 3rd findings. I've suggested either putting the variables into fewer bins or swapping chart types from bar to line charts.
add a new paragraph to your README file outlining your design choices.
Finally, please could you make sure you name your information file README. Officially it should be a markdown file but PDF is fine but make sure you name the file correctly so the Reviewer doesn't miss it.
Code Structure and Functionality

The visualization renders and any interactions or animations work as the reader interacts with the visualization.
Your visualisation renders perfectly - well done.
Large code chunks are commented and all complex code is adequately explained with comments. Comments are not overused to explain obvious code.
Comments are informative and well placed. I'd recommend adding a few more to the dimple code for readers who haven't seen dimple before?
The code uses formatting techniques in a consistent and effective manner to improve code readability.
Yes, well done. Formatting is both consistent and effective.
Visualization is Explanatory

The visualization centers on a specific, clear finding in the data.
You've made a great start here. You've analysed the data and focussed on four clear data stories.

What you need to bear in mind is that the rubric asks for an explanatory visualisation which stands alone without reference to the README file.

All you need to do is add your insights (which are well documented in your PDF) to the visualisation. This could be done by adding a title to each of your charts (see comments below about combining survived and died by using survival rate) and if needed adding a lead paragraph as well.
The selected finding is clearly communicated. Design choices foster communication between the reader and the visualization.
You're doing very well here. You've taken on an ambitious project with what is effectively a dashboard of FOUR findings and you've done a great job so far.

There are a few things you need to do to optimise reader/graphic communication further:

All charts

As mentioned above, please add a title and lead paragraph if needed to add your key findings to the graphic.

Instead of showing two charts (one for Survived and one for Died) I'd suggest showing Survival Rate instead. This way you can get your message across in a single chart. So for example for Passenger Class:

1st Class Females - 91 survived,3 died - therefore 91/(91+3) * 100 = 97% survival rate
3rd Class Males - 17 survived, 300 died - therefore 17/(300+17) * 100 = 5% survival rate
Survival Rate infers the Death Rate so you only need to show % survived.

Passenger Class

You've got a colour coding problem here. 1st is blue and orange, 2nd is orange and 1st. This will be solved if you just show survival rate. I'd also recommend using 1st, 2nd or 3rd instead of 1,2 and 3. It makes the label more accessible.

Sex/Fare

This is very hard to read. I'd strongly recommend putting the fares into different bins. Or you could work with Survival Rate and try a line chart with two lines - fare on the x-axis, survival rate on the y-axis and a line for male and female? Either way, please be careful about colour coding. Blue, Red and Orange have been used in the first charts so you should make sure they do not represent different variables in other charts.

Age

Again here I'd recommend either putting age into different bins (for example 0-20, 20-40 or perhaps child, teenager, adult) OR changing to a line chart. Age on the x-axis, survival rate on the y-axis, a line for male and female? As mentioned above, please be careful with colour coding.

Parch

These are looking great but again I'd recommend Survival Rate. Also, could you find a more accessible way of labelling Parch. For a reader who has never been seen the Titanic data before this means very little.
Design

A reader’s summary of the graphic would closely match the written summary in the README.md file, or a reader would identify at least 1 main point or relationship that the graphic attempts to convey.
You will pass this section once your key findings are on the graphic.
The visualization includes interaction or animation. The interaction or animation may be simple, such as a hover, tooltip, or transition. Interaction or animation enhances understanding of the data.
Tooltips are looking great.
Initial design decisions such as chart type, visual encodings, layout, legends, or hierarchy are included at the beginning of the Design section in the README.md file.
Your documentation is looking great but aside from outlining why you chose dimple, you haven't documented your design choices.

Please go into a bit more detail on why you chose the individual chart types, as well as visual encodings, layout, legends, or hierarchy. A paragraph will be fine.
Feedback and Iteration

Feedback has been collected from at least three people throughout the process of creating the data visualization. The feedback is documented in the Feedback section of the README.md file.
Great job collecting feedback. Documentation is spot on too.
The project includes evidence that the visualization has been improved since the first sketch or the first coded version of the visualization. All of the feedback is listed in the Feedback section of the README.md file. Most design choices and changes are accounted for in the Design section of the README.md file. If no changes were made to the visualization after gathering feedback, this decision is explained.
Well done including two versions of the file. Keep up the good work and include this version as well as your changed file when you resubmit.


2. You are almost done. When you submit the next version please attach the README file to the archive with design section provided. Good luck with the next submission!
Code Structure and Functionality

The visualization renders and any interactions or animations work as the reader interacts with the visualization.
The project renders almost fine, there the only issue with project layout (checked in Chrome and Safari):
Screen Shot 2017-03-28 at 21.32.01.png

Please, be aware the text starts from the same line. In addition, I would say that design information should not be presented at the project page, please move it into the README file.
Large code chunks are commented and all complex code is adequately explained with comments. Comments are not overused to explain obvious code.
There is a minimal set of comments, however, it is enough for code understanding.
The code uses formatting techniques in a consistent and effective manner to improve code readability.
The code formatting is almost great. There are couple of small issues (please refer "code review" section)
Visualization is Explanatory



The visualization centers on a specific, clear finding in the data.
Great job providing various outcomes! They all can be definitely explored in the charts. Even one static chart with a clear outcome is enough to pass this section, but you went further and created the advanced set of it. Great job!
The selected finding is clearly communicated. Design choices foster communication between the reader and the visualization.
You have done lots of improvements, I want to notice that you did not afraid to rework your project drastically. This will definitely make your skills stronger.

The only minor notice: please provide the header to the project page so you will catch the viewer attention just from the start.
Design

A reader’s summary of the graphic would closely match the written summary in the README.md file, or a reader would identify at least 1 main point or relationship that the graphic attempts to convey.
The visualization includes interaction or animation. The interaction or animation may be simple, such as a hover, tooltip, or transition. Interaction or animation enhances understanding of the data.
Tooltips are provided
Initial design decisions such as chart type, visual encodings, layout, legends, or hierarchy are included at the beginning of the Design section in the README.md file.
When you move the design section from the HTML to readme, this section is passed
Feedback and Iteration

Feedback has been collected from at least three people throughout the process of creating the data visualization. The feedback is documented in the Feedback section of the README.md file.
Feedback is collected
The project includes evidence that the visualization has been improved since the first sketch or the first coded version of the visualization. All of the feedback is listed in the Feedback section of the README.md file. Most design choices and changes are accounted for in the Design section of the README.md file. If no changes were made to the visualization after gathering feedback, this decision is explained.

3. What a fantastic submission. Things are really coming along and you are very close to meeting specifications.

There are various small things you need to do:

look at my design choices comments - there are three things that I think would make your charts more accessible as well as a couple of other non-required thoughts.
add feedback to the README file
include this version of the visualisation when you resubmit - hopefully the feedback will also tell the reader more about the evolution of the project?
I'd also highly recommend adding a few more comments to your code but this is not required.
Code Structure and Functionality

The visualization renders and any interactions or animations work as the reader interacts with the visualization.
Yes, well done - your visualisation renders perfectly.
Large code chunks are commented and all complex code is adequately explained with comments. Comments are not overused to explain obvious code.
Comments are informative but there are not many of them. I would highly recommend adding some more for readers who have never used dimple before.

However, as the previous reviewer passed this section I will meet specifications.
The code uses formatting techniques in a consistent and effective manner to improve code readability.
Formatting is consistent and effective - brilliant.
Visualization is Explanatory

The visualization centers on a specific, clear finding in the data.
You've done a great job here - four specific, clear data stories giving an overall picture of survival rate across various factors. Fantastic.
The selected finding is clearly communicated. Design choices foster communication between the reader and the visualization.
I am aware that the previous reviewer met specifications here but there are a number of small quick things that I feel you could do to foster better reader/graphic communications.

It is often helpful to put yourself in the mindset of a reader coming to your visualisation for the first time. Would they understand your message in that first crucial 10/15 seconds? Is there anything you can do to make it clearer?

With this in mind I have a couple of required suggestions:

labels - S_V, Pclass and Parch mean very little to a reader who hasn't seen the Titanic dataset previously and Age_group would look smarter without the underline. I'd highly recommend changing these to something more accessible. Here are two links that will help alter tooltip text, change axis titles.
legend order - two charts are died then survived, two charts are survived then died. It would be neater if they were consistent. Here is a link that should help.
age group - your columns and labels seem to be out of sync. Possibly because you have some records with ages which don't fit your bins? 0 or Null values? I'd highly recommend filtering the data before drawing this chart - see link here to help.
Finally, two thoughts that are not requirements but for you to consider:

I'm wondering whether you've taken into account number of passengers in each group when coming to your conclusions? Particularly with the final chart? Are there many families with 4+ children? Could these be outliers skewing the data? I don't know the answer so I could be wrong but it is worth checking. Even if you don't have time to incorporate the number of passenger count data into your chart you could mention it in your analysis?
do you think your graphic would look better with a bit of variety in font size and layout? Perhaps a larger, bolder title and a mid size for each of the chart titles? A space between the charts and making sure the text and titles are centered on the page would add that professional touch too.
Design

A reader’s summary of the graphic would closely match the written summary in the README.md file, or a reader would identify at least 1 main point or relationship that the graphic attempts to convey.
Yes, brilliant - the message in both is consistent.
The visualization includes interaction or animation. The interaction or animation may be simple, such as a hover, tooltip, or transition. Interaction or animation enhances understanding of the data.
Great interaction in the form of tooltips.
Initial design decisions such as chart type, visual encodings, layout, legends, or hierarchy are included at the beginning of the Design section in the README.md file.
Great job documenting your design choices.
Feedback and Iteration

Feedback has been collected from at least three people throughout the process of creating the data visualization. The feedback is documented in the Feedback section of the README.md file.
There is no mention of feedback in the README file. You need to include this when you resubmit. Remember you need feedback from at least three people - you can include this review and the previous review if you want as long as you clearly documented the feedback and your response.
The project includes evidence that the visualization has been improved since the first sketch or the first coded version of the visualization. All of the feedback is listed in the Feedback section of the README.md file. Most design choices and changes are accounted for in the Design section of the README.md file. If no changes were made to the visualization after gathering feedback, this decision is explained.
I'm afraid there are no previous versions provided and you haven't gone into any detail on the evolution of the project in the README file. Please include this version when you resubmit.


## Iterations
Based on the previous 3 feedbacks, I made numerous changes on my codes:

1. Added insignts to each figure.
2. Changed the survial counts to survival rates.
3. Put ages into different bins.
4. Explained my design choices.
5. Put the design information into readme.md.
6. Removed the records where age information is missing.
7. Fomatted my code to have the lines aligned better.
8. Changed the x and y titles for readers to understand my analysis more easily.
9. Formatted the main title, figure titles and space between each section to make it look clearer.
10. Adjusted the legend order.
11. Included the readme file and historical versions of html files. Actually, I submitted the readme file and html file the first time I submitted, but I did not know I needed to include them every time I submited my modified project...

