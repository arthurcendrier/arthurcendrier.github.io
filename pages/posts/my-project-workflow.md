---
permalink: /my-project-workflow
title: My Project Workflow
description: A quick description of the workflow I use with each project to improve organization and transparency.
---

{% assign asset_path = site.data.path["posts"] %}

{% assign moodboard_img = asset_path | append: "moodboard-example-min.jpg" | relative_url %}

{% assign wireframe_img = asset_path | append: "wireframe-vs-final-design-min.jpg" | relative_url %}

A structured workflow is a good way to ensure transparency and a stable organization. This is why I go through the following steps for each project :

1. [Project Brief](#project-brief)
2. [Moodboard](#moodboard)
3. [Wireframing](#wireframing)
4. [Design](#design)
5. [Webflow Development](#webflow-development)
6. [Launch](#launch)

<a name="project-brief"/>

## Project Brief

The first step is having a video conference call to get to know each other and establish a shared vision of the project and its goals. I synthesize the information gathered during this meeting in a short document called the project brief. I'll send it to you after the call, this way you can confirm that we have a good common understanding.

<a name="moodboard"/>

## Mood Board

Based on the project brief I will make a mood board (i.e. an aggregation of inspirations) and get your feedback on it thanks to Figma's collaboration tools (more info available [on their website](https://help.figma.com/hc/en-us/articles/360039825314-Getting-started-with-comments)). This way I can get a feeling for your tastes without the need for countless revisions and we both save time!

<figure>
  <img src="{{ moodboard_img }}" alt="Mood Board Example">
  <figcaption>Mood Board Example</figcaption>
</figure>


<a name="wireframing"/>

## Wireframing

Based on the previous steps I come up with a wireframe proposal of the design. This is a very simplified version without any details, the goal is to have a common understanding of what the content of the website will be and how it will be presented. Once you confirm everything is fine, we go to the next step.

<figure>
  <img src="{{ wireframe_img }}" alt="Wireframe vs Final Design">
  <figcaption>Wireframe vs Final Design</figcaption>
</figure>

<a name="design"/>

## Design

This time I design the website as it will look like for the end-users. I'll share the result on Figsma where you can ask for revisions before I start the development.


<a name="webflow-development"/>

## Webflow Development

The design having been confirmed, it's time to turn it into a real responsive website thanks to Webflow. You'll be able to check that everything works well by visiting the live website on a temporary URL.

<a name="launch"/>

## Launch

The only thing left to do at this point is to buy a domain name (if you haven't already), sign up for Webflow's hosting plan and we're good to go. That's also when I'll transfer the project to you and train you to be able to add and modify content without my help. This way you'll have full ownership of your website! (Of course, you can always hire me for extra work on it in the future if you want to!)