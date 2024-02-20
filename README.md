# Secrets Application
The Secrets Application is a web application developed using Node.js, Express.js, EJS, and PostgreSQL. It provides users with a platform to securely register and log in to access exclusive content.

![db1](https://github.com/Saurabhkumar21/Authentication-lv.1/assets/109983569/024ecdf7-b499-4931-a39a-312d5e5d93a5)


## Features:
* User Registration: Allows users to sign up for an account by providing their credentials, which are securely stored in a PostgreSQL database.
  
![db2](https://github.com/Saurabhkumar21/Authentication-lv.1/assets/109983569/6194ccd9-d118-4ff2-bde8-5a6e2f8e9b88)

* User Authentication: Validates user credentials during login by checking against the stored data in the database.

 ![db3](https://github.com/Saurabhkumar21/Authentication-lv.1/assets/109983569/1798058a-438b-4159-9f6a-e1ccadd41e36)

* Access Control: Grants access to the homepage upon successful authentication; otherwise, prompts the user with an error message indicating incorrect credentials.

 <img src="https://github.com/Saurabhkumar21/Authentication-lv.1/assets/109983569/29682a6a-1502-46b7-8475-94a36238d3f6"  width="48%" height="50%">


 <img src="https://github.com/Saurabhkumar21/Authentication-lv.1/assets/109983569/3a43241e-868c-4cad-b4fe-f2dffdfacea8" width="48%" height="50%">

  
## Technologies Used:
* Node.js: A JavaScript runtime for building server-side applications.
* Express.js: A minimalist web framework for Node.js, facilitating the development of web applications and APIs.
* EJS (Embedded JavaScript): A templating language that generates HTML markup with plain JavaScript.
* PostgreSQL: A powerful, open-source relational database system used for data storage and retrieval.
  
## Usage:
* Clone the repository to your local machine.
* Install dependencies using npm install.
* Set up your PostgreSQL database and update the connection details in the application.
* Run the application using npm start.
* Access the application through your web browser.

## How it Works:
* User Registration: Upon registration, user credentials are securely saved in the PostgreSQL database.
* User Authentication: During login, the application verifies user credentials against the stored data. If the credentials are correct, the user gains access to the homepage; otherwise, an error message is displayed.
* Access Control: Incorrect login attempts redirect the user to the homepage to re-enter correct credentials. Unregistered users are also directed to the homepage, where they can sign up for an account.
  
## Contributing:
* Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
