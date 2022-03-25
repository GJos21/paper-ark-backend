# Paper Ark

(Originally cloned from Flatiron json-server-template, see here for README 
[https://github.com/learn-co-curriculum/json-server-template/blob/main/README.md])

## Setup

Fork and clone this repo. Then install the dependencies by running:

```sh
npm install
```

## Seeding Data

Then, run `npm run seed` to copy data from the `db/seeds.json` file to the
`db/db.json` file. `json-server` uses the `db.json` file to create your RESTful
API, so make sure your `db.json` file is always up to date!

Any time you want to reset your database back to your original data, run
`npm run seed` again. Doing this will overwrite all the data in your `db.json`
file, so make sure you don't have any data in that file that you don't mind
losing!

## Running the Server Locally

To run your server in development mode, run:

```sh
npm run dev
```

## Deploying the Server

Free services like Heroku make it simple to deploy your Node server. Heroku also
works nicely with Rails, which you'll learn later in the program.

First, download the [Heroku CLI](https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up).

Then, [deploy your app](https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app).

Since Heroku deployment integrates with your git repo, you can easily deploy
changes to your database. To deploy changes, make sure to commit your code:

```sh
git add .
git commit -m "Updated database"
```

Then push your main/default branch up to Heroku:

```sh
git push heroku main
```
# paper-ark-backend
