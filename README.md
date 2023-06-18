# Theresa Kincaid's ePortfolio

#### Table of Contents:
1. Professional Self-Assessment
2. Software Design and Engineering
3. Algorithm and Data Structures
4. Database
5. Code Review

## 1. Professional Self-Assessment
Hello, I'm Theresa Kincaid. By the end of June 2023, I will have successfully completed my Bachelor of Computer Science from Southern New Hampshire University. I have genuinely cherished my experience in the computer science program. I am impressed by the program’s curriculum, which has equipped me with a broad range of skills that cover various areas within the field of computer science. Continuing on, I would like to reflect on some of the most significant experiences and accomplishments I have had during my journey in this computer science program.

#### Collaborating in a Team Environment
While working on my program, I developed strong teamwork skills that are necessary for successful software development projects. In addition to strengthening my technical skills, the course IT-315 Object Oriented Analysis and Design also emphasized the importance of effective collaboration within a team environment. Throughout the course, we engaged in a group project, constructing a student information system. This system handled tasks such as class registration, verification, and management of student and course data. Working on this group project provided me with valuable experience in collaborating with my peers to tackle software design tasks. This involved participating in group discussions, creating diagrams and presentations, and maintaining requirement documentation. Overall, this course allowed me to enhance my ability to effectively contribute towards shared goals. 

I also credit the CS-310 Collaboration and Team Project course for equipping me with the necessary skills to excel in collaborative team efforts. In this course, I utilized change control tools while working on a software project. Using a shared Git repository, we collectively built a calculator application. This project was a Java program, with the repository serving as a central hub for collaboration. I gained skills essential for team collaboration, including repository cloning and setup, branching and merging, committing changes with meaningful commit messages, pulling changes from and pushing changes to a shared repository, resolving conflicts, conducting code reviews, and providing high-quality feedback.

#### Communicating to Stakeholders

#### Data Structures and Algorithms

#### Software Engineering and Database

#### Security

#### Artifacts

## 2. Category One: Software Design and Engineering
This artifact is a Java application called “SlideShow” and was originally created in the course CS-250. It started as a slideshow with six slides and two navigation buttons, “Previous” and “Next”. The slides show various wellness related locations, each with an image and a brief description.

I have chosen to include this artifact in my ePortfolio for the software design and engineering category for the following reasons: First, it serves as evidence of my accomplishment of the course outcome, "Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science”. This code is valuable because it provides a visually appealing and interactive way for users to explore different wellness destinations. It accomplishes industry-specific goals related to creating engaging presentations and displaying information to users. The modular design of the code, the naming conventions, and the event-driven architecture all align with industry best practices. Additionally, the program follows a structured approach with well-defined methods and classes. This demonstrates my ability to organize code logically and modularize functionality.

To improve the application, I incorporated two additional buttons and implemented a timer. The first button, labeled “Restart,” allows the user to go back to the first slide and restart the slideshow from the beginning. The second button, labeled “Pause/Resume,” provides the user with the ability to pause and resume the automatic slideshow progression. When the user clicks the button, it pauses the timer and stops the automatic slide transition. Clicking the button again resumes the slideshow. The text for this button dynamically adjusts according to the state of the timer. The timer implementation adds a time interval of 3 seconds between each slide transition, providing a consistent progression through the slides. Together, these improvements create a more interactive and user-friendly experience, offering greater control over the slideshow navigation.

Overall, my experience with making these changes to the artifact was relatively trouble-free. The most demanding aspect of the enhancement was implementing the timer. While understanding the logic of the timer was easy, ensuring that the timer coordinated effectively with the card layout and slide transitions took more time. Nevertheless, I am glad I was able to implement a timer because now the slideshow successfully runs automatically.

## 3. Category Two: Algorithm and Data Structures
This artifact is a Java application named "PeopleWeights" that allows users to manage a list of people's names and their corresponding weights. It also displays useful statistics regarding those weights. This artifact was originally created as part of the IT-145 course.

