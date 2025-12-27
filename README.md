<h1>Employee Management</h1>

[//]: # (Introduction section)
<h2>1) Introduction</h2>

<h3>What is this project about?</h3>
<p>This is a project of managing employees in <b>Tech</b> of a fake company, where you can manage employees like in real projects that 
companies use. This project has two parts: Admin and user (Employee). You'll know more about in next sections.</p>

<h3>Why does this project exist?</h3>
<p>The goal of this project is to practice building a modular and scalable desktop applications using <b>Java, and JavaFx</b>, while
applying clean architecture and <B>SOLID</B> principals.</p>

<h3>Technologies I will use:</h3>
<ul>
    <li>Java.</li>
    <li>JavaFx.</li>
    <li>Database (SQLite).</li>
    <li>SOLID principals.</li>
    <li>Maven dependencies.</li>
    <li>MVC Architecture.</li>
    <li>Scene Builder.</li>
    <li>CSS.</li>
    <li>Jackson Library.</li>
    <li>HTML in creating README.md file.</li>
</ul>
<p>I might add another technologies if I needed</p>

[//]: # (Project ideas section)
<h2>2) Project features</h2>
<ul>
    <li><b>Adding different employees:</b> Backend, Frontend, Cybersecurity, DevOps, and Mobile.</li>
    <li><b>Filtering data:</b> Gender, City, Role, Salary, etc.</li>
    <li><b>Updating employees data:</b> Salary, Role, Address, Age, etc.</li>
    <li><b>Saving and opening files.</b></li>
    <li><b>Deleting employees.</b></li>
    <li><b>Settings in both part:</b> Admin and user.</li>
    <li><b>Company statistics: </b> Average salaries, males, females, numbers of employees types, number of employees form each city, average age, etc.</li>
    <li><b>Searching for a specific employee using: </b> ID and name.</li>
    <li><b>Table for showing all the employees.</b></li>
    <li><b>Managing tasks.</b></li>
    <li><b>Role-Based permissions.</b></li>
    <li><b>Internal Messaging System.</b></li>
    <li><b>Logs System.</b></li>
    <li><b>Performance Review.</b></li>
    <li><b>User interface.</b></li>
    <li><b>Admin interface.</b></li>
    <li><b>Employee Profile and Documents.</b></li>
    <li><b>Authentication and Authorization.</b></li>
</ul>

[//]: # (Project structure section)
<h2>3) Project structure:</h2>

```
SRC
├───main
│   ├───java
│   │   └───org
│   │       └───example
│   │           ├───Controllers
│   │           │   ├───AdminControllers
│   │           │   └───UsersControllers
│   │           ├───DAO
│   │           ├───Enums
│   │           ├───Interfaces
│   │           ├───Models
│   │           ├───Repositories
│   │           └───Services
│   │               ├───Filters
│   │               ├───Managers
│   │               └───Statistics
│   └───resources
│       ├───Images
│       ├───Scenes
│       │   ├───AdminScenes
│       │   └───UsersScenes
│       ├───Sounds
│       └───Styles
└───test
    └───java
 ```