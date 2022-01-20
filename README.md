# Assignment 1: Protests
The past few years in the United States, there has been a surge in protests in support of Black Lives Matter, gender equity, and other social issues. In this assignment, you'll work with data from [CountLove](https://countlove.org/) -- the same data often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the New York Times -- to learn more about demonstrations over the past few years.

By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundational programming skills in R.


## Background Research
Before diving into this (or any) dataset, it's important to have _domain familiarity_ (i.e., to know something about the topic). As preparation, I'm asking that you read **three articles** about protests in the U.S., and provide a brief 1 - 2 sentence summary or takeaway from each one.

In the section below, create an **unordered list** of the three articles you found. Make sure to provide an appropriate markdown link (_not_ just the URL) to the article in addition to your 1 - 2 sentence summary.

- <https://www.nytimes.com/interactive/2020/07/03/us/george-floyd-protests-crowd-size.html> 15-26 million people have participated in the George Floyd protests, making this the largest movement in the history of the US.
- <https://www.usnews.com/news/national-news/articles/2021-01-12/the-us-capitol-riots-and-the-double-standard-of-protest-policing> While a group of majority Black protestors gathered around the White House, police officers stood their ground using pepper spray and batons. Many concerns arise about how this situation was handled compared to the Capitol storming.
- <https://www.politico.com/news/2021/10/10/college-students-pandemic-protections-515709> Students at Texas A&M gathered to protest the lack of COVID-19 precautions at their learning institution after a student died of COVID.

## Accompanying Image
In this section, please **display one image** to accompany your text, and describe _why_ you included it (~2 - 3 sentences). This will require that you download an image into your project folder. In your description, use **bold** and _italics_ (at least once, for practice) to emphasize some of your points.

![](https://www.bostonherald.com/wp-content/uploads/2020/07/AP20185507092914.jpg?w=863)  
- I chose this picture because I felt that it really represented the protests in 2020. There were countless protests involving *arson and other dangerous acts*, and it was all about the state of our country, which is what the **upside down flag** represents.


## Analysis
At this point, you should open up your `analysis.R` script to begin working with the data. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- What does the difference between the mean and the median tell you about the *distribution* of the data?

  The data is skewed positively skewed, and the median being so low suggests that much of the data are lower values.
- Does the number of protests in Washington surprise you? Why or why not?

  The number of protests in WA doesn't really surprise me that much because of how our state is very "activist" - like.
- Looking at the `state_table` variable, what data quality issues do you notice, and how would you use that to change your analysis (no need to actually change your analysis)?

  I noticed that the states were sorted alphabetically, and that some were much higher numbers than others.
- Does the change in the number of protests from 2019 to 2020 surprise you? Why or why not?

  No because of the political turmoil involving the election.
- Do a bit of research. Find at least *two specific policies* that have been changed as a result of protests in 2020. These may be at the city, state, or University level. Please provide a basic summary, as well as a link to each article.
A policing reform bill passed in Washington, D.C. will require officers to undergo further training on racism and white supremacy.

  The measure to make officers’ records public is among several police accountability bills moving through the state legislature.
  Another policy would provide all state troopers with body cameras and ensure that police officers provide medical and mental health attention to people in custody.
  <https://www.usatoday.com/in-depth/news/2020/06/18/2020-protests-impact-city-and-state-changes-policing/5337751002/>
- Take a look (`View()`) your `high_level_table` variable. What picture does this paint of the U.S.?

  There's lots of education protests and "others."
## Critical Reflection
Now that you have had time to work with the data and visualize it, I want you to practice thinking critically about the dataset we provided. An important part of data analysis is reflecting on the assumptions, limitations, and gaps in your datasets. Remember that all datasets have to make assumptions and not all assumptions are bad or unreasonable! Practicing these skill will help you in your career to be self critical and ethically alert.

For this section, please write 2-3 sentences for each of the reflections below:

- How was the dataset collected and who collected the data?

  Nathan and Tommy collected the data by keeping track of local news reports every night. Nathan and Tommy were regular students who liked the work on projects such as this one.
- What assumptions does the dataset make? List atleast two assumptions you identified. For inspiration, check out this [blog post](https://towardsdatascience.com/check-your-assumptions-about-your-data-20be250c143) that describes one method for identifying data assumptions.   

  They assume that all protests covered on the local news were accurate in terms of attendees and location. Furthermore, they assume that their news station has no bias towards any political side which could sway numbers.
- What data is missing from the dataset? Think about if there are any data points you would have liked to have seen in the dataset.

  I think that length of the protest could be good. Knowing how long the protest lasted might tell us how significant some are compared to others.
## Final Thoughts
When you are finished, with your analysis, please answer the following questions in 1-2 sentences each.

- What about the analysis surprised you?

  Just the overall number of protests was surprising to me.
- What parts of this analysis did you find challenging?

  Mostly just the markdown stuff, writing down my thoughts is a fun twist compared to all the coding.
- What types of analysis do you wish you were able to do with the dataset, but currently don't have the technical skills to do?

  Making more graphs and charts about the protest to visually show the data.
