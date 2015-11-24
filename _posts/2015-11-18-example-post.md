---
layout:             post
title:              "Introducing CareerQB"
author:             "Mike Daley"
categories:         careerqb
image:              "/images/posts/careerqb/2015-11-18/example-post/job_search_new_icon_01.jpg"
landscape:          "/images/posts/careerqb/2015-11-18/example-post/job_search_new_570px.jpg"
excerpt_separator:   <!--more-->
---

Searching for new job is a lot of work. It involves finding job openings, applying for jobs, preparing for interviews, and negotiating an offer. There are a lot of great tools for searching for positions and there is a lot of great online career advice, but the sites are not focused on helping people with all of the hard work of organizing their job searches. CareerQB is a new job search site with the goal of providing the tools people need to land their dream job.

<!--more-->

<!--
  -- ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
  -- TODO: 11/24/2015
  -- THIS BUILDS THE IMAGE PATH DYNAMICALLY, BUT IT ENDS UP BEING WAY TOO
  -- LONG, SO I'M HARD-CODING THE IMAGE NAMES FOR NOW UNTIL I FIGURE OUT
  -- THE LIQUID TEMPLATES A LITTLE BETTER
  --
  -- <img class="img-responsive img-thumbnail" 
  --      src="{{ site.root_url | append: "images/posts" | append: page.id | append: page.landscape }}">
  -- ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
-->

<img class="img-responsive img-thumbnail" src="{{ page.landscape }}"/>

Search for millions of Healthcare, Legal, Finance, Marketing, Human Resources, Engineering, and Technology jobs posted on [Indeed.com](http://indeed.com) and [CareerBuilder.com](http://careerbuilder.com) from a single site, CareerQB. CareerQB aggregates multiple job search sites into a single site and we will be adding new job search sites over the coming months.

Page url  = {{ page.url  }}

Page id   = {{ page.id   }}

Page path = {{ page.path }}

Page date = {{ page.date | date: "%Y-%m-%d" | append: "/test" }}

Site root url = {{ site.root_url }}

Never lose a job posting by saving postings from multiple job search sites in a single location. I cannot count how many times that I saw a job posting that looked interesting and I forgot to bookmark it. When I went to search for it a few days later - I was unable to find it because I could not remember which job site that I found the position.

