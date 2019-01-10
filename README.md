# README

A Rails 5 API app to demonstrate setup of authentication with JWT using devise.

Setting up complete authentication flow for a service can be really painful. By using devise and devise-jwt libraries we can set up entire authentication flow with rails in minutes.

# ToDo -- Write detailed instructions 

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
