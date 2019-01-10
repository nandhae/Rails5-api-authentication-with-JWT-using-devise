# README

A Rails 5 API app to demonstrate setup of authentication with JWT using devise.

Setting up complete authentication flow for a service can be really painful. By using devise and devise-jwt libraries we can set up entire authentication flow with rails in minutes.

You can find my <a href="https://medium.com/@nandhaez/2019-how-i-set-up-authentication-with-jwt-in-just-a-few-lines-of-code-with-rails-5-api-devise-9db7d3cee2c0">detailed blog</a> with step by step instructions on the setup.

# Repo Setup Instructions 

Setup the databases
```sh
$ rake db:create
$ rake db:migrate
$ rake db:seed
```
You can also run the following instead of the above 3 commands
```sh
$ rake db:setup
```
To drop the database, run
```sh
$ rake db:drop
```

Run the API server
```sh
$ rails s
```
