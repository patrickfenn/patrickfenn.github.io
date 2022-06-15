---
layout: post
title: Google Search Clone - A search engine that utilizes Lucene and our own Web Crawler!
subtitle: A search engine made by my team in our Info Retreival class.
cover-img: /asssets/img/path.jpg
thumbnail-img: /assets/img/google.jpeg
share-img: /assets/img/path.jpg
tags: [java,lucene,web,search,engine,spring,boot,python,beautiful,soup]
---

My team and I made a search engine for the most popular MMA sport websites. To accomplish this, we first needed to create a web crawler that crawled each web page and save the associated text. For this we used python's Beautiful Soup to scrape the data. Once we scraped a sufficient amount, we used Lucene to index the data to perform searches. I was responsible for implementing the backend in Spring Boot. While my partners implemented the front end and the snippets for showing within the search results. In order to facilitate a Restful API, we assigned each query a unique ID and embedded it into the resulting JSON. 

[Github](https://github.com/patrickfenn/CS172-Group-Project)

[Demo](http://mma-search.herokuapp.com/)
