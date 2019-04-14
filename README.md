<h1> Portfolio Website With Django.</h1>

<p1>A Django website consists of a single project that is split into separate apps. The idea is that each app handles a self-contained 
function that the site needs to perform. As an example, imagine an application like Instagram. There are several different functions 
that need to be performed:</p>
<ol>
<li>User management: Login, logout, register, and so on</li>
<li>The image feed: Uploading, editing, and displaying images</li>
<li>Private messaging: Private messages between users and notifications</li>
</ol>

<p>Each application also has its own URLs as well as its own HTML templates and static files, such as JavaScript and CSS.</p>
<p>Django apps are structured so that there is a separation of logic. It supports the Model-View-Controller Pattern, which is the
architecture on which most web frameworks are built. The basic principle is that in each application there are three separate files 
that handle the three main pieces of logic separately:</p>
<ul>
<li>Model defines the data structure. This is usually a database and is the base layer to an application.</li>
<li>View displays some or all of the data to the user with HTML and CSS.</li>
<li>Controller handles how the database and the view interact.</li>
</ul>

<p>A Django site starts off as a project and is built up with a number of applications that each handle separate functionality. Each app follows
the Model-View-Template pattern.</p>
 
 <h2>Set Up Your Development Environment</h2>
 <p>first set up your development environment. Create a new directory for your project to live in, and cd into it:</p>
 <ul>
 $ mkdir rp-portfolio<br>
 $ cd rp-portfolio
 </ul>
 <p>Once your inside the main directory, it’s a good idea to create a virtual environment to manage dependencies. There are many different ways to set
 up virtual environments, but here you’re going to use venv:</p>
 <ul>
 $ python3 -m venv venv
 </ul>
 
 <p>Now that you’ve created a virtual environment, it’s time to install Django. You can do this using pip:</p>
 
 (venv) $ pip install Django
 <h2>Create a Django Project</h2>
 <p> Django web application is made up of a project and its constituent apps. Making sure you’re in the rp_portfolio directory, and you’ve activated 
 your virtual environment, run the following command to create the project:</p>
 $ django-admin startproject personal_portfolio
 
 <h2>Read More click below</h2>
 <a href ="https://realpython.com/get-started-with-django-1/">Click here</a>
