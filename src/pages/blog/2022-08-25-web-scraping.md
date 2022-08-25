---
templateKey: blog-post
title: Web Scraping
date: 2022-08-25T23:42:27.134Z
description: "#web"
featuredpost: false
featuredimage: /img/webscrap.jpg
---
## What is web scraping?

**Web scraping is the process of using bots to extract content and data from a website.**
Unlike screen scraping, which only copies pixels displayed onscreen, web scraping extracts underlying HTML code and, with it, data stored in a database. The scraper can then replicate entire website content elsewhere.

Web scraping is used in a variety of digital businesses that rely on data harvesting. Legitimate use cases include:

* Search engine bots crawling a site, analyzing its content and then ranking it.
* Price comparison sites deploying bots to auto-fetch prices and product descriptions for allied seller websites.
* Market research companies using scrapers to pull data from forums and social media (e.g., for sentiment analysis).

![](/img/webscrap.jpg)

### Cheerio

Cheerio is the most amazing package I never heard of until now. Essentially, Cheerio gives you jQuery-like queries on the DOM structure of the HTML you load! Its amazing and allows you to do things like this:

```
  const cheerio = require('cheerio')
  const $ = cheerio.load('<h2 class="title">Hello world</h2>')
  const titleText = $('h2.title').text();
```



So we can scrape the data on the sites. Here are some resource suggestions to know more about this topic;

* <https://axios-http.com/docs/intro>
* <https://cheerio.js.org/>
* <https://www.freecodecamp.org/news/how-to-scrape-websites-with-node-js-and-cheerio/>
* <https://dev.to/drsimplegraffiti/i-scraped-dev-to-using-axios-and-cheerio-26ko>

## References

1. xxx, AAA, 2020, http://www.galaksiya.com 
2. xxx, AAA, 2021, http://www.galaksiya.com