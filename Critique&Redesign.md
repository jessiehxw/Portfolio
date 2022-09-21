## Assignment 3 & 4: Critique by Design

> September.20th   
> [Source website for the original visualizations](https://research.com/education/student-stress-statistics)

### Why these charts need redesign?
As the semester proceeds, CMU students are experiencing an increasing amount of stress with a more significant workload and exams. Thus, I searched "College Student Stress Report" online and clicked on the first result that popped up. The report revealed different stress sources for students, including grades, bullying, homesickness, etc. It contains numerous visuals throughout the information. However, I found the visualizations poorly designed with a bad layout, wrong choice of color, and chart types. These flaws prevent them from adding value to the article, and I would love to see them delivered in a better form.  

Below is how I rate the visualizations on this site with the Data Visualization Effectiveness Profile:  

<img src="Pictures/EffectivenessMatrix.png" alt="Sketch of the Pie Chart" width="700"/>

Overall, the charts on the site are functional as basic visualizations with accurate information and the necessary components. However, they are not appealing to readers and lack intriguing insights. Basically, not "interesting" enough to impress readers with the selected contents and persuade them with the given facts.

#### Critique on the Original Charts
There are multiple charts on this page. In the Google form, I critiqued on several of them with their positive and negative aspects. Since I don't have time to redesign every single one of them, I chose to focus on one pie chart and one donut chart.

#### Pie Chart:
<img src="Pictures/how-stressed-are-student.png" alt="How Stressed are Students?" width="700"/>  

Pros:
- clear chart titles that sum up the content
- show comparison between different categories

Cons:
- The sequential colors used for different categories are too similar
- Usually, deeper colors represent high density, but it is the opposite. The most significant stress is in the brightest blue. This can confuse people at first look
- The numbers are poorly positioned. For small slices, the number doesn’t fit in the piece.
- The current title is a good summary but doesn't tell a good story. It can be changed to something more informative.

#### Donut Chart:
<img src="Pictures/What-Do-International-Students-Miss-About-Home.jpeg" alt="What Do International Students Miss About Home?" width="700"/>

Pros:
- Four donut charts show the proportion of each group side by side. Since they don't add up to 100%, donut charts are good choices for showing percentages.

Cons:
- The two zeros at the end of each percentage value are unnecessary.
- There is no emphasis on the chart with close percentages, single color, and small labels below each donut.
- As all the charts have the same color, there is no need to have a color legend below each one.
- According to the context (“These sounds include people talking in their native language (50%), local community hustle and bustle (26%), public transport sounds (25%), and native wildlife (20%).”), the “Native language conversations” and “native wildlife noises” are part of the “sounds of their hometown.” However, the chart compares them at the same level as separate categories, which is misleading.

### Sketch some ideas!
After evaluating the good and bad's of the two charts, I brainstormed ideas for improving each chart and sketched them in different layouts, chart types, and colors.

#### Pie Chart Remake:
<img src="Pictures/Pie-chart-sketch.png" alt="Sketch of the Pie Chart" width="700"/>

Firstly, I rewrote the title and subtitle to be more informative. Compared to "How Stressed are Students?", I think "Students are stressed out" is a more powerful title that directly states the core meaning of the chart directly. Then for the subtitle, I wrote, "One in every two students claims to experience more than average amount of stress," which further illustrates the severe problem.

Then, I reordered the pie chart slices from large to small. I moved the number outside for the smallest slice that couldn't fit the number and connected it to the slice with a line. Instead of having a legend at the bottom, I repositioned the labels next to their corresponding slice to reduce readers' eye movement.

The original sequential colors used are too close to each other, which makes it hard to align the different pieces. So I decided to change it into diverging color between red and green. (Red for the "Tremendous" stress, and green for "Not a bit" of stress, as people tend to perceive green as good and red as a warning.)

#### Donut Chart Remake:
![Donut Chart Remake Sketch](Pictures/Donut-chart-remake-sketch.jpeg)

I think the donut chart is a good answer for this piece of data but not the best. Since this chart is more about displaying the different things that international students miss about home and what they miss more compared to others, I chose to amplify the difference between percentages of each element by using Treemap. 

Also, since "Native Language", "Local Community Hustle and Bustle," "Public Transport Sounds," and "Native Wildlife noises" are subcategories of "Sounds of their hometown," I came up with the idea of having a treemap inside treemap. So I split the "Sounds of their hometown" rectangle into small rectangles representing each subcategory. Then, if possible, there can be a transition animation between the two treemaps unfolding the "Sounds of their hometown" into more detailed sounds. And if that is too hard to realize, we can have both charts displayed side by side. 

I repositioned the labels with larger font inside the corresponding rectangles alongside the percentages. 

### Get some Feedback! 
#### Student, early 20's
Pie chart:
>Can you tell me what you think this is?  
"This is a Pie chart represents groups of students experiencing different level of stress." 

>Can you describe to me what this is telling you?   
"Most students are experiencing more than average amount of stress."

>Is there anything you find surprising or confusing?  
"I'm surprised that there is actually 2.4% students that are not stressed at all :)"

>Who do you think is the intended audience for this?  
"I think the intended audience would be some researcher, educators, or anyone who works in educational industry." 

>Is there anything you would change or do differently?
""







 