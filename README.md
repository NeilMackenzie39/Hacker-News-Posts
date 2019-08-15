# Hacker-News-Posts
Assess popularity of "Ask" and "Show" posts on Hacker News web page

## Getting Started
This repository contains the jupyter notebook and 'HN_posts_year_to_Sep_26_2016.csv' file required to run the notebook.

## Notebook versions
Two version of the jupyter notebook exist for this project exist in this repository. A description of each is given below:
1. 'Hacker News Project.ipnub' contains the initial work I did on this project during my first attempt. 
2. 'Hacker News Project_Updated.ipnub' is an updated version of the notebook containing modifications made after I had learnt about pandas dataframes and plotting using matplotlib.

## Dataset contents
A table describing the columns of the dataset is shown below

Column|Description
---|---
id|The unique identifier from Hacker News for the post
title|The title of the post
url|The URL that the posts links to, if it the post has a URL
num_points|The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
num_comments|The number of comments that were made on the post
author|The username of the person who submitted the post
created_at|The date and time at which the post was submitted


