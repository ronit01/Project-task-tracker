# Project Task Tracker Application

## Overview

**Description:**
The objective of this project is to develop a Project Task Tracker that facilitates the setup of projects, management of tasks. The app will enable users to create projects, and invite people to collaborate.

## Objectives

**Main Goal:**
To build a comprehensive application that combines project management and task tracking functionalities to enhance team productivity and project oversight.

1. Allow users to set up and define projects, including project details like name, description, and objectives.
2. Enable users to invite collaborators to join projects using email invitations or direct links.
3. Integrate a task manager where users can add, assign, and track tasks, set deadlines, and update statuses.

##Photo
![image](https://github.com/ronit01/Project-task-tracker/assets/91108281/fec340db-5d50-4cad-93c9-eeee21d311d4)
![Screenshot 2024-05-19 153131](https://github.com/ronit01/Project-task-tracker/assets/91108281/b7b47033-885c-4f0c-9ea8-fd3b75640ff3)
![image](https://github.com/ronit01/Project-task-tracker/assets/91108281/b8a4b193-4d85-4bfb-bbb6-2d2f227a213c)
![image](https://github.com/ronit01/Project-task-tracker/assets/91108281/11908a45-078a-4dcc-9b22-c896ecfcb426)



## Tech Stack

- **Frontend:**
  - ReactJS
  - Bootstrap

- **Backend:**
  - Python
  - Flask

- **Database:**
  - MongoDB

## Features

- **Project Setup:**
  - Define project details such as name, description, and objectives.
- **Task Management:**
  - Create, assign, and track tasks.
  - Set deadlines and update task statuses.

## Installation

### Prerequisites

- Node.js and npm
- Python 3.x
- MongoDB

### Frontend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/ronit01/project-task-tracker.git
    cd project-task-tracker/frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the frontend server:
    ```bash
    npm start
    ```

### Backend Setup

1. Navigate to the backend directory:
    ```bash
    cd ../backend
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Start the backend server:
    ```bash
    flask run
    ```

### Database Setup

1. Make sure MongoDB is installed and running on your local machine.

2. Create a database for the project:
    ```bash
    mongo
    use project-task-tracker
    ```


