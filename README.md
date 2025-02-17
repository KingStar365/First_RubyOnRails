# README

This README would normally document whatever steps are necessary to get the application up and running.

Rails is a web application development framework written in the Ruby programming language.
It is designed to make programming web applications easier by making assumptions about what every developer needs to get started.
It allows you to write less code while accomplishing more than many other languages and frameworks.

Things you may want to cover:

* For this Project, you will need:
  1. Ruby 3.2 or newer
  2. Rails 8.0.0 or newer
  3. A code editor:VScode
* System dependencies

* Configuration
  start: bin/rails server
* Database creation
  1. bin/rails generate model Product name:string
  2. Createing Records: Product.new(name: "")
  3. Querying Records: Product.all
  4. Filtering & Ordering Records: Product.where(name: "")
  5. Finding Records: Product.find()
  6. Updating Records: product.update(name: "")
  7. Deleting Records: product.destory
* Database initialization
  bin/rails db:migrate
* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
