# Nima Dehghani - Portfolio
Hi, I’m Nima Dehghani — a data-driven problem solver with a background in Agile leadership, digital learning development, and renewable-energy-focused engineering projects. I’ve led cross-functional teams, built national-scale digital platforms, and delivered solutions used by more than 30,000 learners across Australia.
My work sits at the intersection of technology, education, engineering and analytics. At Weld Australia, I progressed from Graduate Learning Developer to Digital Education Manager, where I designed and delivered a nationally consistent digital learning ecosystem. I created data-supported workflows, developed scalable content strategies, and introduced multimedia storytelling to improve engagement and outcomes. I developed the digital education learning resources section of Weld Australia from scratch and was able to deliver high quality products with the help of my team. 
Earlier roles strengthened my technical versatility: from building SEO-driven digital growth as a Marketing & Sales Manager, to developing a solar-powered battery payment system during an engineering project in Cambodia. Across each project, I’ve focused on turning complexity into clear, actionable solutions.

Now based in Berlin, I’m expanding my work into energy, renewables, and analytics. This portfolio showcases the projects I’m developing to grow my technical skill set — including data analysis, visualization, automation, and tools that support clean-energy innovation.

Thanks for stopping by — I’m always open to collaborating, learning, and contributing to impactful projects.



<h1>1990s Netflix Movie Analysis — Exploratory Data Analysis Project</h1>

For this project, I explored a dataset of Netflix titles to better understand movie trends from the 1990s. The goal was to analyze movie durations, identify common patterns, and investigate how many short action movies were produced during the decade. This analysis simulates the type of research a production company might do when developing nostalgic or era-inspired content.

<h3>Objective</h3>
<ul>
  <li>Focus on movies released between 1990 and 1999</li>
  <li>Determine the most common movie duration during that decade</li>
  <li>Count the number of short action movies (defined as < 90 minutes)</li>
</ul>



Approach

I began by filtering the dataset (netflix_data.csv) to include only movies (not TV shows) released in the 1990s. After isolating the decade, I analyzed the distribution of movie durations using basic exploratory data analysis techniques.

To identify the typical runtime, I looked at the frequency of each duration value. Movie runtimes tend to cluster, so instead of a single exact mode, I used an approximate most frequent duration, saved as an integer.

Next, I examined the genre column to isolate action movies from the same period. From there, I counted how many titles met the criteria for a short movie — defined as running under 90 minutes.

Results

Most frequent movie duration: Around ___ minutes (saved as duration)
(You can fill this with your actual computed value.)

Number of short action movies in the 1990s: ___ (saved as short_movie_count)

Key Skills Demonstrated

Exploratory data analysis (EDA)

Data cleaning and filtering

Working with categorical and numerical features

Deriving insights from real-world entertainment data

Applying logical conditions to define custom metrics

Reflection

This project was a great exercise in examining real-world media trends using data. Beyond simple filtering, it highlighted how much variation exists in movie runtimes across genres and eras. It also reinforced the importance of clearly defining criteria (like “short movie”) and validating assumptions with data before drawing conclusions.
