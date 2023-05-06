# Blog ♥️ 

This is a simple blog using Node.js and Express.js with MongoDB Atlas as backend to persist the blog articles.

The initial skeleton of this app was created from Github Codespace's express web app template.

To setup this project, first create a hidden file `.env` on project root and update your mongo credentials.

MONGODB_URI = mongodb+srv://<user-name>:<password>@<cluster-given-name>.mongodb.net/blog?retryWrites=true&w=majority

Before starting up the app, ensure you create your Mongo database on Atlas as follows:
database name: blog
collections: posts

To run this application on Codespace:

```
npm start
```

To run this application locally:

```
nodemon index.js
```
