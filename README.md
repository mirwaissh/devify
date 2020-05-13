# Devify 2.0

> Social network for developers

This is a MERN stack application. It is a small social network app that includes authentication, profiles and forum posts.



# Quick Start 🚀

### Add a default.json file in config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```



### Deploy to Heroku


Create your Heroku project

```bash
heroku create
```

And push the local production branch to the remote heroku master branch.

```bash
git push heroku master
```

Now Heroku will have the config it needs to build the project.

> **Don't forget to make sure your production database is not whitelisted in MongoDB Atlas, otherwise the database connection will fail and your app will crash.**


---

## App Info

### Author

Mirwais Shahryar
[mirwaisjs](http://www.mirwaisjs.com)

### Version

2.0.0

### License

This project is licensed under the MIT License
