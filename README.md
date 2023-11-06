# About The Project

## Introduction

**Project Summary**:

This project is a full-stack web development 
**Key Highlights**:

1. **Front-End Proficiency**: 

2. **Back-End Data Management**: 
3. **Rich Functionality**: 


<p align="right">(<a href="#readme-top">back to top</a>)</p>


**Major frameworks and libraries**:

* [![JavaScript][JavaScript-icon]][JavaScript-url]
* [![React][React-icon]][React-url]
* [![HTML][HTML-icon]][HTML-url]
* [![CSS][CSS-icon]][CSS-url]
* [![Postman][Postman-icon]][Postman-url]
* [![NodeJS][NodeJS-icon]][NodeJS-ul]
* [![MongoDB][MongoDB-icon]][MongoDB-ul]

[React-url]:https://reactjs.org/
[React-icon]:https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB
[HTML-url]:https://html.com/
[HTML-icon]:https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white
[CSS-url]:https://www.css3.com/
[CSS-icon]:https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white
[JavaScript-url]:https://www.javascript.com/
[JavaScript-icon]:https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E
[NodeJS-icon]:https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white
[NodeJS-ul]:https://nodejs.org/en
[MongoDB-icon]:https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-ul]:https://www.mongodb.com/atlas/database
[Postman-url]:https://www.postman.com/
[Postman-icon]:https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

These steps will help you clone the repository, set up the back end, and configure the front end, allowing you to start development or run the project. To set up and run this project, follow these steps:

1. Clone the repository. This command clones the project repository to your local machine.
   ```sh
   gh repo clone vickyzhang7/Trip-share-website
   ```
   
### Backend Setup

2. Open the `app.js` and `location.js` files and input your API key. Replace 'YOUR KEY' with your actual API key.
   ```js
   const API_KEY = 'YOUR KEY';
   ```

3. Install Mongoose version 6.  This command installs the required Mongoose version.
   ```sh
   npm install mongoose@6
   ```

4. Start the backend server. This command starts the backend server for the application.
   ```sh
   npm start
   ```

### Frontend Setup

5. Install NVM (Node Version Manager). This command installs NVM, a tool for managing Node.js versions.
   ```sh
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
   ```
6. Activate NVM. This command activates NVM for use.
   ```sh
   source ~/.nvm/nvm.sh
   ```

7. Install Node.js version 14. This command installs Node.js version 14, which is required for the project.
   ```sh
   nvm install 14
   ```

8. Check Node.js version. Verify that Node.js 14 is successfully installed.
   ```sh
   node -v
   ```

9. Install frontend project dependencies. This command installs the necessary frontend project dependencies.
   ```sh
   npm install
   ```

10. Start the frontend. This command starts at the frontend of the web application.
    ```sh
    npm start
    ```



<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Interface Screenshots

1. **Initial Interface (No Users)**:
   - Upon the initial launch of the application, users will encounter a screen displaying "No users" since no user information is pre-stored. Authentication is required for further access.

     <img width="1208" alt="Screenshot 2023-11-05 at 6 25 53 PM" src="https://github.com/vickyzhang7/Trip-share-website/assets/130918669/385d9455-2f11-41a1-89d5-cead7d4f0701">


2. **Sign Up**:
   - Users can create an account by providing their name, email, password, and a profile picture. If a username or email is already in use, the system will prompt that the user already exists.

     <img width="1208" alt="Screenshot 2023-11-05 at 6 33 29 PM" src="https://github.com/vickyzhang7/Trip-share-website/assets/130918669/4d5e9e28-03fe-4b8e-ad3d-55d291378d5e">


3. **Log In**:
   - Registered users can log in to the application to share their travel experiences.

     <img width="1208" alt="Screenshot 2023-11-05 at 6 36 15 PM" src="https://github.com/vickyzhang7/Trip-share-website/assets/130918669/0a86ccfa-e0cc-44b5-ae51-a3e49303ce98">


4. **Manage Travel Records**:
   - Users can edit, delete, and view the specific locations of their travel records on Google Maps.

     <img width="1228" alt="Screenshot 2023-11-05 at 7 41 11 PM" src="https://github.com/vickyzhang7/Trip-share-website/assets/130918669/7ae4f06d-f504-4a90-8f2c-d9c2fb026eef">


5. **Browse All User Travels**:
   - Users can explore and view the travel records of other users. However, they do not have the permission to modify others' travel records. Users can view the detailed addresses of locations shared by other users on Google Maps.
     <img width="1239" alt="Screenshot 2023-11-05 at 7 50 28 PM" src="https://github.com/vickyzhang7/Trip-share-website/assets/130918669/42781e21-9ec6-4476-9e9c-c4fd06395a9e">



6. **Final Dashboard (User Summary)**:

   - The final screenshot provides a summary of all users' information and activities, offering insights into the top contributors and their travel experiences.

     <img width="1228" alt="Screenshot 2023-11-05 at 7 50 08 PM" src="https://github.com/vickyzhang7/Trip-share-website/assets/130918669/49bd808a-ef55-4811-9f9d-320fd997b0c2">




## interface screenshot

 1. **Database Browsing**:

Users can access a variety of news and information stored in the database. This allows users to explore the contents of the database, including news, articles, and other related information.

  <img width="1414" alt="Screen Shot 2023-11-01 at 7 14 07 PM" src="https://github.com/vickyzhang7/Real-or-Fake-Facts/assets/130918669/039961b2-cf7e-4d96-bb49-d0d59523b6f7">
  <br>

  2. **News Posting and Storage**:
   
Users can post news they've come across, adding links and categories to the news. This information is securely stored in the database for future reference and sharing. This provides users with a convenient platform to share their discoveries and interests with other users.

  <img width="1385" alt="Screen Shot 2023-11-01 at 7 16 06 PM" src="https://github.com/vickyzhang7/Real-or-Fake-Facts/assets/130918669/178e626b-ce8c-45b7-94ed-b81e71cd9bdb">
  <br>   

  3. **Real-time Voting and Sorting**: 

Users can vote on news articles, including rating them for their level of interest, how mind-blowing they are, and their credibility. All voting data is recorded and used to re-sort the news list. News articles are ranked based on the number of "interesting" votes, ensuring that users see the most intriguing news first. This provides an interactive and dynamic news browsing experience.

  <img width="1406" alt="Screen Shot 2023-11-01 at 7 17 03 PM" src="https://github.com/vickyzhang7/Real-or-Fake-Facts/assets/130918669/74450d76-7c07-4249-bd60-eaf06ffe7cb7">
  <br>   

<p align="right">(<a href="#readme-top">back to top</a>)</p>




