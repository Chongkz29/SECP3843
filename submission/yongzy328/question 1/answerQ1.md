<a href="https://github.com/drshahizan/SECP3843/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/SECP3843" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/network/members"><img src="https://img.shields.io/github/forks/drshahizan/SECP3843" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/SECP3843" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/issues"><img src="https://img.shields.io/github/issues/drshahizan/SECP3843" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/SECP3843?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2FSECP3843&labelColor=%23d9e3f0&countColor=%23697689&style=flat)


Don't forget to hit the :star: if you like this repo.

# Special Topic Data Engineering (SECP3843): Alternative Assessment

#### Name: Yong Zhi Yan
#### Matric No.: A20EC0172
#### Datatset: City Inspections	

## Question 1 (a)
The 5 servers of this project are implemented as below:
<table>
  <thead>
    <th>Server</th>
    <th>Functionality</th>
  </thead>
  <tbody>
    <tr>
      <td>Web server</td>
      <td>Used to handle the network routings (including the incoming requests and outgoing responses) between the user's browser and the Django framework through HTTP protocols. Examples of web server services are Apache HTTP Server, Nginx, and Microsoft IIS.</td>
    </tr>
    <tr>
      <td>Database Server 1 (MySQL)</td>
      <td>Used to host the MySQL database for the system. It is crucial in handling the client's request from the application and executing the database operations such as inserting, querying, updating and deleting through the SQL queries. Django application will connect to this database using the package <code>mysqlclient</code>.</td>
    </tr>
    <tr>
      <td>Database Server 2 (MongoDB)</td>
      <td>Used to host the MongoDB database for the system. It is significant in handling high volume of unstructured data of the Django application through the processes of storing and retrieving. The package <code>djongo</code> is applied to manage the connection between Django framework and MongoDB database.</td>
    </tr>
    <tr>
      <td>File Server</td>
      <td>Used as a file storage system that responsible for managing all the files which will be accessed by the users through the application or system over the network. Example of file servers are Server Message Block (SMB) and Network File System (NFS) which enable the files to be accessed remotely by the client.</td>
    </tr>
    <tr>
      <td>Load Balancer</td>
      <td>Used to evenly distribute the incoming and outgoing network traffic accross the available servers in order to optimize the overall performance, increase realibility and prevent overload of the Django application. </td>
    </tr>
  </tbody>
</table>

### Steps to Integrate Django with JSON dataset
#### 1. Set up Django Application
Using the Command Prompt (CMD), change the directory to the created project folder's location (the AA folder in this case) and then set up a virtual environment for it by running the command <code>py -m venv env</code>. Then run the virtual environment by using the command <code>env\Scripts\activate</code>. <br>
<img src="./files/images/Screenshot%202023-06-27%20153108.png" alt="activate virtual environment"><br>

<img src="./files/images/Screenshot%202023-06-27%20153218.png" alt="install django mysqlclient pymongo">

<img src="./files/images/Screenshot%202023-06-27%20153237.png" alt="install djongo">

<img src="./files/images/Screenshot%202023-06-27%20153149.png" alt="django start project">

<img src="./files/images/Screenshot%202023-06-27%20153205.png" alt="startapp">

<img src="./files/images/Screenshot%202023-06-27%20164105.png" alt="setting.py">

<img src="./files/images/Screenshot%202023-06-28%20015242.png" alt="database setting">

<img src="./files/images/Screenshot%202023-06-28%20153939.png" alt="model">

<img src="./files/images/Screenshot%202023-06-28%20015411.png" alt="make migrations">

<img src="./files/images/Screenshot%202023-06-28%20015441.png" alt="migrate">

<img src="./files/images/Screenshot%202023-06-28%20015852.png" alt="mysql after migration">

<img src="./files/images/Screenshot%202023-06-28%20153924.png" alt="loaddata.py">

<img src="./files/images/Screenshot%202023-06-28%20162050.png" alt="loaddata json">

<img src="./files/images/Screenshot%202023-06-28%20162035.png" alt="load data success">











<code>python manage.py loaddata city_inspections.json</code>

## Question 1 (b)
<img src="./files/images/use%20case%20diagram%20(current%20system)%20-%20Page%203.png" alt="system architecture">





## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/special-topic-data-engineering/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)



