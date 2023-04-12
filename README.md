# README

### What is MVC (Model, View, Controller)?
 It is a software architecture pattern that separates the representation of information from user interaction.

### CRUD 
CRUD is an acronym for the four verbs we use to operate on data
* Create
* Read
* Update
* Delete

### Scaffold (CRUD generator)
Example :
```cmd 
rails generate scaffold <Model> <data:type> <data:type>..
rails generate scaffold Coin description:string acronym:string url_image:string
```
This command will create : views, controller, model and migration

### Active Record and ORM - [Active Record Basics](https://guides.rubyonrails.org/active_record_basics.html)

### Migrations - [Active Record Migrations](https://guides.rubyonrails.org/active_record_migrations.html)

### Rails dbconsole
```cmd 
rails dbconsole
```

### Rails Tasks
```cmd 
rails -T
rails db:create
rails db:drop
rails db:migrate
rails db:rollback
```