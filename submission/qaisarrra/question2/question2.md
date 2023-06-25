<a href="https://github.com/drshahizan/SECP3843/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/SECP3843" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/network/members"><img src="https://img.shields.io/github/forks/drshahizan/SECP3843" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/SECP3843" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/issues"><img src="https://img.shields.io/github/issues/drshahizan/SECP3843" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/SECP3843/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/SECP3843?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2FSECP3843&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

Don't forget to hit the :star: if you like this repo.

# Special Topic Data Engineering (SECP3843): Alternative Assessment

#### Name: Qaisara binti Rohzan
#### Matric No.: A20EC0133
#### Dataset: 04 - Companies

## Question 2 (a)
The answer to the question is divided into the following segments:
* [Prerequisites](#-prerequisites)
* [Preparation of JSON file](#️-preparation-of-json-file)
* [Starting MongoDB Server](#-starting-mongodb-server)
* [Import Dataset](#-import-dataset)
* [Accessing MongoDB Shell](#-accessing-mongodb-shell)
<br></br>

### Prerequisites
To carry out the tasks of this question, it it crucial for us to do the following:
1. Install [MongoDB Community Server](https://www.mongodb.com/try/download/community)
2. Install [MongoDB Shell](https://www.mongodb.com/try/download/shell)
3. Install [MongoDB Database Tools](https://www.mongodb.com/try/download/database-tools)
4. Edit paths in the system environment variables. Include the MongoDB and Mongosh folder directory
<br></br>

### Preparation of JSON file
Ensure that you have downloaded the [Companies dataset](https://github.com/drshahizan/dataset/blob/main/mongodb/04-companies/companies.json) into your local device. Place it in a destination that is easily accessible.
<br></br>

### Starting MongoDB Server
Open command prompt by pressing on the Windows key + R **OR** type cmd or cmd.exe in the Run command box before pressing **Enter**. We can start off by inputing the command below to take regard of the MongoDB version we installed.
```bash
mongod --version
```
The next line of command processes data requests, maintains data access, and runs background management tasks. 
```bash
mongod 
```
Below shows the expected output of the commands:
<p align="center">
   <img width="947" alt="image" src="https://github.com/drshahizan/SECP3843/blob/main/submission/qaisarrra/question2/files/images/Start%20MongoDB%20Server.png">
</p>
<br>

### Import Dataset
To import the JSON dataset into MongoDB, ensure that you have already installed **MongoDB Database Tools**. In the Command Prompt Terminal, change the directory to the **bin** folder of **MongoDB - Tools**.
```bash
cd C:\Program Files\MongoDB\Tools\100\bin
```
The next line of command is used for listing computer files and directories. It is one of the fundamental instructions for navigating the file system.
```bash
dir
```
The following line of command allows us to import the dataset into MongoDB, where **-d** is the name of the database  and **-c** is the name of the collection. Do specify the correct path in which the dataset file is located. 
```bash
mongoimport "C:\Users\Qaisara Rohzan\Desktop\companies.json" -d AA -c Companies
```
Below shows the expected output of the commands:
<p align="center">
   <img width="947" alt="image" src="https://github.com/drshahizan/SECP3843/blob/main/submission/qaisarrra/question2/files/images/Import%20Dataset.png">
   <img width="947" alt="image" src="https://github.com/drshahizan/SECP3843/blob/main/submission/qaisarrra/question2/files/images/Dataset%20Successfully%20Uploaded.png">
</p>
<br></br>

### Accessing MongoDB Shell
Run the command from your server prompt to access the MongoDB shell. By default, the programme launches a shell linked to a locally installed MongoDB instance running on port 27017.
```bash
mongosh
```
The next command (after **test>**) allows us see the existing databases in our MongoDB. As you can see, the **AA** database that stores the Companies dataset can be found if you input this line of command.
```bash
show cbs
```
Below shows the expected output of the command:
<p align="center">
   <img width="947" alt="image" src="https://github.com/drshahizan/SECP3843/blob/main/submission/qaisarrra/question2/files/images/Access%20MongoDB%20Shell.png">
</p>
<br></br>

## Question 2 (b)
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/special-topic-data-engineering/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)



