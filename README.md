# The Odin Recipes 🍝

A collection of recipes built with plain HTML, developed as an exercise for [The Odin Project](https://www.theodinproject.com/) course. The project simulates a small recipe website, with a home page listing the available dishes and a dedicated page for each recipe.

## 📖 About the project

This is an HTML fundamentals project: no frameworks, no JavaScript, and no build step. The goal is to practice HTML document structure, relative links, images, lists, and file organization within folders.

**Available recipes:**

- 🧀 [Cheese Bread](src/recipes/cheese-bread.html)
- 🍲 [Lasagna](src/recipes/lasagna.html)

## 📁 Project structure

```text
the-odin-recipes/
├── index.html                  # Home page with the list of recipes
├── README.md
└── src/
    ├── assets/                 # Images used in the recipes
    │   ├── bread.webp
    │   └── lasagna.webp
    └── recipes/                # Individual recipe pages
        ├── cheese-bread.html
        └── lasagna.html
```

Each recipe page contains:

- The dish name and an image;
- A short description of the dish;
- General information (preparation time, servings, and yield);
- The list of ingredients;
- The step-by-step preparation instructions as an ordered list;
- A link back to the home page;
- A footer with project credits.

## 🚀 How to view

There are no dependencies or installation steps. Just open the `index.html` file in any browser.

If you prefer to serve the project locally:

```bash
# Python 3
python3 -m http.server 8000

# Node.js (with npx)
npx serve
```

Then open `http://localhost:8000` in your browser.

## 🛠️ Technologies

- HTML5

## 👤 Author

Developed by [Guilherme Portela](https://github.com/Guilherme-Portela) as part of the [The Odin Project](https://www.theodinproject.com/) exercises.

## 📄 License

Study project, free to use for reference and learning.
