# Assignment 5: Final Project Proposal

**Due Date:** October 30st, 11:59 PM

## Objective

For this assignment, you will propose your final project, which can be done solo or in a group of two. Your proposal will include an outline of the project you intend to develop, the data you will use, your audience, and the tasks your project will help users perform. This assignment is designed to help you plan and organize your project effectively before implementation.

## Instructions

Your proposal must cover the following areas. **But don't overthink it; this is just a preliminary. Many details will change as you learn more about your project. You just need to make some decisions and do some digging for now.**

### 1. Topic
The **topic** refers to the broad area or field that your project will focus on. This is the overarching theme or domain under which your specific visualizations will fall. We highly suggest choosing a topic that you are passionate about or one that you enjoy. Some possible areas to explore include:
  - **Sports**: Analyze players' performances, team stats, or match outcomes.
  - **Health**: Visualize health trends, fitness data, or medical research outcomes.
  - **Entertainment**: Visualize trends in music, movies, gaming, or streaming services.
  - **Environment**: Explore climate data, deforestation rates, or pollution trends.
  - **Technology**: Dive into tech trends, product sales, or the growth of tech companies.
  - **Politics**: Analyze election results, voter demographics, or policy impacts.
  - **Education**: Visualize student performance, education accessibility, or curriculum outcomes.
  - **Economics**: Explore GDP growth, inflation rates, or the distribution of wealth.
  - **Transportation**: Analyze traffic patterns, public transport usage, or urban mobility trends.
  - **Social Media**: Examine trends in social media usage, hashtag popularity, or content engagement.
  - **E-commerce**: Visualize online shopping trends, product categories, or user behavior.

Provide a clear description of the **topic** you’ve chosen.

### 2 Subject
The **subject** refers to the specific question, pattern, or phenomenon that you will analyze within your chosen topic. It narrows down your focus to the particular aspect you will be visualizing.

For example:
- If your **topic** is **Sports**, your **subject** could be: *"Analyzing player performance in the 2023/24 soccer season"*.
- If your **topic** is **Health**, your **subject** could be: *"Visualizing the spread of a particular disease over the last five years."*

Clearly describe the **subject** you will explore within your topic.

### 3. Your Goal
As the designer or author of the visualization, what is your goal? Is it to communicate a message? Is it to solve a problem? Is it to improve some specific decision-making performance for something? Is it to get people to laugh? Think about and write about your goal to create the visualization. 

### 4. Tasks
Describe the tasks that your visualization will help users perform. What will your users be able to do with your visualizations? Refer to our tasks slides and the Munzner chapter. But some Examples include:
- Compare data (e.g., compare player performance across seasons).
- Explore trends (e.g., track stock prices over time).
- Identify patterns or outliers (e.g., find patterns in social media engagement).

### 5. Target Audience
Who will use your visualization? Define your target users or audience. These could be:
- **Experts** in the field (e.g., data scientists, sports analysts).
- **Non-experts** (e.g., casual fans, general public).
- **Students** learning about the topic.
- **Businesses** looking for insights in a particular area.

Clearly specify the target audience and why this group will benefit from your visualizations.

### 6. Data Source & Description
Look for data sources. Describe the dataset(s) you plan to use for your project. Tell us what you looked for and what you couldn't find. Include:
- **Data Source**: Where the data comes from (e.g., public datasets, APIs).
- **Data Columns**: Key columns and data types.
- **Description**: What each column represents and why this data is relevant to your project.

If you don’t have a dataset yet, explain how you plan to find or collect it. Explain what information you might need. 

---

## Submission Instructions

1. **Submit a PDF** containing the details of your project proposal.
2. Ensure your file is named as follows:  
   **Assignment5_FirstNameLastName.pdf**

---


## Example Project Proposal

### Topic: **Entertainment**

### Subject: *Analyzing Box Office Revenue Trends of Superhero Movies Over the Past Decade*

In this project, I will explore how superhero movies have performed at the global box office between 2012 and 2022. The aim is to identify trends in revenue growth, the impact of certain movie studios on overall box office success, and the role of leading actors or directors in influencing box office performance. 

The visualization will focus on movies produced by major studios such as Marvel Studios, Warner Bros (DC Comics), and others. Specific analysis will also be done to compare the success of individual franchises like *The Avengers*, *Batman*, and *Spider-Man*.

### Goal: **I want to make a case for how superhero movies have overtaken the movie industry and have hurt other movie genres**.

### Tasks:
1. **Track revenue trends**: The users will be able to observe how box office revenue for superhero movies has evolved over time.
2. **Compare franchises**: Users will be able to compare the performance of individual superhero franchises and identify which franchise dominates the box office.
3. **Identify patterns in actor/director influence**: The users can explore if certain actors or directors consistently appear in top-grossing movies and how their involvement impacts the success of superhero movies.
4. **Analyze regional performance**: Viewers can explore box office revenue differences by region (e.g., North America vs. International sales).

### Target Audience:
- **Movie enthusiasts and fans of superhero films**: This audience will find the project engaging as it provides insights into the success of their favorite franchises and actors.
- **Film industry analysts**: Analysts can use the visualization to detect trends, compare franchises, and predict future success based on the historical data.
- **Students studying film or media**: This tool can help students understand the relationship between star power, production decisions, and revenue generation in the film industry.

### Data Source & Description:
- **Data Source**: The dataset will be sourced from publicly available movie databases such as [Box Office Mojo](https://www.boxofficemojo.com/), [The Numbers](https://www.the-numbers.com/), or [IMDB](https://www.imdb.com/). Additional data could be extracted via APIs if necessary.
- **Data Columns**:
    - **Title** (*Nominal*): The title of the movie. This helps to identify the movie and will serve as the primary key when combining data from different sources.
    - **Release Year** (*Ordinal*): The year the movie was released. This column will be used to analyze trends in box office revenue over time and compare performance across different years.
    - **Studio** (*Nominal*): The name of the production studio (e.g., Marvel Studios, Warner Bros). This is relevant for comparing how different studios perform in terms of box office success, particularly with superhero movies.
    - **Genre** (*Nominal*): The genre of the movie, with a focus on superhero films. This column will allow me to filter and analyze only superhero-related movies and compare them with other genres where applicable.
    - **Global Box Office Revenue** (*Quantitative*): The total worldwide box office revenue in US dollars. This is crucial for understanding the overall financial success of each movie and will be used for comparisons and trend analysis.
    - **Domestic Box Office Revenue** (*Quantitative*): Revenue generated from North America. This column is essential for comparing regional performance and understanding how movies perform in the domestic market.
    - **International Box Office Revenue** (*Quantitative*): Revenue generated from regions outside of North America. This column will provide insight into global appeal and international performance of superhero movies.
    - **Director** (*Nominal*): The name of the director. Analyzing this column will help identify whether certain directors contribute to higher box office revenues and if director reputation correlates with financial success.
    - **Lead Actors** (*Nominal*): The main actors featured in the movie. This column will be useful for exploring whether certain actors contribute to higher grossing movies and for identifying recurring actors across successful superhero franchises.
    - **IMDb Rating** (*Quantitative*): The average user rating of the movie on IMDb, on a scale from 1 to 10. This rating provides insight into audience reception and will be used to compare critical and financial success.
    - **Rotten Tomatoes Score** (*Quantitative*): The aggregated critic score from Rotten Tomatoes, presented as a percentage. This column will help compare critical reception with box office performance and determine whether higher critic ratings correlate with revenue.



---
Let us know if you need further guidance!
