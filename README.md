<h1>Django Blog</h1>

<p>Welcome to Django Blog, a simple web application where users can sign up, log in, create, edit, and delete blog posts. This application uses SQLite as the database.</p>

<h2>Features</h2>

<ul>
  <li>Sign up and log in with a unique username and password</li>
  <li>Create, edit, and delete blog posts</li>
  <li>View all blog posts on the home page</li>
</ul>

<h2>Requirements</h2>

<ul>
  <li>Python 3.x</li>
  <li>Django 2.x</li>
</ul>

<h2>Usage</h2>

<ol>
  <li>Clone the repository: <code>git clone https://github.com/ishworii/django_blog.git</code></li>
  <li>Navigate to the project directory: <code>cd django_blog</code></li>
  <li>Create a virtual environment and activate it:
    <pre>
python -m venv venv
source venv/bin/activate
    </pre>
  </li>
  <li>Install the required packages: <code>pip install -r requirements.txt</code></li>
  <li>Migrate the database: <code>python manage.py migrate</code></li>
  <li>Create a superuser: <code>python manage.py createsuperuser</code></li>
  <li>Run the development server: <code>python manage.py runserver</code></li>
  <li>Open a web browser and go to http://localhost:8000/ to view the application</li>
</ol>

<h2>License</h2>

<p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more information.</p>
