# SNHU-CS-300
Repository of projects created for SNHU class CS-300

<b>What was the problem you were solving in the projects for this course?</b>

We needed to create a program that could load a course list into a data structure from a text file, organize the items alphanumerically, and print either individual courses or the entire sourted list. 

<b>How did you approach the problem? Consider why data structures are important to understand.</b>

In project one we created psuedocode that would help analize the different data structures, the pros and cons to each data structure, and which structure performs appropriately and quickly for our coding needs. In project two I chose to load a file into a binary search tree and passed the appropriate data through a temporary vector in order to hold each line of the text file. The items of line were added to the vector and assigned a course variable to be loaded into the binary tree. My inOrder function traversed the tree down to the left side and printed up to the root and down to the right side. This created the alphanumeric order. This also allowed me to search a course by course number by searching the tree recursively until the matching course was found. Using the binary tree allowed me to perform this in an intuitive and efficient manner.  

<b>How did you overcome any roadblocks you encountered while going through the activities or project?</b>

I found most of my roadblocks came from getting Visual Studio to fully run on my desktop and had to utilize Stack Overflow and Google quite a bit in order to get things running smoothly. I found working on my laptop, which runs on Linux, was a much easier experience, though it's a very small laptop which makes it a bit uncomfortable to work on. With coding, I found some difficulty loading the data into the data structures, however, utilizing Stack Overflow and reviewing the previous modules code bases I was able to figure it out.

<b>How has your work on this project expanded your approach to designing software and developing programs?</b>

I have had previous experiences with C++ coding, however, this was my first experience working with Visual Studio and my first time implementing data structures with data coming from an external file instead of just implementing it into the code itself. 

<b>How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?</b>

Each step towards my degree has expanded my knowledge and experience towards writing working, clean code that is better adept at handling real-world structures. 
