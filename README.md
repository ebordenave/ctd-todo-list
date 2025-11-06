# To-Do List App

A simple and flexible task management application designed to help users stay organized and productive.

## Features

- Create and manage a custom list of tasks
- Set **times**, and **locations** for tasks (when applicable)
- Assign tasks to different **categories**
- Assign tasks to different users
- Configure **recurring tasks**
- Set optional due dates for Tasks

## Stretch Goals

- Google Calendar integration
- Cross-platform sync
- API development
- Mobile support (_future consideration_)


## Installation Instructions

### 1. Clone the repository

#### **SSH**

```bash
git clone git@github.com:ebordenave/ctd-todo-list.git
```
#### **HTTPS**

```bash
git clone https://github.com/ebordenave/ctd-todo-list.git
```

### 2. Install Dependencies

```bash
npm create vite@latest . -- --template react
```

### 3. Run Development Server

```bash
npm run dev
```
By default, this ToDo App will run at:
```http://localhost:5173```