# Travel List

A React packing list app for managing trip items before traveling. Users can add items, mark them as packed, delete items, sort the list, clear everything, and track packing progress.

## Features

- Add travel items with quantity and description
- Mark items as packed or unpacked
- Delete individual items
- Sort items by input order, description, or packed status
- Clear the full list with a confirmation prompt
- View live packing statistics and completion percentage

## Tech Stack

- React
- JavaScript
- CSS
- Create React App

## What I Learned

- Managing local state with `useState`
- Passing data through `props`
- Lifting state up to a shared parent component
- Building controlled form inputs
- Updating arrays immutably with `map`, `filter`, and spread syntax
- Computing derived state for progress statistics
- Sorting displayed data without mutating the original state
- Passing callback functions from parent components to child components

## Project Structure

```txt
src/
  App.js
  index.js
  index.css
```

Main components:

- `App` owns the main `items` state
- `Form` handles new item input
- `PackingList` renders and sorts the list
- `Item` renders each list item
- `Stats` calculates packing progress

## Getting Started

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

Open the app:

```txt
http://localhost:3000
```

## Status

Completed as part of my React learning path, focused on state management fundamentals.
