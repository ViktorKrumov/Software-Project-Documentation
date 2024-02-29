# 🎵Music Library
  
## 📝Overview

**Music Library** is a front-end app (**SPA**) for **creating** and **managing** music albums. The **application** allows **visitors** to **browse** through the **albums catalog**. **Users** may **register** with an **email** and **password** which allows them to **create** their **own album card**. **Album authors** can also **edit** or **delete** their own **publications** at any time.

<p align="center">
  <img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/e09c2fc3-8ea8-440d-9956-4e15a5596b06" alt="Landing Page" width="500">
</p>


## ✨ Features

- **Browse Albums**: Explore a vast collection of albums with ease.
- **User Registration**: Sign up with your email and password.
- **Create Albums**: Users can create their own album cards.
- **Direct Content Management**: Edit or remove your contributions at your discretion.


## 🛠️ Technologies Used

- **Frontend**:
  - <img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/javascript/javascript.png" alt="JavaScript" width="20"/> JavaScript
  - <img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/html/html.png" alt="HTML5" width="20"/> HTML
  - <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/css-3.svg" alt="CSS3" width="20" style="filter: invert(56%) sepia(97%) saturate(754%) hue-rotate(194deg) brightness(94%) contrast(87%);"/> CSS

- **Backend**:
  - <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/nodejs-icon.svg" alt="Node.js" width="20"/> Node.js
  - <img src="https://expressjs.com/images/express-facebook-share.png" alt="Express.js" width="20"/> Express.js

- **Testing**:
  - <img src="https://avatars.githubusercontent.com/u/8770005?s=200&v=4" alt="Mocha" width="20"/> Mocha
  - <img src="https://www.chaijs.com/img/chai-logo.png" alt="Chai" width="20"/> Chai



## Pages and Permissions

This section provides an overview of the various pages in the application and the corresponding permissions required.

### All Users 🔓

- [Home](#home)
- [Dashboard](#dashboard)
- [Details](#details)
- [Login](#login)
- [Register](#register)

### Authenticated Users 🔒

- [Dashboard](#dashboard-authenticated)
- [Add Album](#add-album)
- [Album Details](#album-details)
- [Edit Album](#edit-album)
- [Delete Album](#delete-album)

### Home {#home}

The Home Page is accessible to all users without any specific permissions.

### Dashboard {#dashboard}

The Dashboard provides an overview of user-related information.

### Details {#details}

The Details page displays additional information about the application.

### Login {#login}

The Login page allows users to authenticate and access their accounts.

### Register {#register}

The Register page allows users to create new accounts.

### Dashboard (Authenticated) {#dashboard-authenticated}

The Dashboard provides an overview of user-related information for authenticated users.

### Add Album {#add-album}

The Add Album page allows authenticated users to add a new album, providing details such as Singer/Band, Album Name, Image URL, Release Date, Label, and Sales.

### Album Details {#album-details}

The Album Details page displays detailed information about a specific album.

### Edit Album {#edit-album}

The Edit Album page allows authenticated users to edit album details, but only if they are the owner of the album.

### Delete Album {#delete-album}

The Delete Album page allows authenticated users to delete albums, but only if they are the owner of the album.





## ⚙️ Installation

### Step 1: Clone the repository

```shell
https://github.com/ViktorKrumov/Software-Project-Documentation.git
```

### Step 2: Install the the required resources

```shell
npm install
```

### Step 3: Run the project

```shell
npm start
```


## Unit Tests
The Music Library is equipped with a suite of unit tests designed to ensure the reliability and stability of the application. These tests cover a range of functionalities, from user authentication to album management.

#### Running Tests

To run the unit tests for the Harmony Hub application, follow these steps:

1. Open the terminal in Visual Studio Code.
2. Type in the following command:

    ```
    npm run test
    ```

3. After a few seconds, different tests will appear in the terminal.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/325a301c-5397-493c-b926-79df09681b57" alt="image" width="600">



