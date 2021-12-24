# web-engineering-assignment
Todo and Blog Application
In this assignemnt-based project, I have implemented a session based Todo and Blog application using PDO's approch.

Salient Features
Session based Todo App implemention.
Blog App using PDO.
Session based authentication mechanism.
Only logged in users can post new blogs.
Read blog page is set public.
Using given below credentials, one can post blog using local server, email me at csmdot84@gmail.com to get list of users of live server.

    $users = array(
        array("user" => "user1@blog.com", "pass" => "pass1", "name" => "Johnny"),
        array("user" => "user2@blog.com", "pass" => "pass2", "name" => "Petter"),
        array("user" => "user3@blog.com", "pass" => "pass3", "name" => "Plotter"),
    );
How to setup and run the code
Clone this repo using git clone https://github.com/jahangir121988/web-engineering-assignment/edit/main/README.md. There is a file dbSetup.php in root directory, which will generate a dummy database with some record to test the blog side of application. Run it on localhost using http://localhost/todo&blog-app/dbSetup.php url.

How to run the application
Open browser and visit http://localhost/todo&blog-app and test it on local server.
One copy of this code is also deployed on live server at https://todo-blog.000webhostapp.com/
Odds
Some logical fixes are still pending to do...will fix soon.
Screenshots
Navbar when there is a guest user.

Navbar when there is a guest user. Logged-out Navbar Navbar when there is a logged-in user. Logged-in Navbar On home page there display components of Todo and Read blog are imported from components.php and these same components are used in todo.php and blog.php, respectively. Home Page 

On Todo Page there is a add task component with display Todo component. 
