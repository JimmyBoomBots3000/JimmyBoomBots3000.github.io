## Thanks for stopping by!

I'm a career electronics technician making a transition to a career in software engineering.  I'm currently wrapping up a BS in Computer Science, concentration in Software Engineering.  This page is a digital portfolio of some of the coursework I've completed during the program and am improving for my program capstone.  
Please pardon my dust as I build up this work-in-progress!

### Code Review

My code review of the three projects you see below.  Here I walk through the features of the existing code as it was originally submitted, perform an analysis of this code, and detail the planned improvements (the results of which will be showcasaed here).

<div class="container">
<iframe src="https://drive.google.com/file/d/1MysUefThHCuq-Ze-aeqMAi1ix4_HHIxW/preview" frameborder="0" allowfullscreen class="video"></iframe>
</div>  
<br>
### Software Design and Engineering

In CS410: **Software Reverse Engineering**, I reverse-engineered a legacy program from binary to assembly to C++, and corrected security flaws in the source code of the reversed program.  Many of these vulnerabilities were due to the programmer of the legacy code not observing proper considerations of C programming, but the original as well as the reversed and revised programs also lack portability.  Both could be enhanced by porting the reversed application to Java, which imposes stricter compile limitations and is also write-once-run-anywhere.  This work is the result of that translation from C++ to Java, which has been further modified to produce more modular code.  

This artifact originally showcased my ability to reverse-engineer software from binary, but in this revised form, highlights my understanding of object oriented programming, and how different languages can overlap in programming paradigms.  This revision takes the original program and makes it more modular, secure, reliable, and portable.

Determining an effective way to structure the client objects (clients as in people) took a few iterations, and I eventually decided on using a HashMap to store the client objects as key-value pairs.  I’m well aware that this might not represent a real-world use-case, and this structure might be rendered unnecessary with further enhancements such as utilizing a database, but it makes a fine structure for expanding and testing the application.  

Planned further enhancements include JUnit testing.  Source for this project is available [here](https://github.com/JimmyBoomBots3000/Banking).

[![Image](/images/art1.jpg)](https://raw.githubusercontent.com/JimmyBoomBots3000/JimmyBoomBots3000.github.io/main/images/art1.jpg)  

### Algorithms and Data Structure

In CS260: **Data Structures and Algorithms**, I developed four C++ programs, one each demonstrating a **Vector** **Linked List** **Hash Table** and **Binary Search Tree**.  Each program reads data into its respective structure from a csv file, and allows a user to display all items, search the strucutre and display a single item, as well as manipulate the structure by adding or removing an item.  Over time, these programs has been updated for bug fixes and security, and feature adds such as timing operations to compare performance of different operations.

[![Image](/images/6008765.jpg)](https://raw.githubusercontent.com/JimmyBoomBots3000/JimmyBoomBots3000.github.io/main/images/art1.jpg)  

### Databases

...  

### Contact

[JamesBRichmond@protonmail.com](mailto:JamesBRichmond@protonmail.com)
