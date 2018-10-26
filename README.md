# nytreact

## Description
A recreation of the NYT Articles Search

## Demo

Check out the deployed demo [here.](https://nyt-articles-react.herokuapp.com/)

# Getting Started

## Installation

To install the application, please run the following commands into your Bash terminal:

```
git clone To install the application, please run the following commands into your Bash terminal:

cd nytreact

npm install
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

## Author

* **Corey Mitchell** - (https://github.com/corey-mitchell)