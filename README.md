# Project: Bare Metal Forms and Helpers (Ruby on Rails)

This is the fifth project of the Main Rails curriculum at [Microverse](https://www.microverse.org/) - @microverseinc

- The objective is to build some forms, both using nearly-pure HTML and then graduating to using the helper methods that Rails provides.
- A front end is built with a very limited feature and styling.

#### [Assignment link](https://www.theodinproject.com/courses/ruby-on-rails/lessons/forms)

## Usage Instructions

### Clone the project

- Clone the repo and run the app.

```bash
$ git clone git@github.com:Torres-ssf/re-former.git
$ cd micro-reddit

```

### Run bundle install and migrate as follows:

```bash
bundle install

rails db:migrate
```

## Validations

```

User Model
- `username` can not be blank and can not exceed 50 characters
`email` can not be blank and can not exceed 255 characters, must be unique but not case sensitive
`password` can not be blank and can not be lesser tha 6 characters

```

## Screenshots

### Create user

`http://localhost:3000/users/new`
![Create user](https://res.cloudinary.com/bolaah/image/upload/v1560484514/github-microverse-project/rails_form/form_create_new.png)

### Edit/Update user

`http://localhost:3000/users/1/edit`
![Edit/Update user](https://res.cloudinary.com/bolaah/image/upload/v1560484514/github-microverse-project/rails_form/form_update.png)

### Form Validations

![Form Validations](https://res.cloudinary.com/bolaah/image/upload/v1560484514/github-microverse-project/rails_form/form_valid.png)

### Show current user

`http://localhost:3000/users/1`
![Show current user](https://res.cloudinary.com/bolaah/image/upload/v1560484514/github-microverse-project/rails_form/form_display.png)

### Show all users

`http://localhost:3000/users`
![Show all users](https://res.cloudinary.com/bolaah/image/upload/v1560484514/github-microverse-project/rails_form/form_show_all.png)

## Ruby version

    ruby 2.6.3p62

## Rails version

    Rails 5.2.3

#### Authors

- [@Torres-ssf](https://github.com/Torres-ssf)
- [@bolah2009](https://github.com/bolah2009/)
