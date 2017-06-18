---
layout: post
section-type: post
title: The Dutch National Flag problem
category: Technical, Data Structures & Algorithms
tags: [ '', 'dutch national flag problem', 'quick sort', 'grouping', 'dijkstra' ]
---

The Dutch National Flag Problem is a solution invented by the Dutch computer scientist Edsger W. Dijkstra. Consider the tricolored Dutch National Flag - . 

**Problem:** Given balls of the three colors on the flag, what is the best method of grouping them in a way so as to form the Dutch flag? 

**Solution:** Consider the balls as elements of an array. Maintain three pointers - low, mid and high. The first color of balls should be located between indices 0 to low of the array. The second color of balls should be located between indices low+1 to mid. And you guessed right, the third color of balls, should be placed between indices mid+1 to high. 

Consider the following representation: 

[[https://raw.githubusercontent.com/tssavita/tssavita.github.io/master/img/\_posts/two\_elements.png]]

**For only two groups of elements** (you can look at the picture representation above), steps included in the algorithm are as follows. 
  
* We start with low = 1 and high = n, where n is the number of elements in the array.
* We consider that:
  * 0 to low are already elements of the first type, and, 
  * h to n-1 are already elements of the second type.
  * elements from low to high are those whose type is unknown. They have not been grouped yet. 
* While low <= high: 
  * if arr[low] == <first type> 
        increment low.
  * if arr[low] == <second type> 
        swap(arr[low], arr[high]),
        decrement high.

**For three groups of elements** (you can look at the picture representation ![above](/img/_posts/three_elements.png)). The steps would be similar, except:

* We have an extra pointer - mid to keep track of the ending position of the second element in the array,
* The ungrouped elements are now present from mid to high,
* There are three possibilities for the ungrouped element:
  * if arr[mid] == <first type>
        swap (arr[low], arr[mid]),
        increment low, 
        increment mid.
  * if arr[mid] == <second type>
        increment mid
  * if arr[mid] == <third type>
        swap (arr[mid], arr[high])
        decrement high

Note that the mid index just got the ungrouped element that was present at arr[high] earlier, which means that it still needs to be grouped. So there is no need to increment mid. 

Some applications/variations of this problem are:

* Shifting 0s to the end of the array.
* Shifting even numbers to then end of the array. 
* Given an array containing elements - 0, 1, and 2, rearrange the elements in such a way that all same elements occur together. 
