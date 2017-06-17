---
layout: post
section-type: post
title: Python script to download submitted HackerRank solutions
category: Technical
tags: [ 'Python','Python Requests Module','BeautifulSoup', 'Scripting' ]
---

The other day when I was reading Steve Yegge's post on the five most essential questions that phone screen interviewers should include in their interviews (you can read the post at [1]), I found that scripting was one of the areas. That somehow stayed with me. So when I was trying to download the solutions that I had submitted while practising on HackerRank, I thought that ws the best opportunity for me to brush up my scripting and Python skills (*Two birds with the same shot and all...*). The following are the Python modules I used in the script: 

* Requests module </li>
* BeautifulSoup </li>
* User Agent </li>

Used requests and BeautifulSoup modules from Python to get the url and navigate through the tags to get challenge names before finally being able to construct the URL for each challenge and navigating to the solution to download it.

### Completed: 

<div class="align-left">
<ol>
<li> Getting a URL using *requests* module of Python,</li>
<li> Logging in using requests.get(),</li>
<li> Iterate over the content of the response captured, in chunks,</li>
<li> Using a file descriptor, write it to a file on the disk,</li>
<li> Use *BeautifulSoup()* to do *html.pars*ing over the file,</li>
<li> Using the returned bs object, find tags that satisfy the necessary condition (for example, a tag that contains a particular text),</li>
<li> Get values of specific attributes from the captured tag.</li>
<li> Construct a URL using the page you want to navigate to. </li>
<li> Open the *.html* page and iterative carry </li>
<li> Look for a tag with the username.</li>
<li> Use the User Agent module to emulate the behaviour of a browser.</li>
<li> Download submission with the submitted code.</li>
</ol>
</div>

### References: 

[1]: https://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions
