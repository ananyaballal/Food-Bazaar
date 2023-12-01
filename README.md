# FoodBank
Food bank is a food review posting site developed in Django. Where user can Register, Login Then add review. User can like review, Update their own profile, Edit their posted review also can delete them. There is a comment system implement for each review.

<h2>Requirements</h2>
<pre>open requirements.txt file to see requirements</pre>

<h2>Installing</h2>
<pre>open terminal and type</pre>
<code>git clone https://github.com/devmahmud/FoodBank.git</code><br><br>

<h4>or simply download using the url below</h4>
<code>https://github.com/ananyaballal/Food-Bazaar</code><br>


<h2>To migrate the database open terminal in project directory and type</h2>
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code>

<h2>Static files collection</h2>
<pre>open terminal and type</pre>
<code>python manage.py collectstatic</code>

<h2>Creating Superuser</h2>
<pre>To create superuser open terminal and type</pre>
<code>python manage.py createsuperuser</code>

<h2> For password Reset functionality by email fill up the information in Your Project setting </h2>
<code>EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'</code><br>
<code>EMAIL_HOST = 'smtp.gmail.com'</code><br>
<code>EMAIL_PORT = 587</code><br>
<code>EMAIL_USE_TLS = True</code><br>
<code>EMAIL_HOST_USER = 'your email'</code><br>
<code>EMAIL_HOST_PASSWORD = 'your email password'</code><br>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000 in your browser</p>

<h2>Project screenshot</h2>
<h3>FoodBank Home Page</h3>
<div align="center">
    <img src="https://private-user-images.githubusercontent.com/149685593/287230292-cb0f6c02-bba0-4d2e-b060-4c48dd828d82.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDE0MjUzMDQsIm5iZiI6MTcwMTQyNTAwNCwicGF0aCI6Ii8xNDk2ODU1OTMvMjg3MjMwMjkyLWNiMGY2YzAyLWJiYTAtNGQyZS1iMDYwLTRjNDhkZDgyOGQ4Mi5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIwMVQxMDAzMjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wOTZmYTY3ZDFlMTNhNjhkY2QxMmFkNjdhODJjODI1MWU3NDFhMGYxZjg2ZmU5MzQzYTk1NjY2OTdmZjVlZTlkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.QC3o4hB0SGEW-0htFg4oyjr04q55nBXYgzFfpLA-YSg" width="70%"</img> 
</div>

<h3>User Login Page</h3>
<div align="center">
    <img src="https://private-user-images.githubusercontent.com/149685593/287230288-007116d6-5dfd-4400-80c1-3cf844e5eb52.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDE0MjUyNTIsIm5iZiI6MTcwMTQyNDk1MiwicGF0aCI6Ii8xNDk2ODU1OTMvMjg3MjMwMjg4LTAwNzExNmQ2LTVkZmQtNDQwMC04MGMxLTNjZjg0NGU1ZWI1Mi5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIwMVQxMDAyMzJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMzhmYWZlYmI3MTVlZmZkYzcyZTY2NjVkMzQ2NzY1NjU2ODAxNmE3ZDQyNzhiYWFlNDFjYzAzNTZkNDM1NzQ1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.JPA-_aaESB_VHRpHbLCnzjMlRlvdy63xY9_dnl0lbYI" width="100%"</img> 
</div>

<h3>User Registration Page</h3>
<div align="center">
    <img src="https://private-user-images.githubusercontent.com/149685593/287230277-a643ab64-a7d8-47fc-b00a-15833e3178ed.JPG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDE0MjUyNTIsIm5iZiI6MTcwMTQyNDk1MiwicGF0aCI6Ii8xNDk2ODU1OTMvMjg3MjMwMjc3LWE2NDNhYjY0LWE3ZDgtNDdmYy1iMDBhLTE1ODMzZTMxNzhlZC5KUEc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIwMVQxMDAyMzJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hNTVkNzhjNGMyZjE0YTI5Yjc4YjRjZjczNDMyNjI5NTUyMzdjZGY1MDc0OTZhZDAwMGRiYzY3N2ZiMmJhNjk2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.vgYm5AZlv6sPp1xtSG2diAnE1KtBpZASgDYH5YwP7Aw" width="100%"</img> 
</div>

<h3>Dashboard Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/54106920-e5a59180-4401-11e9-8f01-e79fe229ef78.png" width="100%"</img> 
</div>

<h3>Profile Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/54107006-1a194d80-4402-11e9-898a-1673e7ca5f31.png" width="100%"</img> 
</div>

<h3>Create Post Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/54107051-41701a80-4402-11e9-9139-ca71c74ef670.png" width="100%"</img> 
</div>

<h3>Post Details Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/54107124-6e243200-4402-11e9-9f4c-20c1c83503e9.png" width="100%"</img> 
</div>

<h2>Author</h2>
<blockquote>
  Mahmudul alam<br>
  Email: expelmahmud@gmail.com
</blockquote>

<div align="center">
    <h3>========Thank You !!!=========</h3>
</div>

