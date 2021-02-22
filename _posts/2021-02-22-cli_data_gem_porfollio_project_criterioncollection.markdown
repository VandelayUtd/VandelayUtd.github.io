---
layout: post
title:      "CLI data gem Porfollio Project, CriterionCollection"
date:       2021-02-22 20:32:12 +0000
permalink:  cli_data_gem_porfollio_project_criterioncollection
---


This project was a real riot! First time program built from scratch, first gem I've made, and building the program helped build confidence in the skills I've learned thus far. I decided to build a CLI that interacts with two different libraries stored on www.criterion.com. The libraries, one belonging to me and the other to my roommate, log movies that he and I have in our personal collections. I wanted to use a URL that I could actually edit in someway myself and play with the dynamism there. The biggest snag I ran into in the project was that the website I was using wasn't the most accomodating with the flow I wanted in  some of my scraper methods. I was using a list of movies that had corresponding directors and movie url's, but in order to get to the corresponding director i had to program the scaper to move from the list page to the movie  page and then to the director page. This worked and was functional and fun even to play with Nokogiri, but the load time to puts out the initial list of directors took forever so instead applied some regex to hardcode director's links, which  proved to be significantly faster, but won't account for future changes in the structure of the website. All in all, my project works the way I want it to and was a wonderful excersize in object orientation.
