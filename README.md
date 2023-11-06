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


# Trip Share Website

This repository contains a web application for sharing trip information.

## Getting Started

To set up and run this project, follow these steps:

1. Clone the repository
   ```sh
   gh repo clone vickyzhang7/Trip-share-website
   ```
   This command clones the project repository to your local machine.

### Backend Setup

2. Open the `app.js` and `location.js` files and input your API key.
   ```js
   const API_KEY = 'YOUR KEY';
   ```
   Replace 'YOUR KEY' with your actual API key.

3. Install Mongoose version 6
   ```sh
   npm install mongoose@6
   ```
   This command installs the required Mongoose version.

4. Start the backend server
   ```sh
   npm start
   ```
   This command starts the backend server for the application.

### Frontend Setup

5. Install NVM (Node Version Manager)
   ```sh
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
   ```
   This command installs NVM, a tool for managing Node.js versions.

6. Activate NVM
   ```sh
   source ~/.nvm/nvm.sh
   ```
   This command activates NVM for use.

7. Install Node.js version 14
   ```sh
   nvm install 14
   ```
   This command installs Node.js version 14, which is required for the project.

8. Check Node.js version
   ```sh
   node -v
   ```
   Verify that Node.js 14 is successfully installed.

9. Install frontend project dependencies
   ```sh
   npm install
   ```
   This command installs the necessary frontend project dependencies.

10. Start the frontend
    ```sh
    npm start
    ```
    This command starts the frontend of the web application.

These steps will help you clone the repository, set up the backend, and configure the frontend, allowing you to start development or run the project. If you have any questions or encounter any issues, feel free to contact us.

Please note that you should replace 'YOUR KEY' in the `app.js` and `location.js` files with your actual API key to enable the application's functionality.




1. Clone the repo
   ```sh
   gh repo clone vickyzhang7/Real-or-Fake-Facts
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your API in `script.js` and `supabase.js`
   ```js
   const res = await fetch("YOUR FACTS", {
    headers: {
      apikey: "YOUR API KEY",
      authorization: "Bearer YOUR API KEY",
    },});
   ```

4. Start
   ```sh
   npm start
   ```
   
<p align="right">(<a href="#readme-top">back to top</a>)</p>

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




