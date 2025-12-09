<h1>1990s Netflix Movie Analysis — Exploratory Data Analysis Project</h1>
<img src="images/Netflix/9251177d3d4de55e03b0ce7f515b391f.jpg" height="300 style="display: block; margin: 0 auto;">
 
For this project, I explored a dataset of Netflix titles to better understand movie trends from the 1990s. The goal was to analyze movie durations, identify common patterns, and investigate how many short action movies were produced during the decade. This analysis simulates the type of research a production company might do when developing nostalgic or era-inspired content.

<h3>Objective</h3>
<ul>
  <li>Focus on movies released between 1990 and 1999</li>
  <li>Determine the most common movie duration during that decade</li>
  <li>Count the number of short action movies (defined as < 90 minutes)</li>
</ul>



<h3>Approach</h3>

I began by filtering the dataset (netflix_data.csv) to include only movies (not TV shows) released in the 1990s. After isolating the decade, I analyzed the distribution of movie durations using basic exploratory data analysis techniques.

To identify the typical runtime, I looked at the frequency of each duration value. Movie runtimes tend to cluster, so instead of a single exact mode, I used an approximate most frequent duration, saved as an integer.

Next, I examined the genre column to isolate action movies from the same period. From there, I counted how many titles met the criteria for a short movie — defined as running under 90 minutes.

<h3>Results</h3>

Most frequent movie duration: Around ___ minutes (saved as duration)
(You can fill this with your actual computed value.)

Number of short action movies in the 1990s: ___ (saved as short_movie_count)

<h3>Key Skills Demonstrated</h3>

<ul>
  <li>Exploratory data analysis (EDA)</li>
  <li>Data cleaning and filtering</li>
  <li>Working with categorical and numerical features</li>
  <li>Deriving insights from real-world entertainment data</li>
  <li>Applying logical conditions to define custom metrics</li>
</ul>

<h3>Reflection</h3>

This project was a great exercise in examining real-world media trends using data. Beyond simple filtering, it highlighted how much variation exists in movie runtimes across genres and eras. It also reinforced the importance of clearly defining criteria (like “short movie”) and validating assumptions with data before drawing conclusions.

<a href="Data-Portfolio/projects/Netflix/notebook.ipynb">You can find the link to the book for the codes here</a>
