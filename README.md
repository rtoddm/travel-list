# Far Away – Travel Packing List

A small React application for creating and managing a travel packing list.

This project was built while working through Jonas Schmedtmann's *The Ultimate React Course* and focuses on practicing React state, forms, event handling, and component communication.

## Features

- Add items to a packing list
- Select a quantity for each item
- Mark items as packed or unpacked
- Delete individual items
- Sort items by:
  - Input order
  - Description
  - Packed status
- View packing progress and statistics
- Clear the packing list

## What I Practiced

- Creating and composing React components
- Managing state with `useState`
- Building controlled form elements
- Handling form submissions and user events
- Passing data through props
- Passing callback functions through props
- Updating arrays in React state without mutation
- Rendering lists with `.map()`
- Deleting items with `.filter()`
- Updating objects in an array with `.map()`
- Conditionally rendering content
- Sorting data without mutating React state
- Sharing state between components by lifting state up

## Component Structure

The application is divided into several components:

- `App` – manages the main packing-list state
- `Logo` – displays the application heading
- `Form` – handles creation of new packing-list items
- `PackingList` – displays and sorts the list
- `Item` – represents an individual packing-list item
- `Stats` – displays packing progress

## Built With

- React
- JavaScript
- HTML
- CSS

## About

This is a course project completed as part of my ongoing React learning. The primary goal was to practice managing state across multiple components and understanding how data and event handlers move through a React application.
