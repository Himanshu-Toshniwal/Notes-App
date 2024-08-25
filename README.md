# Notes App

## Table of Contents
1. [Introduction](#introduction)
2. [Technology](#technology)
3. [Features](#features)
4. [Overview](#overview)
5. [Screenshots](#screenshots)
6. [Usage](#usage)

## Introduction
The Notes App is a user-friendly web application built using HTML, CSS, and JavaScript. It allows users to create, edit, and delete notes, all of which are stored in the browser's local storage for persistence. The application features a clean and intuitive interface, making it easy for users to manage their notes effectively.

## Technology
- **HTML**: Provides the structure of the app.
- **CSS**: Styles the application and ensures a responsive and visually appealing layout.
- **JavaScript**: Manages the functionality of creating, editing, and deleting notes, as well as handling local storage operations.

## Features
- **Create Notes**: Add new notes with a click of a button.
- **Edit Notes**: Modify note content directly within the app.
- **Delete Notes**: Remove notes by clicking on the delete icon.
- **Persistent Storage**: Automatically saves and retrieves notes from local storage.

## Overview
The Notes App consists of three main components:
1. **HTML**: Defines the structure, including a container for notes and a button to create new notes.
2. **CSS**: Styles the app with a gradient background, a flexible note container, and a well-designed button.
3. **JavaScript**: Handles note creation, deletion, and local storage management. It ensures notes are preserved across page reloads.

### HTML
The HTML file (`index.html`) includes:
- A container (`<div class="container">`) for the app's content.
- A heading (`<h1>`) displaying the app's title and an image.
- A button (`<button class="btn">`) for creating new notes.
- A `<div class="notes-container">` for displaying the notes.

### CSS
The CSS file (`style.css`) includes:
- Basic styling for the body and container.
- Specific styles for headings, buttons, and notes.
- A responsive grid layout for arranging notes.

### JavaScript
The JavaScript file (`script.js`) includes:
- **`showNotes()`**: Retrieves and displays notes from local storage.
- **`updateStorage()`**: Updates local storage with the current notes.
- **Event Listeners**: Handles button clicks for creating notes and interactions for editing and deleting notes.

## Screenshots
Include screenshots of your application below to showcase its features and user interface.

![Screenshot 1]()

## Usage
To use the Notes App:
1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/notes-app.git
2. Navigate to the project directory:
   ```bash
    cd Notes-App
    ```
3. Open `index.html` in your web browser.

