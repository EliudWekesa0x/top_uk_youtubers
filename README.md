# Data Portfolio: Excel to Power BI

<p align="center">
  <img src="https://github.com/EliudWekesa0x/top_uk_youtubers/blob/main/assets/images/kaggle_to_powerbi.gif"
alt= "Kaggle to Power BI Demo">
<p>

# Table of Contents
  - [Objective](#objective)
  - [Data Source](#data-source)
  - [Stages](#stages)
  - [Design](#design)
    - [Mockup](#mockup)
    - [Tools](#tools)
  - [Development](#development)
    - [Pseudocode](#pseudocode)
    - [Data Exploration](#data-exploration)
    - [Data Cleaning](#data-cleaning)
    - [Transform the Data](#tranform-the-data)
    - [Create the SQL View](#create-the-sql-view)
  - [Testing](#testing)
    - [Data Quality Tests](#data-quality-tests)
  - [Visualization](#visualization)
    - [Results](#results)
    - [DAX Measures](#results)
  - [Analysis](#analysis)
    - [Findings](#findings)
    - [Validation](#validation)
    - [Discovery](#discovery)
  - [Recommendations](#recommendations)
    - [Potential ROI](#potential-roi)
    - [Potential Courses of Action](#potential-courses-of-action)
  - [Conclusion](#conclusion)

# Objective
  - What is the key pain point?

The Head of Marketing wants to find out who the top YouTubers are in 2024 to decide on which YouTubers would be best to run marketing campaigns throughout the rest of the year.

  - What is the ideal solution?

To create a dashboard that provides insights into the top UK YouTubers in 2024 that includes their

  - Subscriber count
  - Total views
  - Total videos, and
  - Engagement metrics

This will help the marketing team make informed decisions about which YouTubers to collaborate with for their marketing campaigns.

# User Story
As the Head of Marketing, I want to use a dashboard that analyses YouTube channel data in the UK .

This dashboard should allow me to identify the top performing channels based on metrics like subscriber base and average views.

With this information, I can make more informed decisions about which Youtubers are right to collaborate with, and therefore maximize how effective each marketing campaign is.

# Data Source
  - What is needed to achieve our objective

We need data on the top UK YouTubers in 2024 that includes their

  - Channel names
  - Total subscribers
  - Total views
  - Total videos uploaded
  - Where is the data coming from? The data is sourced from Kaggle (an Excel extract), [see here to find it](https://www.kaggle.com/datasets/bhavyadhingra00020/top-100-social-media-influencers-2024-countrywise?resource=download)

# Stages
  - Design
  - Development
  - Testing
  - Analysis

# Design

## Dashboard components required

  - What should the dashboard contain based on the requirements provided?

To understand what it should contain, we need to figure out what questions we need the dashboard to answer:

  1. Who are the top 10 YouTubers with the most subscribers?
  2. Which 3 channels have uploaded the most videos?
  3. Which 3 channels have the most views?
  4. Which 3 channels have the highest average views per video?
  5. Which 3 channels have the highest views per subscriber ratio?
  6. Which 3 channels have the highest subscriber engagement rate per video uploaded?

For now, these are some of the questions we need to answer, this may change as we progress down our analysis.

## Dashboard mockup

  - What should it look like?

Some of the data visuals that may be appropriate in answering our questions include:

  1. Table
  2. Treemap / Scatter chart / Bubble chart
  3. Scorecards
  4. Horizontal bar chart

<p align="center">
  <img src="https://github.com/EliudWekesa0x/top_uk_youtubers/blob/main/assets/images/dashboard_mockup.png"
alt= "Kaggle to Power BI Demo">
<p>

## Tools



