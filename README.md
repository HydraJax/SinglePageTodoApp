# Todo Single Page App

A single page app demo using todos.

To get the app setup, create a `.env` file in the root of the project.  Make a `SECRET_KEY_BASE` environment variable in the .env file.

Next do:

```
rake db:drop && rake db:create && rake db:migrate && rake db:seed
```

```
rails s
```
