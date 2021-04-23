## Thanks for stopping by!

I'm a career electronics technician making a transition to a career in software engineering.  Over the course of earning my Bachelor’s in Computer Science, I’ve been surprised by how much the soft skills of these two professions overlap.  Logical problem solving, mathematical aptitude, organized and methodical thought, and attention to detail are key ingredients in both these fields.  Whether building them up, or tearing them down to better understand them or fix them, I’ve learned that circuits and software require a similar type of thinking to mentally digest.

These professions are also similar in that a good team is always more than the sum of its parts.  Very much like my career  in electronics, having talented peers to bounce ideas off of, and enthusiastic mentors to offer guidance has made earning my degree as much a joy as it was a challenge.

This page is a digital portfolio of some of the work I've completed during the Computer Science (concentration Software Engineering) program at Southern New Hampshire University.  It showcases some of what I’ve learned in topics as broad as data structures and databases, and as narrow as Python web-app frameworks and secure coding in C++.  It’s by no means a comprehensive list of everything I can do, but I hope it highlights my approach to problem-solving (which is not to beat a problem with code until something works).  I plan to add to it as I complete more projects, and even further enhance what’s already here.  
I’ve left some contact info at the bottom of the page, so feel free to reach out, and thanks for stopping by!

### Code Review

My code review of the three projects you see below.  Here I walk through the features of the existing code as it was originally submitted, perform an analysis of this code, and detail the planned improvements (the results of which will be showcased here).

<div class="container">
<iframe src="https://drive.google.com/file/d/1MysUefThHCuq-Ze-aeqMAi1ix4_HHIxW/preview" frameborder="0" allowfullscreen class="video"></iframe>
</div>  
<p></p>

***

### Software Design and Engineering

In CS-410: **Software Reverse Engineering**, I reverse-engineered a legacy program from binary to assembly to C++, and corrected security flaws in the source code of the reversed program.  Many of these vulnerabilities were due to the programmer of the legacy code not observing proper considerations of C programming, but the original as well as the reversed and revised programs also lack portability.  Both could be enhanced by porting the reversed application to Java, which imposes stricter compile limitations and is also write-once-run-anywhere.  This work is the result of that translation from C++ to Java, which has been further modified to produce more modular code.  

This artifact originally showcased my ability to reverse-engineer software from binary, but in this revised form, highlights my understanding of object-oriented programming, and how different languages can overlap in programming paradigms.  This revision takes the original program and makes it more modular, secure, reliable, and portable.

The program currently uses a HashMap to store the client objects as key-value pairs.  I’m well aware that this might not represent a real-world use-case, and a realistic scenario would utilize a database, but it makes a fine structure for expanding and testing the application.  

Planned further enhancements include JUnit testing.  Source for this project is available at [github.com/JimmyBoomBots3000/Banking](https://github.com/JimmyBoomBots3000/Banking).

[![Image](/images/art1.jpg)](https://raw.githubusercontent.com/JimmyBoomBots3000/JimmyBoomBots3000.github.io/main/images/art1.jpg "C++ to Java")  

***

### Algorithms and Data Structure

In CS-260: **Data Structures and Algorithms**, I developed four C++ programs, one each demonstrating a **Vector**, **Linked List**, **Hash Table**, and **Binary Search Tree**.  Each program reads data into its respective structure from a csv file, and allows a user to display all items, search the structure and display a single item, as well as manipulate the structure by adding or removing an item.  Over time, these programs have been updated for bug fixes and security, and feature adds such as timing operations to compare performance of different operations.

I admit, this set of programs may seem pedestrian, but I wanted something to show that I understand data structures and can develop algorithms to suit them, and this demo gets straight to the point.

Source code for this project is at [github.com/JimmyBoomBots3000/DataStructuresAndAlgorithms](https://github.com/JimmyBoomBots3000/DataStructuresAndAlgorithms).

[![Image](/images/structures.jpg)](https://raw.githubusercontent.com/JimmyBoomBots3000/JimmyBoomBots3000.github.io/main/images/structures.jpg "Data Structures")  

***

### Databases

In CS-340: **Client-Server Development**, I was given a specification as well as the following  scenario: 

> Grazioso Salvare identifies dogs that are good candidates for search-and-rescue training. When trained, these dogs are able to find and help to rescue humans or other animals, often in life-threatening conditions. To help identify dogs for training, Grazioso Salvare has reached an agreement with a nonprofit agency that operates five animal shelters in the region around Austin, Texas. This non-profit agency will provide Grazioso Salvare with data from their shelters...  
> 
> ...Grazioso Salvare is seeking a software application that can work with existing data from the animal shelters to identify and categorize available dogs. Global Rain has contracted for a full stack development of this application that will include a database and a client-facing web application dashboard. Grazioso Salvare will use this dashboard to interact with and visualize data from a MongoDB database. The dashboard must be a user-friendly, intuitive interface that will reduce user errors and training time.

What I produced was a web app, written front-to-back in Python.  To take this demo out of the classroom (where it ran entirely on localhost resources), I have it hosted on Heroku, and established my own MongoDB cluster to house the same data that was used in the original project.  The interface has also been cleaned up a bit, and is now utilizing the Bootstrap front-end framework.  Take it for a spin at [graziososalvare.herokuapp.com](https://graziososalvare.herokuapp.com/).

Source code is at [github.com/JimmyBoomBots3000/GraziosoSalvare](https://github.com/JimmyBoomBots3000/GraziosoSalvare).

[![Image](/images/new_3[1].PNG)](https://graziososalvare.herokuapp.com/ "Grazioso Salvare web app")  

***

### Contact

[JamesBRichmond@protonmail.com](mailto:JamesBRichmond@protonmail.com)
