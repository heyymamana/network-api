 social network API built using Express.js and MongoDB, which can handle large amounts of unstructured data. It offers a variety of features such as sharing thoughts, reacting to friend’s thoughts, and creating a friend list. It’s a great solution for social media startups as it offers flexibility in terms of data structure and handles large amounts of data effectively. It also offers API GET, POST, PUT, and DELETE routes to enable users to interact with the database, and the Mongoose ODM is used for database modeling. ThoughtsUp is perfect for developers looking to build social network APIs and require scalability and flexibility in their data structure.

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Installation

To install and run on your local machine, follow these steps:

**Clone this repository to your local machine**

`git clone <'REPOURL'>`

**Install the necessary dependencies**

`npm init -y`

`npm i express`

`npm i mongoose`

**Seed The Database**

`npm run seed`

**Run the Application**

`node server`

