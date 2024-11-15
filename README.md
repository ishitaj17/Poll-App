# Django-Poll-App

The Django Poll App is a fully-featured platform where users must register to view polls and vote. Each user can vote on a poll only once. The poll owner has exclusive rights to manage polls, including adding, editing, updating, deleting polls and their choices, and ending polls. Once a poll is ended, it cannot be voted on and only displays the final results to users. The app includes a search feature to find polls by name and filtering options based on poll name, publish date, or the number of votes. Page navigation ensures smooth browsing, even when filters are applied.

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h2>To migrate the database open terminal in project directory and type</h2>
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code>

<h2>To use admin panel you need to create superuser using this command </h2>
<code>python manage.py createsuperuser</code>

<h2>To Create some dummy text data for your app follow the step below:</h2>
<code>pip install faker</code>
<code>python manage.py shell</code>
<code>import seeder</code>
<code>seeder.seed_all(30)</code>
<p>Here 30 is a number of entry. You can use it as your own</p>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000 in your browser</p>

<h2>Project snapshot</h2>
<h3>Home page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/home-page.jpg?raw=true" width="100%"</img> 
</div>
<h3>Login page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/login-page.jpg?raw=true" width="100%"</img> 
</div>
<h3>Register page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/register-page.jpg?raw=true" width="100%"</img> 
</div><h3>Login Details page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/login-details.jpg?raw=true" width="100%"</img> 
</div><h3>Create Poll page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/create-poll.jpg?raw=true" width="100%"</img> 
</div><h3>Poll Details page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/poll-vote-before.jpg?raw=true" width="100%"</img> 
</div><h3>Poll After page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/poll-vote-after.jpg?raw=true" width="100%"</img> 
</div><h3>Poll Added page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/poll-added.jpg?raw=true" width="100%"</img> 
</div><h3>Poll Dashboard page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/poll-dashboard-page.jpg?raw=true" width="100%"</img> 
</div><h3>Edit Poll page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/edit-poll.jpg?raw=true" width="100%"</img> 
</div><h3>Poll Ended page</h3>
<div align="center">
    <img src="https://github.com/ishitaj17/Poll-App/blob/main/Screenshots/poll-end.jpg?raw=true" width="100%"</img>
