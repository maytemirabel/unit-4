# *Unit 4 Project: A Piece of Bake* #
![Levi Ackerman X Reader __ Under Rewriting - Chapter 4 _ Confession_](https://user-images.githubusercontent.com/105724334/231612717-3c163155-c429-4560-9950-927cdd422e90.gif)
###### Pinterest. [^1]

## Criteria A: Planning
### Problem Definition
Often times, students are ISAK are not satisfied with the limited dessert options provided by CK. The same chocolate chip cookies, sunflower cake and jelly get incredibly repetitive, leaving students with only one option: make their own desserts. Some students, including myself, in order to spread their creations, have shared their recipes in class group chats so others can learn from them. Unfortunately, these recipes are often forgotten and even worse, neglected. Bakers at ISAK are in immediate need of a social network which will allow them to share recipes and connect with each other and their cultures. 
###### *Refer to Figure - in Appendix for evidence of consultation.*

### Design Statement
I will design and make a social network for all bakers in ISAK. The social network will focus on the sharing of dessert recipes with the campus community and will be constructed using Python, HTML, CSS, SQLite, and Flask. It will take approximately four weeks to make and will be evaluated according to the criteria below.

### Success Criteria
1. The social network has a secure registration and login system.
2. Recipes can be uploaded as a social media post.
3. Each user has their own profile page where their posts are displayed. 
4. Users can edit or delete their posts. 
5. Users can search for others’ profiles and recipes. 
6. User will be able to convert values from grams to ounces and vice versa. 

### Rationale for Proposed Solution
The social network A Piece of Cake will allow students to share their dessert recipes. This network will be a lot more productive than sending recipes out on class group chats, for instance, as all of the recipes will be found in the same place. There will be no need to scroll through chats in search for recipes as such will be neatly and concisely posted on the network. Not only will ISAK students’ recipes be published, but the community of bakers will grow as people will be able to interact with each other and form bonds due to their shared passion: baking. 

For the development of this social network, Python will be used as it is the most suitable for the project.
This is because, compared to languages like C++, Python has a faster development time due to its simple syntax. [^3] Furthermore, Python’s ease of comprehension allows for the work and improvement of the code by future developers, especially beginners, to be more accessible and convenient. Despite Python's limitations, like its inability to support mobile application development, its adaptable and straightforward nature makes it the most fitting language for the swift development of this social network. [^4]

Flask is a popular Python-based micro-framework for developing web applications, and it will be used to create the web application. There are several reasons why Flask may be chosen over other frameworks such as Django. Firstly, Flask provides a lightweight and modular structure, which allows developers to create web applications quickly and efficiently. [^5] Moreover, Flask's speedy implementation ensures efficiency. [^6] As feedback is gathered, Flask provides an excellent option for adding more features, enabling developers to continuously improve their products with quick integration and support systems. All of the reasons mentioned above prove why Flask is the most suitable framework for the development of this web application. 

For this website, HTML will work hand-in-hand with CSS. HTML and CSS (Cascading Style Sheets) serve as the foundation of web development, with HTML providing the structure and content of the website and CSS providing the styling and layout. Together, these languages offer the basic building blocks for creating visually appealing and responsive websites. A huge advantage of CSS is its cascading feature. [^7] This allows cascading styles to be applied from parent to child, making the customization of web pages simple. Additionally, HTML and CSS are the most accessible languages for web development, as they are supported by all major web browsers and are used by millions of websites worldwide. JavaScript, in contrast to these two languages, can be complex to learn and can also slow down a website's performance, which all goes to point that HTML and CSS are the best options regarding the design language. [^8]

The proposed solution will use SQLite as its database management system is efficient, reliable, and broadly compatible. SQLite is an open-source and free database that eliminates the need for a separate server process and licensing, allowing multiple databases to be implemented in a single file. [^9] This feature provides flexibility and ease of use, allowing work on multiple databases simultaneously within a single session. Compared to other databases such as Oracle, SQLite offers lightweight features, including safe and fast storage of various types of data without lengthy procedural routines. Additionally, SQLite provides continuous transaction updates and atomic behaviors, ensuring that a program crash or power outage won't leave the database corrupted. With its cross-platform compatibility, SQLite enables the program to be expanded to other platforms. Overall, SQLite is a cost-effective, reliable, and user-friendly database management system and the best choice for the proposed network.

[^1]: Pinterest. 13 Apr. 2023, https://www.pinterest.co.uk/pin/199917670945980784/.
[^3]:UpGrad. "10 Reasons Why Python is Popular with Developers." UpGrad Blog, UpGrad Education Private Limited, 28 Feb. 2020, https://www.upgrad.com/blog/reasons-why-python-popular-with-developers/#:~:text=The%20python%20language%20is%20one,faster%20than%20other%20programming%20languages.
[^4]: Vilmate LLC. "Python vs Other Programming Languages: A Comprehensive Guide." Vilmate Blog, Vilmate LLC, 5 Feb. 2021, https://vilmate.com/blog/python-vs-other-programming-languages/.
[^5]: Shah, Hardik. "6 Reasons Why Flask is Better Framework for Web Application Development." Able, Able Bio, Inc., 11 Feb. 2020, https://able.bio/hardikshah/6-reasons-why-flask-is-better-framework-for-web-application-development--cd398f73.
[^6]: STX Next. "Flask vs. Django – a Comparison for 2021." STX Next Blog, STX Next sp. z o.o., 11 Feb. 2021, https://www.stxnext.com/blog/flask-vs-django-comparison/.
[^7]: Devmountain. "What is CSS and Why Use It?" Devmountain Blog, Devmountain LLC, 5 Jan. 2021, https://devmountain.com/blog/what-is-css-and-why-use-it/. 
[^8]: "Web Design: HTML, CSS, and JavaScript." HubSpot Blog, HubSpot, Accessed 24 Apr. 2023, https://blog.hubspot.com/marketing/web-design-html-css-javascript#:~:text=An%20overview%3A,the%20behavior%20of%20different%20elements.
[^9]: "SQLite - Advantages and Disadvantages." javatpoint.com, Tutorials Point (India) Pvt. Ltd., Accessed 24 Apr. 2023, https://www.javatpoint.com/sqlite-advantages-and-disadvantages.

## Criteria B: Solution
### System Diagram

##### Figure 1. The System Diagram For the Application

### Wireframe
![IMG_0764](https://user-images.githubusercontent.com/105724334/234566255-509cd654-499d-46bb-a19e-ef6445e0dee1.jpg)

##### Figure 2. The Wireframe for the Application

### ER Diagram
![IMG_B5BCEDEBDD82-1](https://user-images.githubusercontent.com/105724334/234288189-d14e4fe6-d166-4a73-a437-eddd53e8875e.jpeg)

##### Figure 3. ER Diagram

### UML Diagram

##### Figure 4. The UML Diagram For the Classes In the Application

### Flow Diagrams

##### Figure 5. Flow diagram of 

##### Figure 6. Flow diagram of

##### Figure 7. Flow diagram of

### Test Plan
| Test No| Test type | Description | Input / Procedure | Outcome |
|--------|-----------|-------------|-------|---------|

### Record of Tasks
| Task No. | Design Cycle Step | Planned Action | Planned Outcome | Time estimate | Target completion date | Criterion |
|---------|------------------------------------------------|----------------------------------------|-------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1 |  Planning | Define problem context | A concise problem definition that will allow the developer (me) identify all the necessary components of the project | 20 min | April 13 | A | 
| 2 | Planning | Consult potential network users | Confirmation of what the issue is and how to solve it | 10 min | April 13 | A | 
| 3 | Planning | Write proposed solution and rationale | A concrete and reasoned solution that addresses the issue exposed | 30 min | April 13 | A |
| 4 | Planning| Write design statement | A clear plan and goal of the project | 10 min | April 13 | A | 
| 5 | Planning | Define success criteria | Clear needs and expectations of the project are outlined  | 20 min | April 14 | A |
| 6 | Planning | Write rationale for proposed solution | A detailed description and reasoning for the developed solution | 30 min | April 14 | A | 
| 7 | Designing | System Diagram | A visual idea of the software and hardware requirements involved in the development of the application | 50 min | April 15 | B |
| 8 | Designing | Draw the website's wireframe | Visual illutration of the website's overall structure | 40 min | April 15 | B | 
| 9 | Designing | Create ER diagram | A diagram that illustrates the objects in the website and how they relate to each other | 30 min | April 16 | B | 
| 10 | Designing | Create UML diagram | A visual representation that showcases the multiple classes and methods used | 40 min | April 16 | B |
| 11 | Development | Initialize database handler | Set-up the database where all information will be saved in an organized manner	| 15 min	| April 17	| C |
| 12 | Development | Create the Login Page | A secure system that allows the user to access the website using an existing username and password | 40 min | April 17 | C | 
| 13 | Development | Create the Register Page | Users will be able to create an account in order to access the website | 50 min | April 17 | C |
| 14 | Development | Create the Home Page | The screen the user encounters with when logged in to the website | 40 min | April 18 | C | 
| 15 | 


## Criteria C: Development
### Techniques Used
1. 

### Setting up tools needed

## Criteria D: Functionality and Testability 

## Criteria E: Evaluation

## Appendix
### Evidence of consultation 
<img width="645" alt="Screen Shot 2023-04-19 at 11 38 49" src="https://user-images.githubusercontent.com/105724334/232953946-9d9535c1-75a0-49fc-81a2-b534cffa7dce.png">

##### Figure . Baker at ISAK confirming the need for a recipe sharing social network 

### Works Cited
