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



## Ruby version

    ruby 2.6.3p62

## Rails version

    Rails 5.2.3

#### Authors

- [@Torres-ssf](https://github.com/Torres-ssf)
- [@bolah2009](https://github.com/bolah2009/)
