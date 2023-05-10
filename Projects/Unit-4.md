# *Unit 4 Project: A Piece of Bake* #
![Levi Ackerman X Reader __ Under Rewriting - Chapter 4 _ Confession_](https://user-images.githubusercontent.com/105724334/231612717-3c163155-c429-4560-9950-927cdd422e90.gif)
###### Pinterest. [^1]

## Criteria A: Planning
### Problem Definition
Often times, students are ISAK are not satisfied with the limited dessert options provided by CK. The same chocolate chip cookies, sunflower cake and jelly get incredibly repetitive, leaving students with only one option: make their own desserts. Some students, including myself, in order to spread their creations, have shared their recipes in class group chats so others can learn from them. Unfortunately, these recipes are often forgotten and even worse, neglected. Bakers at ISAK are in immediate need of a social network which will allow them to share recipes and connect with each other and their cultures. 
###### *Refer to Fig. 8 in Appendix for evidence of consultation.*

### Design Statement
I will design and make a social network for all bakers in ISAK. The social network will focus on the sharing of dessert recipes with the campus community and will be constructed using Python, HTML, CSS, SQLite, and Flask. It will take approximately four weeks to make and will be evaluated according to the criteria below.

### Success Criteria
1. The social network has a secure registration and login system.
2. Recipes can be uploaded as a social media post.
3. Each user has their own profile page where their posts are displayed. 
4. Users can delete their posts. 
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
The system diagram is a visual model of the application, its components and their interactions. As shown on Fig. 1, the input is done through a keyboard and the output is manifested on the display (screen.) Although the website runs on a web browser, all of the various inputs made by the user will be saved in a local SQL database called **project4.db**.

### Wireframe
![Comp Sci-8 2](https://github.com/maytemirabel/unit-4/assets/105724334/28878d86-4908-4153-9ece-dc61707eec19)

##### Figure 2. The Wireframe for the Application
The wireframe provides a visual representation of the website's design before any code is made. It also displays the functionalities of every button planned out to be utilized, which is helpful as the developer as there is a model to refer back to if in doubt.  

### ER Diagram
<img width="998" alt="Screen Shot 2023-05-10 at 21 00 59" src="https://github.com/maytemirabel/unit-4/assets/105724334/2484aa41-db6b-430c-bee9-f3c7fa0a72df">


##### Figure 3. ER Diagram
The ER diagram shows the two tables: users and posts, and how they relate to each other within the system. 

### UML Diagram
<img width="506" alt="Screen Shot 2023-05-10 at 20 45 23" src="https://github.com/maytemirabel/unit-4/assets/105724334/1f871705-b656-4bc3-97d7-bb536fa27418">


##### Figure 4. The UML Diagram For the Classes In the Application
The UML diagram allows easy vizualization of the website before it is developed. The diagram shown in Fig. 4 vizualises the handling database interactions such as executing queries, saving changes, and closing the connection.

### Flow Diagrams

##### Figure 5. Flow diagram of 

##### Figure 6. Flow diagram of

##### Figure 7. Flow diagram of

### Test Plan
| Test No. | Test type | Description | Input / Procedure | Outcome |
|--------|-----------|-------------|-------|---------|

### Record of Tasks
| Task No. | Design Cycle Step | Planned Action | Planned Outcome | Time estimate | Target completion date | Criterion |
|---------|------------------------------------------------|----------------------------------------|-------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1 |  Planning | Define problem context | A concise problem definition that will allow the developer (me) identify all the necessary components to solve the problem | 20 min | April 13 | A | 
| 2 | Planning | Consult potential network users | Confirmation of what the issue is, feedback on solution. Adgustments are made if necessary | 10 min | April 13 | A | 
| 3 | Planning | Write proposed solution and rationale | A concrete and reasoned solution that addresses the issue exposed and its components | 30 min | April 13 | A |
| 4 | Planning| Write design statement | A clear plan and goal for the project following the Design Statement format | 10 min | April 13 | A | 
| 5 | Planning | Define success criteria | Clear needs and expectations of the project are outlined | 20 min | April 14 | A |
| 6 | Planning | Write rationale for proposed solution | A detailed description and reasoning for the developed solution | 30 min | April 14 | A | 
| 7 | Designing | System Diagram | A visual idea of the software and hardware requirements involved in the development of the application | 50 min | April 15 | B |
| 8 | Designing | Draw the website's wireframe | Visual illutration of the website's overall structure and its functionalities | 40 min | April 15 | B | 
| 9 | Designing | Create ER diagram | A diagram that illustrates the objects in the website and how they relate to each other | 30 min | April 16 | B | 
| 10 | Designing | Create UML diagram | A visual representation that showcases the multiple classes and methods used for the website | 40 min | April 16 | B |
| 11 | Designing | Draw flowcharts | Diagrams that outline the sequence of snipets of the overall program | 40 min | April 16 | B |
| 12 | Development | Initialize database handler | Set-up the database where all information will be saved in an organized manner	| 15 min	| April 17	| C |
| 13 | Development | Create the Login Page | A secure system that allows the user to access the website using an existing username and password | 40 min | April 17 | C | 
| 14 | Development | Build the CSS for the Login Page | An improved front-end of the website's login in page which users will be able to enjoy and navigate through the website | 40 min | April 17 | C | 
| 15 | Development | Create the Register Page | Users will be able to create an account in order to access the website | 50 min | April 17 | C |
| 14 | Development | Build the CSS for the Register Page | An improved front-end of the website's register which users will be able to enjoy and navigate through the website  | 30 min | April 17 | C | 
| 16 | Development | Create the Home Page | The screen the user encounters with when logged in to the website | 40 min | April 18 | C | 
| 17 | Testing | Unit Testing for Login & Register Page | Feedback will be gathered to deduce the functionality of the pages | 30 min | April 18 | B | 
| 18 | Development | Construct CSS for the Home Page | A clear and visually-pleasing front-end of the Home page | 40 min | April 18 | C |
| 19 | Development | Build the Search Bar | A tool that fascilitates the search of recipes uploaded to the website | 50 min | April 18 | C |
| 20 | Development | Create the Profile Page | If logged in, user will be able to view posts they have published | 50 min | April 19 | C |
| 21 | Development | Build the CSS for the Profile Page | An aesthetic display of the user's information | 40 min | April 19 | C |
| 22 | Development | Develop the New Post Page | Users will be able to upload their recipes to the website | 60 min | April 19 | C | 
| 23 | Development | Create the CSS for the New Post Page | Clear visuals that guide the user through the recipe-uploading process | 50 min | April 20 | C |
| 24 | Testing | Unit testing for New Post Page | Insights on the New Post Page and whether the inputs are saved in the database connected | 30 min | April 30 | B | 
| 25 | Development | Construct the Landing Page | Pag
| 26 | Development | Build the CSS for the Landing Page |
| 27 | Development | Create the Converter Page | 
| 28 | Development | Put together the CSS for the Converter Page |
| 29 | Development | Set-up Logout system | 
| 30 | Development | Code Delete Post system |
| 31 | Development | Finalize all functionality codes | 
| 32 | Development | Finalize all CSS | 
| 33 | Implementation | Beta Testing of finalized website | Feedback is collected based on observations made by the users | 30 min | May | 
| 34 | Developement | Improve website based on feedback gathered | 
| 35 | Implementation | Evaluation by Client |  
| 36 | Development | Final touches based on Client's observations |
| 37 | Evaluation | Evaluate the success criteria's level of accomplishment | 
| 38 | Functionality | Film final video | A video walking through the overall functionality of the completed website | 30 min | May 9 | D | 
| 39 | Evaluation | Deliver final product to client | Client's requirements and needs are met | 10 min | May 10 | E | 

## Criteria C: Development
### Tools Utilized
| Tools | Explanation of Use |
|-------|---------|
| Flask Library | As Python's web framework, it enabled the use of templates, cookies and other elements essential to website development. |
| PyCharm | PyCharm was the software in which the website launched from. |
| Python | This language was used for the development of the website. Its extensive tools and website-developing specific libraries were especially helpful.  |
| HTML/CSS | Together, HTML and CSS formed the front-end of the website. HTML assembled the strcuture and content of the web pages while CSS tackled the design and layout aspect. The two were utilized to make the website engaging and user-friendly. | 
| SQLite | In order to store all of the sets of information on the client-side of the website, SQLite was used. As a database management system, all of the data the user input was saved in a database called **project4.db**. |
| Chat GPT | This tool was used for problem solving consultation when the root cause of the issue was not easy to undertand nor identify. |

### Techniques Utilized
| Techniques | Explanation of Use |
|-------|---------|
| For loops | |
| If-else statements | |
| Functions | | 
| Password encryption | | 
| Database interaction (SQLite) | | 
| HTTP Cookies | | 

### Setting up tools needed

## Criteria D: Functionality and Extensibility  

## Criteria E: Evaluation

## Appendix
### Evidence of consultation 
<img width="645" alt="Screen Shot 2023-04-19 at 11 38 49" src="https://user-images.githubusercontent.com/105724334/232953946-9d9535c1-75a0-49fc-81a2-b534cffa7dce.png">

##### Figure 8. Baker at ISAK confirming the need for a recipe sharing social network 

### Works Cited
