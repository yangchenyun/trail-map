Rails ActiveRecord
=====

Critical learning
-----------------

* Read Chapter 1 of [Pro Active Record Databases with Ruby and Rails](http://www.amazon.com/Pro-Active-Record-Databases-Experts/dp/1590598474)($)
* Read [official guides for migrations](http://guides.rubyonrails.org/migrations.html).
* Read [official guides for validations](http://guides.rubyonrails.org/active_record_validations_callbacks.html).
* Read [official guides for associations](http://guides.rubyonrails.org/association_basics.html).
* Read [official guides for query interfaces](http://guides.rubyonrails.org/active_record_querying.html).
* Read [Agile Web Development with Rails](http://www.amazon.com/Agile-Development-Rails-Pragmatic-Programmers/dp/1934356549/) Chapter 19, 23. ($)
* Read examples of source code, such as [this](https://github.com/copycopter/copycopter-server/tree/master/app/models).
* Watch [Peepcode Advanced ActiveRecord](https://peepcode.com/products/advanced-activerecord)

Validation
----------

You know everyday ActiveRecord when you can:
* Config connection and setup with database adapters.
* Know the conventions used by ActiveRecord mapping to retrieve data from table columns.
* Write migrations to create and alter table structures and indexes
* Use `rake` tasks to manage migrations
* Perform basic CRUD operations with `new`, `find`, `save`, `destroy` through ActiveRecord

You know intermediate ActiveRecord when you can:
* Know the Dynamic method to query data
* Inspect the SQL statements translated and executed by ActiveRecord
* Execute raw SQL statements in migrations and models
* Add SQL clause through `:conditions`, `:order`, `:select`, `:from`, `:limit`, `:offect`, `:group` and `:having` options
* Perform SQL calculations through ActiveRecord

* Modify the scheme and build various associations in ActiveRecord
* Use the build-in methods to CRUD associated objects.

* Know the hooks in a life cycle of ActiveRecord
* Use the build-in validators.
* Write validations with validate helpers in ActiveRecord
* Access validation errors

You know advanced ActiveRecord when you can:
* Load associations with `:join` and `:include`
* Write Table Inheritance
* Use **Polymorphic Associations**
* Use transaction to group queries
* Write locking queries
* Write customized validators
* Use scope to add customized method
* Use callbacks and observers in models

Ongoing reference
-----------------
* Refer to [the API documentation](http://api.rubyonrails.org/classes/ActiveRecord.html).
