Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.
# Mini Blog Platform

A simple and elegant blog application built with **Ruby on Rails 8**, **Devise authentication**, and **Bootstrap 5**. Users can sign up, log in, and create/edit/delete their own posts.

---

## Features

- User authentication (Sign up, Login, Logout) via Devise
- Create, Read, Update, Delete (CRUD) for blog posts
- Posts are associated with the logged-in user
- Flash alerts and messages
- Styled with Bootstrap 5
- Protected routes (only logged-in users can create/edit posts)

---

## Tech Stack

- **Ruby on Rails** 8.0.2
- **Ruby** 3.2.2 / 3.2.8
- **PostgreSQL** as the database
- **Devise** for user authentication
- **Bootstrap 5** for styling
- **Gitpod** or local development

---

## Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/mini-blog.git
cd mini-blog
2. Install Dependencies

bundle install
yarn install # if using webpacker
3. Database Setup

rails db:create
rails db:migrate
4. Start the Server

rails server


Folder Structure
app/
├── controllers/
│   └── posts_controller.rb
├── models/
│   ├── user.rb
│   └── post.rb
├── views/
│   ├── posts/
│   └── layouts/
│       └── application.html.erb

Author
B. Tanmai kiran
