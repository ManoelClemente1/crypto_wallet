# README

### What is MVC (Model, View, Controller)?
 It is a software architecture pattern that separates the representation of information from user interaction.

### CRUD 
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
