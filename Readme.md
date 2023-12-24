# CRUD App with MongoDB, React, Node, and Express

A simple CRUD (Create, Read, Update, Delete) application built with MongoDB, React, Node, and Express.



## Introduction

This CRUD application allows users to perform basic operations like creating, reading, updating, and deleting user records. It serves as a simple example of a full-stack application using MongoDB, React, Node, and Express.

## Features

- **Create:** Add new users with their name and email.
- **Read:** View a list of all users.
- **Update:** Modify the name and email of existing users.
- **Delete:** Remove users from the database.

## Technologies Used

- **Frontend:**
  - React

- **Backend:**
  - Node.js
  - Express

- **Database:**
  - MongoDB

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- Node.js
- npm
- MongoDB

### Installation

1. Clone the repository:


```bash`
git clone https://github.com/rajugupta0/MernBasicCrud.git ``````



 ## API Endpoints

### Get All Users

- **Endpoint:** `GET /api/v1/getallusers`
- **Description:** Get a list of all users.

### Create User

- **Endpoint:** `POST /api/v1/createuser`
- **Description:** Create a new user.

### Edit User

- **Endpoint:** `PUT /api/v1/edituser/:id`
- **Description:** Update an existing user.
- **Parameters:**
  - `id` (Path Parameter): User ID to be updated.

### Delete User

- **Endpoint:** `DELETE /api/v1/deleteuser/:id`
- **Description:** Delete a user.
- **Parameters:**
  - `id` (Path Parameter): User ID to be deleted.
