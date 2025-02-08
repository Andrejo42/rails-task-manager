# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


1 - Model
Generate the Task model through the right rails generator. It should have at least the following columns:

title, as a string
details, as a text
completed, as a boolean (default: false)

rails generate model Task title:string details:text completed:boolean
