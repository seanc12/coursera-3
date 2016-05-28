Coursera - Ruby on Rails Web Services and Integration with MongoDB

Course 3 of Ruby on Rails Specialization from John Hopkins Universiy

About the Course
In this course, we will explore MongoDB, a very popular NoSQL database and Web Services concepts and integrate them both with Ruby on Rails. 
MongoDB is a used to handle documents with a pre-defined schema which will give the developers an ability to store, process and use data 
using it’s rich API. The modules will go in-depth from installation to CRUD operations, aggregation, indexing, GridFS and various other 
topics where we continuously integrate MongoDB with RailsRuby.  We will be covering the interface to MongoDB using the Mongo Ruby API and 
the Mongoid ORM framework (the MongoDB access counterpart to RDBMS/ActiveRecord within Rails).  The last portion of the course will focus on 
Web Services with emphasis on REST, its architectural style and integration of Web Services with Rails.  Core concepts of Web Services like 
request/response, filters, data representation (XML/JSON), web linking and best practices will covered in depth.

This course is ideal for students and professionals who have some programming experience and a working knowledge of databases.

http://railsapps.github.io/installrubyonrails-ubuntu.html

Version:
Ruby 2.3.0
Rails 4.2.6

https://community.c9.io/t/setting-up-mongodb/1717

mkdir data
echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
chmod a+x mongod

You can start mongodb by running the mongod script on your project root:
./mongod

To access a shell prompt for the above MongoDB run the following.
mongo

gem install rspec
gem install rspec-its
gem install mongo -v 2.1.2