# README

# Check for Understanding
  - Define CRUD:
    - Create: Add new records to the database, or create new tasks for this use case. POST
    - Read: Retrieve existing records. View tasks. GET
    - Update: Modify existing records. Edit a task. PATCH/PUT
    - Delete: Remove records. Delete a task. DELETE
  - Define MVC:
    - MVC stands for model view controller. ActiveRecord is the model, JSON is the view, & controller connects the model & view, processes incoming requests.
  - What two files would you need to create/modify for a  Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.:
    - The two files that need to be created or modified are the routes file and the tasks_controller file. You can also add a serializer to help format the data for the front end.
  - What are params? Where do they come from?:
    - params is a hash like object which contains all of the data from a request. It can be accessed like a hash in ruby so that we can access them easily from the task_controller.
  - What is the purpose of a serializer?
    - Serializers format your model data into a consistent structure. We can control what data gets exposed when making a request. Instead of outputting the full object, we can specify what is returned.


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
