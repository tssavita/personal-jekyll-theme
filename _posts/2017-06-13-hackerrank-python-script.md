---
layout: post
section-type: post
title: Python script to download submitted HackerRank solutions
category: Technical
tags: [ 'Python','Python Requests Module','BeautifulSoup', 'Scripting' ]
---

The other day when I was reading Steve Yegge's post on the five most essential questions that phone screen interviewers should include in their interviews (you can read the post at [1]), I found that scripting was one of the areas. That somehow stayed with me. So when I was trying to download the solutions that I had submitted while practising on HackerRank, I thought that ws the best opportunity for me to brush up my scripting and Python skills (*Two birds with the same shot and all...*). The following are the Python modules I used in the script: 

<div style="text-align: left">
+ Requests module
+ BeautifulSoup
+ User Agent 
</div>

Used requests and BeautifulSoup modules from Python to get the url and navigate through the tags to get challenge names before finally being able to construct the URL for each challenge and navigating to the solution to download it.

### Completed: 

<div style="text-align:left">
1. Getting a URL using *requests* module of Python,
2. Logging in using requests.get(),
3. Iterate over the content of the response captured, in chunks,
4. Using a file descriptor, write it to a file on the disk,
5. Use *BeautifulSoup()* to do *html.pars*ing over the file,
6. Using the returned bs object, find tags that satisfy the necessary condition (for example, a tag that contains a particular text),
7. Get values of specific attributes from the captured tag.
8. Construct a URL using the page you want to navigate to. 
9. Open the *.html* page and iterative carry 
10. Look for a tag with the username.
11. Use the User Agent module to emulate the behaviour of a browser. 
12. Download submission with the submitted code.
</div>

### References: 

[1]: https://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions
