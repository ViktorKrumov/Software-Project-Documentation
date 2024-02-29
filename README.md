# 🎵Music Library
  
## 📝Overview

**Music Library** is an innovative front-end application (**SPA**) designed for **creating** and **managing** music albums. This dynamic platform offers **visitors** an immersive experience to **explore** a vast catalog of albums. Upon registration, **users** gain access to personalized features, enabling them to **craft** their **own album cards**. Furthermore, **album authors** enjoy full control over their **publications**, with the ability to **edit** or **delete** entries at their convenience.

### Mission Statement:

At **Music Library**, our mission is to provide a platform where music lovers can connect, discover, and share their passion for music. We strive to foster a vibrant community where creativity thrives and users can explore the vast and diverse world of music albums.

Join us on our journey to redefine the way people experience music. Whether you're a casual listener or a die-hard music enthusiast, there's something for everyone at **Music Library**.

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



## Pages

This section provides an overview of the various pages in the application and the corresponding permissions required.

### Home <a name = "home"></a>

The Home Page is accessible to all users without any specific permissions.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/2708d4cf-8d3d-4dd5-9503-3add8b96d488" alt="image" width="800">


### Dashboard <a name = "dashboard"></a>

The Dashboard provides an overview of user-related information.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/a086c397-c9b7-4838-b751-ef1aee70a5c9" alt="image" width="800">


### Details <a name = "details"></a>

The Details page displays additional information about the application.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/b8cf5458-dd88-4947-b53e-ea6be45accbf" alt="image" width="800">


### Login <a name = "login"></a>

The Login page allows users to authenticate and access their accounts.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/a9022434-0af8-4ff2-bdea-52986484cb3e" alt="image" width="800">


### Register <a name = "register"></a>

The Register page allows users to create new accounts.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/0bf211f2-0537-4bf4-b945-a5fc19dd4eff" alt="image" width="800">


### Add Album <a name = "add-album"></a>

The Add Album page allows authenticated users to add a new album, providing details such as Singer/Band, Album Name, Image URL, Release Date, Label, and Sales.

<img src="https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/30cd1a56-3683-44d4-9816-2221a3e6033e" alt="image" width="800">







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

## How to Access the API

### To access the API documentation, open the following link in your browser:

```shell
http://localhost:3300/api-docs
```

### The following API endpoints are available for interacting with the application

## API Endpoints

- `GET /api/albums?order=release_date&dir=desc`:
  - Retrieves a list of albums, sorted by release date in descending order.
  
- `GET /api/albums/{albumId}`:
  - Fetches details for a specific album using its unique identifier.
  
- `POST /api/albums`:
  - Adds a new album to the collection. Requires a JSON payload with album details. Example payload:
    ```json
    {
      "artist": "John Doe",
      "title": "New Horizons",
      "coverUrl": "https://example.com/new_horizons_cover.jpg",
      "releaseDate": "June 1, 2024",
      "recordLabel": "Indie Sounds",
      "sales": "500,000 copies"
    }
    ```

- `PUT /api/albums/{albumId}`:
  - Updates details of an existing album. Send a complete JSON payload with all album details, including any changes. Example payload mirrors the POST endpoint.
  
- `DELETE /api/albums/{albumId}`:
  - Removes an album from the collection using its unique identifier.
  
- `POST /api/users/authenticate`:
  - Authenticates a user and returns a session token. Requires a JSON payload with user credentials. Example payload:
    ```json
    {
      "username": "user123",
      "password": "securepassword"
    }
    ```


![image](https://github.com/ViktorKrumov/Software-Project-Documentation/assets/80381396/181296b3-c68f-481e-a874-3cee475ee668)





