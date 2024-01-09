# SunshineMeals

Welcome to SunshineMeals! This project is a React-based web application for ordering delicious meals online. With SunshineMeals, users can explore a variety of meals, add them to the cart, and place orders.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Demo

[https://food-ordering-web-puce.vercel.app/]

## Features

- **Browsing Meals:** Explore a diverse selection of meals.
- **Shopping Cart:** Add items to the cart and review the total amount.
- **Order Placement:** Place orders with ease.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: "git clone https://github.com/your-username/SunshineMeals.git"
2. Navigate to the project directory: "cd SunshineMeals"
3. Install dependencies: "npm install"
4. Start the development server: "npm start"
5. Open your browser and visit "http://localhost:3000"

## Folder Structure

Here's an overview of the project's folder structure:

- **Food_app:**
  - **node_modules:** The directory where npm installs project dependencies.
  - **public:** Contains static assets and the `index.html` file.
  - **src:** The main source code for the React application.
    - **assets:** Holds images, fonts, or other non-code assets.
    - **components:**
      - **Cart:**
        - `Cart.js`: Component for displaying the shopping cart.
        - `CartIcon.js`: Component for the cart icon in the header.
        - `CartItem.js`: Component for individual items in the cart.
      - **Layout:**
        - `Header.js`: Component for the header of the application.
        - `HeaderCartButton.js`: Component for the cart button in the header.
      - **Meals:**
        - **MealItem:**
          - `MealItem.js`: Component for displaying individual meal items.
          - `MealItemForm.js`: Component for the form to add meals to the cart.
        - `AvailableMeals.js`: Component for displaying the list of available meals.
        - `Meals.js`: Component combining MealsSummary and AvailableMeals.
        - `MealsSummary.js`: Component for displaying a summary of available meals.
      - **UI:**
        - `Card.js`: Component for a generic card layout.
        - `Input.js`: Component for input elements.
        - `Modal.js`: Component for a modal overlay.
    - **store:**
      - `Cart-Context.js`: Context for managing the state of the shopping cart.
      - `CartProvider.js`: Higher-order component providing the cart context.
    - `App.js`: The main component that combines various components.
    - `index.css`: Global styles for the application.
    - `index.js`: Entry point of the React application.

- **.gitignore:** Specifies intentionally untracked files to ignore in version control.
- **package-lock.json:** Lock file for npm dependencies.
- **package.json:** Configuration file for npm, includes project dependencies and scripts.


## Technologies Used

- React
- Module Based CSS.

## Contributing

If you want to contribute to SunshineMeals, follow these steps:

1. Fork the repository.
2. Create a new branch: "git checkout -b feature/your-feature-name"
3. Commit your changes: "git commit -m 'Add your feature"
4. Push to the branch: "git push origin feature/your-feature-name"
5. Open a pull request.

