# Rania-s-Recipe-Notebook
# Recipe Management System

**Developed by:** Rania Zulfiqar  

A simple **AngularJS-based Recipe Management System** that allows users to **add, view, edit, and delete recipes** directly in the browser. All data is stored in the browser's **Local Storage**, making it a fully front-end application with no backend dependency.

---

## Features

- **Add Recipes**: Enter recipe title, ingredients, instructions, and optionally upload an image.
- **Edit Recipes**: Modify existing recipes.
- **Delete Recipes**: Permanently remove recipes with a confirmation modal.
- **Search Recipes**: Filter recipes by title or ingredients.
- **Pagination**: View recipes with customizable items per page.
- **Data Persistence**: All recipes are stored in **Local Storage** under the key `recipes`.
- **Sample Recipes**: Seed the system with pre-defined sample recipes for testing.
- **Reset All**: Clear all recipes from Local Storage with confirmation.
- **Responsive Design**: Works on both desktop and mobile devices.

---

## Technologies Used

- **HTML5 & CSS3**
- **AngularJS 1.8**
- **Google Fonts (Inter)**
- **Browser Local Storage** for data persistence

---

## How to Use

1. Open `index.html` in a modern browser (Chrome, Firefox, Edge, etc.).
2. Use the **“+ Add Recipe”** button to add a new recipe.
3. Use the **search bar** to filter recipes by title or ingredients.
4. Click **Edit** to modify a recipe, or **Delete** to remove it permanently.
5. Use **Seed Sample Recipes** to add demo recipes quickly.
6. **Reset All Recipes** clears all stored data in the browser.

---

## Form Details

- **Title**: Required
- **Ingredients**: Required (comma-separated)
- **Instructions**: Optional
- **Image**: Optional (stored as Base64 string in Local Storage)

---

## Code Structure

- **AngularJS Controller** (`MainController`) manages:
  - CRUD operations
  - Search and filter logic
  - Pagination
  - Image upload and preview
  - Confirmation and alert modals

- **CSS**: Modern warm color palette with responsive layout.
- **Data Storage**: Uses `localStorage` with key `recipes`.

---

## Notes

- No backend is required; this is a purely front-end application.
- Images are stored in Local Storage as **Base64 strings**, which may increase storage usage if many large images are added.
- The application is designed to work offline once loaded in the browser.

---

## Future Improvements

- Add **categories/tags** for recipes.
- Add **rating or favorite system**.
- Implement **export/import recipes** feature.
- Connect to a backend for persistent storage and user accounts.

---

**Enjoy managing your recipes! 🍲**
