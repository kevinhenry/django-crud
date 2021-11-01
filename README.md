# Project Lab 28: Django CRUD

Deployed on: [Link](https://github.com/kevinhenry/django-crud)

PR: [Link](https://github.com/kevinhenry/django-crud/pulls)

Collaboration:
  Tony Regalado, Anthony Williams


## Overview

Add full CRUD functionality to your bag of tricks by building a Django project that allows Creating, Reading, Updating and Deleting.


## Feature Tasks and Requirements

[x] Create snacks_crud_project Django project
[x] Create snacks app
[x] Create Snack model
    [x] title field
    [x] purchaser field
    [x] description field
    [x] Register model with admin
[x] Create SnackListView that extends appropriate generic view
associated url path is an empty string
[x] Create SnackDetailView that extends appropriate generic view
associated url path is <int:pk>/
[x] Create SnackCreateView that extends appropriate generic view
associated url path is create/
[x] Create SnackUpdateView that extends appropriate generic view
associated url path is <int:pk>/update/
[x] Create SnackDeleteView that extends appropriate generic view
associated url path is <int:pk>/delete/
    [x] Add urls to support all views, with appropriate names
    [x] Add templates to support all views
    [x] Add navigation links in appropriate locations to access all pages
    [x] Make all necessary changes to project level files for project to run
        [x] In other words, make it work


## Implementation Notes

A lot of functionality is being added here. But it should still follow the “Django way.” So when in doubt refer back to demo.


### User Acceptance Tests:

[x] Test all Views
[x] Test Model
    [x] string representation
    [x] all fields
[x] When in doubt on what to test refer to demo


## Configuration

Use poetry to create django-crud project.

> $ mkdir django-crud
> $ cd django-crud
> $ poetry init -n
> $ poetry add [required libraries]
> $ poetry shell

Use django-crud folder as the root of your project’s git repository.

## Stretch

[ ] add multiple models
[ ] use an alternate test runner
[ ] add more advanced fields to models, e.g. created time stamp
[ ] add styling


### Getting Started

Clone this repository to your local machine.

$ git clone [Link](https://github.com/kevinhenry/django-crud.git)
Once downloaded, activate your virtual environment and run by ____________

`poetry init`
`poetry shell`
`pmp runserver`
`open 127.0.0.1:8000/admin`
