# 🍕 Kid Chef Recipes – PWA for Young Cooks

This is a Progressive Web App (PWA) designed to help children learn how to cook and follow instructions in a fun, interactive way.

## 🌟 Features
- Step-by-step instructions for kid-friendly recipes
- Read-Aloud mode using speech synthesis
- Themed visual styles (Dino, Princess, Galaxy, Classic)
- Installable on iOS and Android devices
- Works offline via service worker
- JSON-based recipe files (easy to add or remove)
- Lock/unlock recipes with pins, groups, or scheduled access (optional)

## 📁 Project Structure
```
index.html
manifest.webmanifest
sw.js
recipes/
  ├── index.json
  └── easy_pizza_dough.json
icons/
  ├── icon-192.png
  └── icon-512.png
```

## 🧪 Add a New Recipe
1. Create a `.json` file using the format in `easy_pizza_dough.json`
2. Add an entry to `recipes/index.json`
3. Push your changes — all users will get the new recipe on reload!

## 📡 Auto-Sync Recipes from GitHub
The app loads recipe files from this repository’s `recipes/` folder using GitHub’s raw content URLs. Make sure `index.json` lists every recipe.

## 👨‍🍳 Created with love for little chefs.
#   k i d - c h e f - r e c i p e s  
 #   k i d - c h e f - r e c i p e s  
 