---
layout: project
type: project
image: images/manoa-bazaar.png
title: Manoa Bazaar
permalink: projects/finalproject
# All dates must be YYYY-MM-DD format!
date: 2020-12-18
labels:
  - Javascript
  - Github
  - Final Project
  - Meteor React 
  - Semantic UI
summary: Building a functional web application for the final project of ICS 314. The web application was called Manoa Bazaar, which is a website designed for UHM students and faculty to sell and buy products offered by other UHM members.
---

For the final project of my software engineering class, ICS 314, we had to create a web application. Me and my group were assigned the problem that there are lots of students moving in and out of the dorms, for example, and they have no easy accessible way to buy and sell products that might be useful for the dorms. This is applicable to other aspects of university life as well. For example, to sell textbooks that you don't need anymore, or school supplies. We have created a web application called Manoa Bazaar that is designed for UHM community members to buy and sell products. The benefits of this are that all products sold will be close by, and thus there are no long waiting times or high shipping costs. It also is conventional that the products will be explicitly from UHM members, so they will be useful for the life at UH. 

## Manoa Bazaar 
The code for Manoa Bazaar can be found at our github repository called [Manoa Bazaar](https://github.com/manoa-bazaar/manoa-bazaar). Information on how to use the website, download our code, or just some general information about our project can be found [here](https://github.com/manoa-bazaar/manoa-bazaar.github.io). We divided this project up into three milestones where each milestone had a deadline. These milestones can be found [here](https://github.com/manoa-bazaar/manoa-bazaar/projects). Each of these milestones has tasks assigned to them that we had to finish before the due date of that milestone. Each task was assigned to one team member. 

## My contribution to the project 
I was responsible for the code for the categories page and then each respective category. There were five categories that we divided the items up in. The categories page displayed each of those categories. Each category, when selected, will take the user to the respective category. In that category then only the items that belong to that category will be displayed. The categories page looked like this:
<img class="ui image" src="{{ site.baseurl }}/images/categories.png">

To get each category to just display the items that belong in that category, I had to work with filtering items out of the collection that we subscribed to. That was really fun to learn and figure out. The page for each respective category displays just the items for that category:
<img class="ui image" src="{{ site.baseurl }}/images/kitchenitems.png">

When the user then presses the view item button, the user will be taken to a page where there is more information about the offered item available.
<img class="ui image" src="{{ site.baseurl }}/images/viewitem.png">

To get the view item page to work, I had to work with docIDs. In tbe beginning, I was pretty confused by this. After doing some research and watching some videos on this, it all made sense and it is really good to use to display information about just that one item. 
I also helped my teammates with any other issues that they might have with their parts of the code. 

## What I have learned 
I have learned how to work in a group environment, create a web application, and work together with multiple people in one repository in github. I have become way more familiar with javascript after this project, because our whole project was written using javascript. We have also used some underscore / functional programming that definitely helped make the code more readable and compact. I have learned how to write code using different design patterns, such as the pub-sub design pattern, which turned out to be very useful for our project. 
This project allowed me to put everything that I have learned about in ICS 314 into practice. It was a really good way to combine everything that I have learned in that class into building a functional web application. 
In the end, I think our project turned out pretty good, but there is definitely some room for improvement. It was hard to effectively communicate with teammembers, that I did not know before the project, because everything was entirely online. This taught me to have more patience as well. 
