# Chat API - Node


## Technology 
 
* Node.js
* Typescrypt
* TypeORM
 
 
## Services Used
 
* Github
 
 
## Pages Used
 
* "/pages/client" - Client access
* "/pages/admin" - Admin access
 

## API Methods
 
GET - "/settings/:username" - Get settings of specific user<br>
GET - "/messages/:id" - Get messages of specific user<br>

POST - "/settings" - Create new setting<br>
settings = {<br>
&emsp;username: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;},<br>
&emsp;chat: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;}<br>
}

POST - "/users" - Create new user<br>
customer = {<br>
&emsp;email: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;}<br>
}

POST - "/messages" - Create new message<br>
customer = {<br>
&emsp;admin_id: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: false<br>
&emsp;},<br>
&emsp;text: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;},<br>
&emsp;user_id: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;}<br>
}

PUT - "/settings/:username" - Alter settings of specific user<br>
settings = {<br>
&emsp;username: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;},<br>
&emsp;chat: {<br>
&emsp;&emsp;type: String,<br>
&emsp;&emsp;require: true<br>
&emsp;}<br>
}

 
## Authors
 
* **Sivori Junior**: [![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/sivorijr)](https://github.com/sivorijr)
 
 
Please follow github and join us!
Thanks to visiting me and good coding!
