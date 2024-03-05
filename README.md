# Refactoring-and-Bug-fixing

## Introduction

The Note Taking Application is a simple web application developed using Python, Flask, and HTML. It allows users to add and view notes seamlessly on the same page.

## Features

- Add notes: Users can input their notes using a text field and submit them.
- View notes: All the added notes are displayed as an unordered list below the text field on the same page.

## Bug Fixes and Improvements

1. **Corrected method to retrieve note:** Fixed the code to properly handle form data in POST requests by using `request.form.get("note")`.

2. **Added validation for empty notes:** Implemented a check to ensure that only non-empty notes are added to the list of notes.

3. **Handled GET requests:** Modified the route to handle both GET and POST requests, enabling users to access the page and view existing notes.

4. **Passed form data to template:** Included the `notes` list as a parameter when rendering the HTML template, ensuring proper display of notes on the page.

## Installation

To run the Note Taking Application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install Flask using `pip install Flask`.
3. Navigate to the project directory and run the application using `python app.py`.
4. Access the application in your web browser at `http://localhost:5000`.

## Usage

1. Access the application through your web browser.
2. Input your note in the text field and click the "Add Note" button to submit.
3. Your note will be added to the list below the text field, and you can continue adding more notes.
