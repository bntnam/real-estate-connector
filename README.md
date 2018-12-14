<img class="img-fluid mb-5" src="http://bntnam.github.io/img/portfolio/real-estate-connector-1.png" alt="">
<img class="img-fluid mb-5" src="http://bntnam.github.io/img/portfolio/real-estate-connector-3.png" alt="">
<img class="img-fluid mb-5" src="http://bntnam.github.io/img/portfolio/real-estate-connector-2.png" alt="">
<h3>1. Introduction</h3>
<p><strong>1.1. Source Code:</strong> <a href="https://github.com/bntnam/real-estate-connector" target="_blank">https://github.com/bntnam/real-estate-connector</a></p>
<p><strong>1.2. Run project locally:</strong></p>
<ul>
  <li>Clone project from github and go to project folder: <strong>cd real-estate-connector</strong></li>
  <li>Setup virtual environment. For Python3 version: <strong>python3 -m venv ./venv</strong> </li>
  <li>Access virtual environment (on MacOS): <strong>source ./venv/bin/activate</strong> </li>
  <li>Install dependencies: <strong>pip install -r requirements.txt</strong></li>
  <li>Install PostgreSQL, create database and config "database name, username, password" in settings.py</li>
  <li>Create database records from models: <strong>python manage.py migrate</strong></li>
  <li>Run project: <strong>python manage.py runserver</strong></li>
</ul>
<h3>2. Technologies</h3>
<ul>
    <li><strong>Backend:</strong> Python, Django.</li>
    <li><strong>Frontend:</strong> Bootstrap, HTML, CSS and some libraries/tools.</li>
    <li><strong>Database:</strong> PostgreSQL.</li>
</ul>
<h3>3. Features</h3>
<ul><strong>User Interface:</strong>
  <li>Register / Login</li>
  <li>Search for real estates</li>
  <li>Contact realtors by sending a message</li>
</ul>
<ul><strong>Admin Portal: based on Django Admin features</strong>
  <li>Create / Delete / Update real estate information</li>
  <li>Create / Delete / Update realtors</li>
  <li>Create / Delete / Update users</li>
</ul>
