# Somesplash

## Before getting started

1. Create a brand new rails app inside this directory:

```bash
$ rails new . --database postgresql --skip-test
```

2. Add rubocop gems:

```ruby
# Gemfile

group :development do
  ...
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  ...
end
```

3. Resolve the rubocop offensses with `rubocop -A`
4. Commit and push your changes for your team.

## General Instructions

Somesplash will be an open source platforms to share amazing photos with the
world. Your job is to build the first MVP of the product. The current team is
very small, there is no design department and the product owner is at the same
time the general manager, operation manager, talent manager and so on. The GM
has send you the design of the main views for the project with few details. You
will need to infer a lot of details based on the design. Find the design
**[here](https://www.figma.com/file/UqSMl0f43mV6yqguK6IrVR/Somesplash?node-id=888%3A708)**

![https://p-vvf5mjm.t4.n0.cdn.getcloudapp.com/items/7KuE2YBy/67f77363-9c11-4da3-bb3c-b120b78db4ef.png?v=a9b94c013a59b9c7c47f15d165ef817d](https://p-vvf5mjm.t4.n0.cdn.getcloudapp.com/items/7KuE2YBy/67f77363-9c11-4da3-bb3c-b120b78db4ef.png?v=a9b94c013a59b9c7c47f15d165ef817d)

### Task 1: Build a ERD

Based on the design, create a Entity Relationship Diagram with the tables,
fields, data types (Rails data types) and relationships. Include a file with
your ERD on your solution (JPG, PNG, PDF)

### Task 2: Build the project MVP

Using Rails and the MVC pattern, build all the models, controllers and views
necessary to have a functional product.

### Task 3: Fill the data

The objective is to add all the data necessary to resemble the design. You can
do it manually but using the `seed.rb` file could be a better idea.
