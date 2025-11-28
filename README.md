
# Instagram Engagement Capstone Project  
---
DSCI 101 – Data Management
Author: Nina Dort
Instructor: Darien DeWolf  
Due Date: December 5, 2025  

---

#Project Overview

This project analyzes engagement patterns on my personal Instagram account.  
The goal is to understand which types of posts receive the most likes and comments.

The project uses R, tidyverse, and Quarto Markdown to:

- Clean and prepare the dataset  
- Create new variables  
- Analyze engagement across categories  
- Compare emoji vs no-emoji posts  
- Compare carousel vs single-photo posts  
- Explore posting month (advanced element)  
- Produce visualizations and interpretations  

---

# Research Questions

1. Do certain categories of posts (travel, life-events, concerts, etc.) get more likes? 
2. Do posts with emojis receive more engagement?
3. Do carousel posts (multiple photos) get more likes than single-photo posts?
4. Does posting month influence engagement?

---

# Data Set Overview

The dataset was manually collected from my personal Instagram account.  
It includes:

- date  (date posted) 
- likes  (number of likes)
- comments(number of comments)  
- caption text (caption used on post)
- emojis  (number of emojis in caption)
- number of photos (number of photos in each post)
- category (type of post) 
- has face  (whether a face was visible)
- hashtag (if a hashtag was used) 

  The data set contains 26 Instagram posts collected between June 2022
  and August 2025, with 10 recorded variables.
  
  This data set is stored in: data/raw/Instagram_dataset.xlsx
---
# Limitations
-Data is from a single personal account and not generalizable
-Small sample size
-Engagement does not account for reach or algorithm changes
-Posting time of day not included
---

#Ethics Note 
Only publicly visible information from my own account was used.  
No private or third-party data was collected.

---

# How to Run This Project

To reproduce this analysis:

1. Clone this GitHub repository  
2. Open the project in RStudio  
3. Install required packages: 
   install.packages(c("tidyverse", "readxl", "janitor", "lubridate", "quarto"))
4. Open capstone.qmd
5. Click Render to generate the HTML or PDF report

---
