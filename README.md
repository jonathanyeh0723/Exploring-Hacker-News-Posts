# Exploring Hacker News Posts
To analyse post types on [Hacker News](https://news.ycombinator.com/) and determine if there is a type of post which is more popular and attracts more comments.

## Introduction
![hacker_news_title](./resources/hacker_news.jpg)

Hacker News is a site started by the startup incubator [Y Combinator](https://www.ycombinator.com/), where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

## The Data

20101 x 7 (rows x columns). Below are descriptions of the columns:

 - `id`: The unique identifier from Hacker News for the post
 - `title`: The title of the post
 - `url`: The URL that the posts links to, if the post has a URL
 - `num_points`: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
 - `num_comments`: The number of comments that were made on the post
 - `author`: The username of the person who submitted the post
 - `created_at`: The date and time at which the post was submitted

## Target

## Workflow

## Conclusion
This project's purpose was to analyse post types on Hacker News and determine if there is a type of post which is more popular and attracts more comments.

Considering the fact we used only posts with comments, the results showed that on average, ask posts tend to get 4 more comments than show posts. Also, the results concluded that 3pm EST time is the hour when users are more likely to leave comments.