I included this artifact in my ePortfolio because it fulfills the course outcome of designing and evaluating computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while effectively managing trade-offs involved in design choices. First, the code utilizes algorithmic principles, such as bubble sort for sorting the weights array and calculating the standard deviation. It also uses iterative loops and conditional statements to perform tasks based on user input. For computer science practices, the code follows standard practices of organizing code into functions and modularizing the solution. It uses appropriate naming conventions, formatting standards, and includes comments to improve code readability. The code manages trade-offs involved in design by considering factors such as time complexity, space complexity, and code efficiency. For instance, I chose the bubble sort algorithm for simplicity. Bubble sort algorithms are effective for sorting smaller data sets. However, if the data set were larger, I would have used an algorithm that prioritizes time complexity.

The first version of the program prompted the user to enter the names and weights of five people, calculated the total weight, average, and maximum, and then displayed the results. Expanding on this existing functionality, I have enhanced and refined this artifact. I added a menu that presents users with a range of options. This allows users to choose between displaying all records, entering a new record, searching for a record, and quitting the program. This menu-driven approach provides a structured workflow for managing the data. To improve the presentation of data, I implemented an algorithm to sort the weights in ascending order. This ensures that the records are displayed in a more organized manner. By incorporating sorting, users can observe the progression of weights. Lastly, I included the calculation of the standard deviation. This statistical measure provides insights into the distribution of weights. With the inclusion of menu options, sorting, and standard deviation calculation, the program now delivers more value.

When reflecting on the process of enhancing this artifact, I am pleased to say that it was a generally smooth journey. The implementation of the standard deviation calculation was the most intricate aspect of the enhancement. The standard deviation calculation involves multiple steps and requires an understanding of statistical concepts. I am satisfied that I managed to implement this calculation because it adds complexity to the program that goes beyond simple, straightforward calculations like total, average, or maximum.

## 4. Category Three: Database
This artifact is a MongoDB interface with JavaScript and HTML It interacts with a MongoDB database called “nationalmotors” for a fictional company, National Motors. It performs various operations within the "sales" collection. This collection contains records of sales figures for different store locations. This artifact was originally from the course DAT-300.

I have included this artifact in my ePortfolio because it demonstrates my achievement in meeting the course outcome of building collaborative environments that enable different audiences to support organizational decision-making in the field of computer science. By creating a database, a script, and user interface, I have built a system that allows users to interact with the National Motors data set. This provides a more efficient way for users to collaborate with others in accessing, changing, and analyzing these sales records. Users can make changes such as adding new entries, revising existing sales figures, or removing records all together. Analyzing monthly sales figures can help National Motors predict future sales trends and guide decisions related to revenue management. The artifact also meets the course outcome of developing a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources. The artifact incorporates error handling to enhance the reliability of the system by logging errors to the console. The logged error message specifies which operation encountered an error. This can make it easier to locate and troubleshoot issues within the application. Additionally, the JavaScript program closes the MongoDB server connection after each operation, reducing the risk of unintended behavior from the system.

The artifact started out as raw a data set containing sales figures spanning 28 months for six locations: Kansas City, Chicago, Houston, Oklahoma City, Omaha, and Little Rock. To improve the artifact, I set up the database with MongoDB. After importing the original data set into the database, I created two essential files: a JavaScript file and an HTML file. The JavaScript program includes the logic to sets up four different operations: Search, Enter, Update and Delete. It includes predefined queries for the search and delete operations that can be easily modified by users. Each of the operation functions logs successful connections, as well as the results of the given operation. The HTML file provides an intuitive user interface with the company’s name, a menu for the operations, and a submit button.

Among the three artifact enhancements I implemented for my ePortfolio, I found this enhancement to be the most complex one. The task of setting up the MongoDB database for National Motors and ensuring a reliable connection tuned out to be an interesting process. Unlike my previous experiences with databases, where the environments were pre-configured, this artifact enhancement required me to create the database and establish a connection independently. However, this was an excellent learning experience that provided me with a deeper understanding of the complexities associated with establishing a new environment from scratch. I am pleased to have this artifact in my ePortfolio because it helps demonstrate the diversity of my skills.

## 5. Code Review
I have achieved one of the course outcomes by creating a comprehensive code review and sharing it on YouTube. This code review demonstrates my ability to design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and tailored to specific audiences and contexts. For each artifact, I covered the existing functionality, reviewed the code structure, comments, and explained the planned enhancements, highlighting their benefits and impact. The code review link can be found below.

[Click to Watch Code Review](https://youtu.be/WvT-Tb2NSYo)
