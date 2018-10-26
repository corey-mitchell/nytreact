# nytreact

## Description

A React.js app that allows users to search for New York Times articles. After performing a search, the user will see article results including the name of the article, the date and time of publishing, and a button linking to the article source. Finally, users are able to add and remove articles from a saved articles section. 

## Demo

Check out the deployed demo [here.](https://nyt-articles-react.herokuapp.com/)

# Getting Started

## Installation

To install the application, please run the following commands into your Bash terminal:

```
git clone To install the application, please run the following commands into your Bash terminal:

cd nytreact

yarn install
```

## Running Locally

### Dependencies

You will need to yarn install the following node modules:

1. express
2. mongoose
3. body-parser
4. bluebird
5. axios
6. react
7. react-dom
8. react-router-dom
9. react-scripts

Since I have included two package.json files, you do not need to install dependencies by name. Simply run the following in the root of your directory *as well as* in the Client folder:

```
yarn install
```

## Setting Up Local Database

#### Prerequisite

You will need to have MongoDB set up and a database to store the information.

#### Running Locally
Once it is, you will need to navigate to the server.js file in the global application folder.

![folderstructer](https://user-images.githubusercontent.com/37916145/47556852-f632f080-d8d4-11e8-817f-639d9c7d0a38.PNG)

Inside of the server.js file, locate line 48. Should look like so,

![mongooseconnectionline](https://user-images.githubusercontent.com/37916145/47556972-38f4c880-d8d5-11e8-8730-99a186b16415.PNG)

The name of the database we are using in the above photo is 'nyt-search'. Change this line to fit your database name, e.g.

```
const MONGODB_URI = process.env.MONGODB_URI || "mongodb://localhost/<yourDBnamehere>";
```

## Screenshots

**Article search and results**

![screenshot-1](https://i.imgur.com/eiN3oU2.png)

## Author

* **Corey Mitchell** - (https://github.com/corey-mitchell)