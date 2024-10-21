# Django Task Management API

## Overview
This project is a task management system built using Django and Django Rest Framework. It provides a set of APIs to create tasks, assign them to users, and fetch tasks assigned to specific users. The system allows for managing tasks with multiple users and supports task statuses and types.

## Features
- **Create a Task**: Create new tasks with a name, description, and task type.
- **Assign a Task**: Assign tasks to one or multiple users.
- **Get User Tasks**: Fetch all tasks assigned to a particular user.

## Technologies Used
- **Django**: Backend framework
- **Django Rest Framework (DRF)**: For building RESTful APIs
- **SQLite**: Default database (can be replaced with other databases)
- **Python 3.8+**

## Setup Instructions

### Prerequisites
Make sure you have the following installed on your system:
- Python 3.8+
- pip (Python package installer)
- virtualenv (optional, but recommended)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/django-task-management.git
   cd django-task-management
