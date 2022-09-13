<a name="readme-top"></a>

<h3 align="center">MERN: Google Book Search Engine </h3>

<div align="center">

[![MongoDB](https://img.shields.io/badge/MongoDB-green.svg)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/expressjs-orange.svg)](https://expressjs.com/)
[![Mongoose.js](https://img.shields.io/badge/mongoosejs-red.svg)](https://mongoosejs.com/)

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Repo Size](https://img.shields.io/github/repo-size/xndroli/Note-Taker.svg)](https://github.com/xndroli/Note-Taker/issues)
[![GitHub Issues](https://img.shields.io/github/issues/xndroli/Note-Taker.svg)](https://github.com/xndroli/Note-Taker/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/xndroli/Note-Taker.svg)](https://github.com/xndroli/Note-Taker/pulls)

</div>

---

## 🔗 Description <a name = "description"></a>

I will create an application called Note Taker that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.

The application’s front end has already been created. Therefore, I will build the back end, connect the two, and then deploy the entire application to Heroku.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 Table of Contents

- [Description](#description)
- [User Story](#user_story)
- [Acceptance Criteria](#acceptance_criteria)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technology](#built_with)
- [Authors](#authors)
- [Contributing](../CONTRIBUTING.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💡 User Story <a name = "user_story"></a>

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⛓️ Acceptance Criteria <a name = "acceptance_criteria"></a>

```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎞️ Demo <a name = "demo"></a>

As you can see in the following animation, a user can type a search term (in this case, "star wars") in a search box and the results appear:

[![MERN: Google Book Search Engine Demo](./assets/images/googlebooks-app-demo-01.gif)](https://github.com/xndroli/Note-Taker/)

The user can save books by clicking "Save This Book!" under each search result, as shown in the following animation:

[![MERN: Google Book Search Engine Demo](./assets/images/googlebooks-app-demo-02.gif)](https://github.com/xndroli/Note-Taker/)

A user can view their saved books on a separate page, as shown in the following animation:

[![MERN: Google Book Search Engine Demo](./assets/images/googlebooks-app-demo-03.gif)](https://github.com/xndroli/Note-Taker/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🏁 Getting Started <a name = "getting_started"></a>

Clone the repo by running:

`git clone https://github.com/xndroli/Note-Taker.git`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### 💾 Installation <a name = "installation"></a>

Input basic project information in include in your package by running:

`npm init`

Install the package, and any packages that it depends on by running:

`npm install`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Usage <a name="usage"></a>

Run the following command at the root of your project:

`npm start`

If you have nodemon:

`npm run watch`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⛏️ Built With <a name = "built_with"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express.js](https://expressjs.com/) - Server Framework
- [Mongoose.js](https://mongoosejs.com/) - Object Data Modeling
- [Node.js](https://nodejs.org/en/) - Server Environment

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ✍️ Authors <a name = "authors"></a>

- [@xndroli](https://github.com/xndroli)

See also the list of [contributors](https://github.com/xndroli/Note-Taker/contributors) who participated in this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

© 2022 xndroli. All Rights Reserved.
