# 🧠 Angular 19 Task Manager with Signals

This is a **Task Manager Application** built with **Angular 19**, showcasing the power of **Angular Signals**, **signal-based inputs**, **block statements**, and **modern component structure**.

## 🚀 Features

- 🔄 **Real-time reactivity** using Angular **Signals**
- ➕ Add new tasks with status: `To Do`, `In Progress`, or `Completed`
- 📊 Task columns displayed in a **grid layout** grouped by status
- 🔁 Move tasks between statuses using dedicated buttons
- ⚡ Signal-based data flow using `@for`, `@if` and component input signals
- 📦 Modular architecture using Angular standalone components and services

## 🧱 Built With

- Angular 19
- Angular Signals & `@for`, `@if` blocks
- TypeScript

## 📋 Functionality Overview

- 📝 **Add Task**  
  Use the task form to enter a title and select a status (`To Do`, `In Progress`, `Completed`).

- 📊 **Display Tasks by Status**  
  Tasks are grouped and displayed in 3 columns using Angular’s signal `computed` filters.

- 🔄 **Move Tasks**  
  Each task has buttons to move it to another status:
  
  | From \ To      | To Do | In Progress | Completed |
  |----------------|-------|-------------|-----------|
  | **To Do**      | —     | ✅          | ✅        |
  | **In Progress**| ✅    | —           | ✅        |
  | **Completed**  | ✅    | ✅          | —         |


## 🛠️ How to Run

```bash
# Clone the repository
git clone https://github.com/ashna0204/Angular_Task_Manager.git
cd Angular_Task_Manager

# Install dependencies
npm install

# Run the dev server
ng serve


