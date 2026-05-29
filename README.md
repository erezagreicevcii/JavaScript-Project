# Ereza's Forkify

This is my Forkify project, built while following Jonas Schmedtmann's JavaScript course. I worked on it gradually and added the main features one by one, starting from loading a recipe and then continuing with search, pagination, servings, bookmarks, and uploading a custom recipe.

The app allows users to search for recipes, open the recipe details, change the number of servings, save favorite recipes, and add their own recipe through a form. Bookmarks are saved in local storage, so they stay saved even after refreshing the page.

## Features

- Search recipes by ingredient or keyword
- View full recipe details
- Change servings and automatically update ingredient quantities
- Bookmark and unbookmark recipes
- Save bookmarks in local storage
- Add a custom recipe through the upload form
- Simple personal touch with the browser title: "Ereza's forkify"

## Built With

- JavaScript
- HTML
- Sass
- Parcel
- Forkify API

## How To Run

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run start
```

Build the project:

```bash
npm run build
```

## Notes

This project was made for practice and learning. I kept the structure close to the course project, using separate files for the model, controller, helpers, config, and views. The goal was not only to finish the app, but also to understand better how the data, UI, and user actions connect together in a real JavaScript application.
