Download Link: https://assignmentchef.com/product/solved-st558-project-1-vignettes
<br>
5/5 - (1 vote)




Project 1 Instructions

Vignettes are explanations of some concept, package, etc. with text, code, and output interweaved. We already know how to make them with R Markdown!

Project Objectives

This project involves creating a vignette (HTML with table of contents) about reading in data and exploring it. Everyone is paired with another student from your group of four and will work with their partner (see below for group info).

Group

Group A Group B Group C Group D Group E

Group F Group G Group H Group I

JSON Partners

Evan Elms, Cameron Evangelista Kelly Craig, Sejin LimJesse DeLaRosa, Sophia Melenikiotis Heather Barker, Shantel Butler Kristin Calvert, Xingyue Gong

Greg Janesch, Hongliang Liu Kyle Beard, Laura Clebone Tyler Brigman, Stuart Cary Avisek Choudhury, Pierre Cobb

XML Partners

Ariel Macari, Xiyou Zhou Anchal Saxena, Michael Yan Steven Miller, Clayton Ramsey Jin Hong, Ben PfefferPhillip Rodriguez-Lebron, Adam WeimerskirchRyan McGovern, Steve Sortijas Nick King, Quin NelsonErkang Ou, Melissa RineerYan Shi, Thom Teears

The JSON group will create a vignette about reading JSON data into R with an example that includes basic exploratory data analysis (summaries and graphs – more details on this later). The XML group will do the same with an XML data set.

Group Work

Each group will collaborate through GitHub. • One partner should make a repository

• That person should add all three other group members to the project– Go to settings, collaborators, and search for your groupmates (usernames may need to be shared)

1

• All changes to documents should be done on the repositories (this way when grading I can see how much each group member contributes &#x1f642;

• The JSON partners will work independently of the XML partners but incoroporate feedback given by their counterparts (and vice-versa).

<ul>

 <li>–  At some point the JSON partners should ask the XML partners for feedback (with a reasonable amount of time for them to respond). Each of the XML partners must submit at least one pull request on the vignette (and vice-versa).</li>

 <li>–  To do so, the XML members should first fork the repository</li>

 <li>–  Clone the repo locally (i.e. grab the clone URL and start a new project in R Studio (version control –&gt; git) and put in the repo URL)– Make comments/edits locally and commit to your forked repo– Perform a pull request to merge your branch to the original repo master branch</li>

</ul>

2

– Now the JSON group can view pull requests and choose which changes to include

Vignette Content Details

The components of your vignette that must be present include:

<ul>

 <li>Describe your type of data (JSON or XML). What is it, where does it get used, and why is it a good way to store data? This should be detailed enough that someone that hasn’t seen that type of idea would have a good idea what they are dealing with. You should link to references where applicable.</li>

 <li>Discussion of possible packages/functions that are available for reading your type of data into R. Choose one and explain why you’ve chosen it.</li>

 <li>Find a dataset of your type (JSON or XML) and describe where you found the data, how the data was collected, what the variables are, etc.– The data you read in should have at least two categorical variables and two quantitative variables.</li>

 <li>Read in the data set describing the options your package’s functions allow.</li>

 <li>Perform basic exploratory data analysis that reveals a meaningful idea that you would reasonable want to investigate further. Not all things reported need to show something meaningful (i.e. graphs that show no relationship are fine) but you should end up with a solid lead that you would pursue further.

  <ul>

   <li>–  At some point you should create a useful function(s) to do something meaningful with the data or customize the way you read the data in.</li>

   <li>–  You should create a new variable.</li>

   <li>–  You should create some contingency tables and numeric summaries by some of your categoricalvariables</li>

   <li>–  You should create some plots (at least a side-by-side bar plot, side-by-side box plots, and scatter plots with coloring)When you are finished, you should post a link to you/your partner’s repository for us to use along with a rating score for each of your three other group members. (0 – implying that member didn’t contribute in their assigned way to 100 – implying that member contributed fully in their assigned role.)All vignettes will be shared with the class after the due date and grading are finished.</li>

  </ul></li>