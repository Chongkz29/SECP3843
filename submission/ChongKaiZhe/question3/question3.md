<a href="https://github.com/drshahizan/SECP3843/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/SECP3843" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/network/members"><img src="https://img.shields.io/github/forks/drshahizan/SECP3843" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/SECP3843" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/issues"><img src="https://img.shields.io/github/issues/drshahizan/SECP3843" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/SECP3843?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2FSECP3843&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

Don't forget to hit the :star: if you like this repo.

# Special Topic Data Engineering (SECP3843): Alternative Assessment

#### Name: Chong Kai Zhe
#### Matric No.: A20EC0186
#### Dataset: Analytics

## Question 3 (a)
### Pre-Requisites
```python
django-admin startproject AAquestion3
python manage.py startapp AAquestion3app
```
![image](https://github.com/drshahizan/SECP3843/assets/120616074/611c2808-292e-4b6f-abf0-b57d849e8dc7)

Next, we create database for this project in phpMyAdmin
![image](https://github.com/drshahizan/SECP3843/assets/120616074/99d1f476-0014-4817-9e8f-c452ef418cd5)
This the final look of the database after the project

Next, we add our app to the installed apps defination and also MySQL database in settings.py
![image](https://github.com/drshahizan/SECP3843/assets/120616074/80e25377-c89a-4318-8ccb-855d7dffb5f0)

![image](https://github.com/drshahizan/SECP3843/assets/120616074/bf991c69-a990-417c-bbcd-5c089c370a93)

### User Model
In the model we should inlcude username, name, usertype and also password.
![image](https://github.com/drshahizan/SECP3843/assets/120616074/0d5a0d1a-d3d2-46a4-b26e-ffa074de1ad8)

After that, we need to make migrations
![image](https://github.com/drshahizan/SECP3843/assets/120616074/ce2ed33a-87b6-4dbb-8c10-f79face8527a)

### Create registration, Login and also dashboard view
![image](https://github.com/drshahizan/SECP3843/assets/120616074/b0989ea7-80af-455d-aa59-acd2db304e79)
This diagram shows about the registration in views.py

![image](https://github.com/drshahizan/SECP3843/assets/120616074/6c350e4c-a80d-4daa-8018-63865d5dc6fc)
This diagram show about login in views.py
In login user will be redirect to each dahsboards depends on their usertype.

Then create a folder named templates to keep all the templates for registration, login and each users dashboard views
![image](https://github.com/drshahizan/SECP3843/assets/120616074/e2b0f962-8417-4556-8a74-85ea1bdc8f11)

This is register view
![image](https://github.com/drshahizan/SECP3843/assets/120616074/f03e8067-dd4d-4271-8858-a38ddc65e64b)

This is login view
![image](https://github.com/drshahizan/SECP3843/assets/120616074/384e3cfa-b1eb-4770-9ed5-92ba2c6b524c)

This is customer dashboard view
![image](https://github.com/drshahizan/SECP3843/assets/120616074/27154ca8-50c0-4a57-9d74-b375f81ac20b)

This is management dashboard view
![image](https://github.com/drshahizan/SECP3843/assets/120616074/2c0b7e38-e9d9-4b5f-8d93-4ec14ee608db)

This is Worker dashboard view
![image](https://github.com/drshahizan/SECP3843/assets/120616074/becf9b76-1ae7-450b-a077-04cceda61aef)

## Question 3 (b)

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/special-topic-data-engineering/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)



