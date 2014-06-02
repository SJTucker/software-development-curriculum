#ActiveRecord

##Overview
Active Record is an Object-Relation-Mapping(ORM) tool that links the data in your database to the logic in your models, making it the M in MVC.  It communicates with the database to pull out the data so you don't have to write your own raw SQL queries. 

##Models
Active Record generates migration files so that changes in your model correspond to changes in the database.  All of your models will inherit behavior from the ActiveRecord::Base class, but you add your own functionality in your model file to instruct it how to interact with data retrieved from the database.

##Validations
Active Record is also responsible for ensuring the integrity of information entering the database.  You write validations in the model that police what criteria allow for an acceptable record that can be inserted into the database.  For instance, you can write validations that test for uniqueness of a username so that no two users will have the same name before it is saved to the database.

##Scopes
[Reading] -> http://guides.rubyonrails.org/active_record_querying.html#scopes
Scopes are class methods that are named and defined in one line using ActiveRecord syntax.

##Indexes
A database index is a data structure that improves the speed of operations on a database table.  We can code relationships between tables in the database so that they are automatically associated with one another.
[Reading] -> https://tomafro.net/2009/08/using-indexes-in-rails-index-your-associations

##Further Reading
http://guides.rubyonrails.org/active_record_querying.html

