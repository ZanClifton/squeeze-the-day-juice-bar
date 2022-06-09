# Squeeze The Day Juice Bar - The Server

This was my first ever tech test. I didn't progress because I made some not-insignificant mistakes, but I have decided to work on the repo and develop it in a different direction to help me learn some new things!

This is still a work in progress and errors in testing have not yet been corrected.

#
## Run Locally

### ✔️ 1. CLONE THE REPO
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

Terminal Commands:
```
$ git clone https://github.com/ZanClifton/juice-bar.git
$ cd juice-bar
$ code .
```

### ✔️ 2. INSTALL DEPENDENCIES
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
```
$ npm install
```

### ✔️ 3. RUN TESTS
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white) 

```
$ npm test
```

### ✔️ 4. USAGE
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

Start the server listening with:
```
$ npm start
```
You can use a regular browser to make requests, or install a free framework for testing RESTful applications such as [Insomnia](https://insomnia.rest/download)

#
## Description

### 1 - GET `/api/recipes`

A GET endpoint that responds with a list of all recipes.

Includes a query (`?exclude_ingredients=apples,bananas,carrots`) to exclude recipes that contain specific ingredients. (WIP)

### 2 - GET `/api/recipes/:id`

A GET endpoint that responds with a single recipe.

### 3 - POST `/api/recipes`

A POST endpoint that adds a recipe to the data. This should respond with the generated recipe ID. The newly created recipe should be retrievable. (WIP)

This project was created using:
```
$ node -v | v17.7.1
```

The above command will also enable you to check your own version in the terminal. It is recommended you update to the most recent version prior to working with this app.
