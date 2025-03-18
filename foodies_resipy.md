# Foodies Recipe Mobile Application

Welcome to the **Foodies Recipe Mobile Application**! This Flutter-based mobile app allows users to browse, search, and view delicious recipes using the **TheMealDB API**. It’s built with Flutter for seamless cross-platform functionality, supporting both Android and iOS users with a smooth, responsive UI.

## Features

- 🍲 **Browse Categories**: View a variety of meal categories to explore different cuisines.
- 🔍 **Search Recipes**: Quickly search recipes by name, category, or ingredient.
- 📝 **Recipe Details**: View detailed instructions, ingredients, and cooking time for each recipe.
- 🍴 **User-Friendly Interface**: Designed with simplicity in mind, ensuring a great user experience.
- 🌎 **Global Cuisine**: Access recipes from a wide range of global cuisines.

## Screenshots

![App Screenshot 1](App_overview/home_page.png) ![App Screenshot 2](App_overview/image.png)

## Tech Stack

- **Flutter**: Framework for building the mobile app.
- **Dart**: Programming language used to develop the app.
- **TheMealDB API**: A free API that provides meal categories, recipes, and ingredients.
- **JSON**: For handling data from the API.

## Installation

To get started with the **Foodies Recipe Mobile Application**:

### Prerequisites

- Flutter installed on your local machine.
- An IDE (e.g., Android Studio, VS Code).
- A physical or virtual Android/iOS device for testing.

### Steps to Run the App

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sahanamugodage/Foodies-Recipe-Mobile-Application.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Foodies-Recipe-Mobile-Application
   ```

3. **Install dependencies:**

   ```bash
   flutter pub get
   ```

4. **Run the application:**
   ```bash
   flutter run
   ```

This will launch the app on your device or simulator/emulator.

## API

The app fetches recipe data from the **TheMealDB API**.

### API Endpoint

- **URL**: `https://www.themealdb.com/api/json/v1/1/categories.php`
- **Method**: GET
- **Description**: This endpoint returns a list of meal categories that can be used to browse different types of recipes.

### Example API Response:

```json
{
  "categories": [
    {
      "idCategory": "1",
      "strCategory": "Beef",
      "strCategoryThumb": "https://www.themealdb.com/images/category/beef.png",
      "strCategoryDescription": "Beef is a type of meat that comes from cattle."
    },
    {
      "idCategory": "2",
      "strCategory": "Chicken",
      "strCategoryThumb": "https://www.themealdb.com/images/category/chicken.png",
      "strCategoryDescription": "Chicken is one of the most popular poultry meats in the world."
    }
    ...
  ]
}
```

### Additional API Details

- You can also use endpoints like `/filter.php?c=category_name` to get meals based on a specific category, or `/lookup.php?i=meal_id` for detailed information on individual recipes.

## Contributing

We welcome contributions to improve this project! If you'd like to help, please fork the repository, make changes, and submit a pull request. Here's how to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Submit a pull request.

---
