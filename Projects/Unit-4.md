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
![system diagram](https://github.com/maytemirabel/unit-4/assets/105724334/37a38ba3-c656-4905-a6e0-36cf41eee549)

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
| 17 | Testing | Unit Testing for Login & Register Page | Feedback will be gathered to deduce the functionality of the pages | 30 min | April 18 | C | 
| 18 | Development | Construct CSS for the Home Page | A clear and visually-pleasing front-end of the Home page | 40 min | April 18 | C |
| 19 | Development | Build the Search Bar | A tool that fascilitates the search of recipes uploaded to the website | 50 min | April 18 | C |
| 20 | Development | Create the Profile Page | If logged in, user will be able to view posts they have published | 50 min | April 19 | C |
| 21 | Development | Build the CSS for the Profile Page | An aesthetic display of the user's information | 40 min | April 19 | C |
| 22 | Development | Develop the New Post Page | Users will be able to upload their recipes to the website | 60 min | April 19 | C | 
| 23 | Development | Create the CSS for the New Post Page | Clear visuals that guide the user through the recipe-uploading process | 50 min | April 20 | C |
| 24 | Testing | Unit testing for New Post Page | Insights on the New Post Page and whether the inputs are saved in the database connected | 30 min | April 30 | C | 
| 25 | Development | Construct the Landing Page | Page user will be able to either log in to their account or register a new account | 40 min | May 1 | C |
| 26 | Development | Build the CSS for the Landing Page | An easy-to-use and optically satisfying website page users can interact with | 50 min | May 1 | C |
| 27 | Development | Create the Converter Page | When used, users can obtain a certain value in a selected unit in its conversion in another unit | 70 min | May 2 | C |
| 28 | Development | Put together the CSS for the Converter Page | Simple and easy to interact amount converter page | 80 min | May 2 | C |
| 29 | Development | Set-up Logout system | Allows client to log out of their accounts and returns to Landing Page | 30 min | May 3 | C |
| 30 | Development | Code Delete Post system | Users can delete posts from the database they have uploaded | 70 min | May 3 | C |
| 31 | Development | Finalize all functionality codes | Ensure all pieces of code perform as expected | 50 min | May 5 | C |
| 32 | Development | Finalize all CSS | Confirm the website's overall front-end is satisfactory and easy to use | 60 min | May 6 | C |
| 33 | Testing | Beta Testing of finalized website | Feedback is collected based on observations made by the test users | 30 min | May 7 | C | 
| 34 | Development | Beta Developing | Improved website based on feedback gathered | 50 min | May 7 | C |
| 35 | Implementation | Evaluation by Client | Client feedback is gathered for further improvement | 20 min | May 8 | E | 
| 36 | Development | Final touches based on Client's observations | Refering back to the client's observations, improvements are made | 40 min | May 8 | C |
| 37 | Evaluation | Evaluate the success criteria's level of accomplishment | Assess whether the needs established at the start of the project have been met or not | 30 min | May 9 | E | 
| 38 | Functionality | Film final video | A video walking through the overall functionality of the completed website | 30 min | May 9 | D | 
| 39 | Evaluation | Deliver final product to client | Client's requirements and needs are met | 10 min | May 10 | E | 


## Criteria C: Development

### Tools Utilized
| Tools | Explanation of Use |
|-------|---------|
| Flask Library | As Python's web framework, it enabled the use of templates, cookies and other elements essential to website development. |
| PyCharm | PyCharm was the software in which the website was developed in. |
| Python | This language was used for the development of the website. Its extensive tools and website-developing specific libraries were especially helpful throughout the process.  |
| HTML/CSS | Together, HTML and CSS formed the front-end of the website. HTML assembled the strcuture and content of the web pages while CSS tackled the design and layout aspect. The two were utilized to make the website engaging and user-friendly. | 
| SQLite | In order to store all of the sets of information on the client-side of the website, SQLite was used. As a database management system, all of the data the user input was saved in a database called **project4.db**. |
| Chat GPT | This tool was used for problem solving consultation when the root cause of the issue was not easy to understand nor identify. Furthermore, code logistics and general ideas were developed with the help of this tool. |

### Techniques Utilized
| Techniques | Explanation of Use |
|-------|---------|
| For loops | This kind of loop allowed certain pieces of code to be executed repeatedly for a specified number of times or until a certain condition was met.  |
| If-else statements | These conditional statements permitted the execution of different blocks of code depending on whether a condition is true or false. It was heavily used in user-input validation. |
| Functions | Self-contained blocks that were used to improve code readability and reduce redundancy. | 
| Password encryption | Technique used to change a plain-text password into a non-readable formate that is more secure. It allows the user information to be kept confidential and less susceptible to unothorized access. | 
| Database interaction (SQLite) | Database managing was an essential aspect of this project as all of the input the user makes is saved in respective parts of the database. SQLite allowed the storage and management of this data.  | 
| HTTP Cookies | Cookies were utilized for the management of user sessions in the website. As soon as the user logs in, a cookie is created that stores a unique session ID. | 

### Code
Navigation Bar

```.py 
<div class="nav-parent" style="background: white; position: fixed; overflow: hidden;">
    <ul style="display: flex; flex-direction: row; list-style-type: none;">
        <li style="width: 10%"><a href="/home" class="logo"><img src="/Project_Files/static/logos/trans.png"
                                                                 style="width: 50px"><span class="logo"></span></a></li>
        <li style="width: 10%"><a href="/home" style="text-decoration: none;"><i class="fa fa-home"
                                                                                 style="color:#9C61F1;"></i><span
                class="nav-item">Home</span></a></li>
        <li style="width: 10%"><a href="/pet_care" style="text-decoration: none;"><i class="fa fa-heart"></i><span
                class="nav-item">Pet Care</span></a></li>
        <li style="width: 10%"><a href="/shelters" style="text-decoration: none;"><i class="fa fa-dog"></i><span
                class="nav-item">Shelters</span></a></li>
        <li style="width: 10%"><a href="/saves" style="text-decoration: none;"><i
                class="fa-regular fa-bookmark"></i><span class="nav-item">Saved</span></a></li>
        <li style="width: 10%"><a href="/profile" style="text-decoration: none;"><i class="fa fa-user"
                                                                                    style=""></i><span class="nav-item">Profile</span></a>
        </li>
        <li style="width: 10%"><a href="/logout" class="logout" style="text-decoration: none;"><i
                class="fa fa-sign-out-alt"></i><span class="nav-item">Log out</span></a></li>
    </ul>
</div>
```
The navigation bar is an important part of any web application for integration and for the user's experience. I used icons from font awesome to use icons for this website as isual icons are helpful in websites as they provide a quick and intuitive way to convey information, guide user actions, and enhance the overall user experience by facilitating easy recognition and understanding.

Registration System

Although the client did not specify an encrypted registration or log in system in the success criteria, it is important to discuss this step as a secure log in and registration system are good practices of a developer.
```.py
@app.route('/Register', methods=["GET", "POST"])
def signup():
    msg = ""
    if request.method == "POST":
        email = request.form['email']
        passwd = request.form['passwd']
        passwdconfirm = request.form['confirmpasswd']
        if passwd == passwdconfirm:
            hash = encrypt_password(passwd)
            db = database_worker("project4.db")
            new_post = f"INSERT into users (email,password) values('{email}','{hash}')"
            db.run_save(query=new_post)
            return redirect(url_for('login'))
        else:
            msg = "Passwords do not match"
    return render_template("Register.html", message=msg)
 ```
The provided code represents a Flask route called '/signup' that handles the signup functionality for my web application Woof Wise.In line 1, route declaration is done, meaning the code will handle requests related to '/signup'. The naming of this app route is deliberate to ensure that the code is comprehensive & organized. Line 4 if request.method=='POST' ensures that the code indented under line 4 will only be ran once the user clicks submit. This submit button is located in the HTML end of the app route. If the method is not POST, the user will stay access to the signup page. Lines 5 to 7 are used to extract data from the submitted form. Specifically, lines 5 to 8 retrieves the value entered in the 'username', 'password', and 'email' fields respectively of the signup form. Then lines 9 to 10 focus on database interaction. database_worker, a custom class previously explained in this documentation, initializes a connection to the woof.db SQLite database. Line 10 existing_user = db.search(f"SELECT * from users where email = '{email}' or username='{username}'") executes a SELECT query to check if a user with the given email or username already exists in the database. Meanwhile lines 11 to 19 focus on validation and error handling. Specifically, if an existing user is found, line 13 and 15 checks if the email or username inputted is already registered in the database. If so, the code will output a message stating that a user already currently uses the email or username typed in. Line 17 checks if both username and email are already registered and outputs a message suggesting to the user to perhaps log in instead of registering a new account. Line 19 checks if all these criteria were not met and moves on into generating a query to the database, inserting the new user, email, and password provided. The password provided is kept encrypted as seen in line 20 where encrypt_password, a custom class that hashes a given text, is used before inserting the value password to the database. This query is committed to the database and a new row of data appears in the database. db.close closes the database connection. Finally, the user is redirected to the home page upon successful sign up.

Log in System
```.py
@app.route('/Login', methods=["GET","POST"])
def login():
    msg = ""
    if request.method == "POST":
        email = request.form['email']
        password = request.form['password']
        if len(email) > 0 and len(password) > 0:
            db = database_worker("project4.db")
            user = db.search(f"Select * from users where email = '{email}'")
            if user:
                user = user[0] #search returns a list, so only one is selected here
                id, email_db, hashed = user
                if check_password(hashed_password=hashed, user_password=password):
                    response = make_response(redirect('Home'))
                    response.set_cookie('user_id', f"{id}") #cookie is a string
                return response
            else: msg = "Incorrect password! Try again!"
        else:
            msg = "User does not exist."
    return render_template("Register.html", message=msg)

        
```
The provided code handles the login functionality for the Woof Wise web application. It checks if the submitted username or email exists in the database, verifies the password, and authenticates the user by setting a cookie. It also handles error scenarios, such as incorrect passwords or non-existing users.

In line 1, the route decorator is used to specify that this code will handle requests related to the '/login' URL. This code represents the login page of the application. The methods argument is set to ['GET', 'POST'], indicating that this route can handle both GET and POST requests. Starting from line 3, the code checks if the request method is POST, which indicates that the user has submitted the login form. If it is, the code proceeds to extract the username and password from the submitted form in lines 4 and 5, respectively.

In line 6, the code initializes a connection to the 'woof.db' SQLite database using the database_worker class. This class allows interaction with the database. Next, in line 7, a SELECT query is executed to check if a user with the provided username or email exists in the database. The existing_user variable holds the result of this query. In line 8, the password provided by the user is compared to the hashed password stored in the database using the check_password function. If the existing_user is not empty and the password matches, the user is considered authenticated, and the code proceeds to line 12.

In line 12, a response object is created using make_response. It either renders the 'profile.html' template or redirects the user to the 'home' route using the redirect function from the url_for module. This line sets the response's cookie named 'user_id' with the value of the existing user's username. The code in lines 14 and 15 handles incorrect password scenarios. If the password does not match, an error message is displayed in line 14, and the login template is rendered again with the error message. If the existing_user is empty, indicating that the user does not exist in the database, the code proceeds to line 17 and prints a message stating that the user does not exist. Finally, in line 20, the database connection is closed, and if the request method is not POST (GET request), the login template is rendered without any error messages.

Posting Functionality [Success Criteria 1] This posting functionality fulfills success criteria one and acts as the backbone of the web application. It allows different users to post content to the application.
```.py
@app.route('/NewPost', methods=['GET','POST']) # methods used for user to upload posts
def new_post():
    msg = ""
    if request.cookies.get('user_id'): # validate the user
        user_id = request.cookies.get('user_id')
        db = database_worker("project4.db")
        if request.method == 'POST': # recipe is uploaded
            title = request.form['Title']
            ingredients = request.form['Ingredients']
            instructions = request.form['Instructions']
            description = request.form['Description']
            if len(title) > 0 and len(ingredients) > 0 and len(instructions)>0 and len(description)>0:
                new_post = f"INSERT into posts (title, ingredients, instructions, description, user_id) values('{title}','{ingredients}','{instructions}', '{description}', {user_id})"
                db.run_save(query=new_post)
                posts = db.search("Select * FROM posts")
                return redirect(url_for('Project-Home', posts = posts ))
            else:
                msg = "Fields Incomplete: Please enter Title, Ingredients and Instructions"
                return render_template("NewPost.html", message=msg) # error message is displayed
        return render_template("NewPost.html", message=msg)
    else:
        return redirect('Project-Home')
 ```
In the given code snippet, a Flask route is defined at '/new_post' with the allowed methods being GET and POST. If the request method is POST, the code retrieves the data submitted in the form fields of the request using the request.form. The values of the 'title', 'content', and 'options' fields are assigned to respective variables: title, content, and flair. As stated in the tools used, this section of the code, specifically line 7 to 8, uses datetime to mark when the post was created and use this to update the database.


### Setting up tools needed

## Criteria D: Functionality and Extensibility  

## Criteria E: Evaluation

## Appendix
### Evidence of consultation 
<img width="645" alt="Screen Shot 2023-04-19 at 11 38 49" src="https://user-images.githubusercontent.com/105724334/232953946-9d9535c1-75a0-49fc-81a2-b534cffa7dce.png">

##### Figure 8. Baker at ISAK confirming the need for a recipe sharing social network 

### Works Cited
