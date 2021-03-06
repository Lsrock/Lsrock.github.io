---
layout: project
type: project
image: images/shaw1.PNG
title: SHA-1
permalink: projects/SHA1
# All dates must be YYYY-MM-DD format!
date: 2019-04-13
labels:
  - SHA-1
  - C
summary: A hashing algorithm I worked on for ICS 212.
---

<img class="ui image" align="left" src="{{ site.baseurl }}/images/shaone.jpg" height="450" width="450" >

One of my final projects in my Program Structure class, which taught students C and C++, was to write a version of SHA-1 to display messages from files given to me. SHA-1 is a cryptographic hash function that takes a file and produces a message digest, which is displayed in hexadecimal. It essentially inputs a string of characters and separates it into 32-bit unsigned characters. Then they are followed by EOF characters and placed into arrays with a size of 16. These arrays are padded with zeros to fill the indices that do not get filled, and the last array is saved for the input length. The size of the input is important because the number of arrays used is taken from it. The elements in each of those arrays are then hashed after being put into another array of size 80. This is done by using helper functions that work with the location of the item being looked at. The program then returns a five words message digest. 

I searched out help to complete this project due to its complexity and managed to complete it with classmates. Every student was responsible for turning in their version of the project however. I had the choice of using either C or C++ to complete this project and ended up using C. It was an interesting and brief look into the world of cybersecurity, and helped me understand encryption better. 
