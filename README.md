# Personal Expense Tracker

A SwiftUI-based app that helps users track their expenses by adding, viewing, sorting, and filtering them. It supports dynamic updating of the expense list and allows toggling between dark and light modes. The app also stores expenses persistently using `@State`, `@ObservedObject`, and `UserDefaults` for saving data.

## Features

### 1️⃣ Expense Entry Form

- **Expense Name**: Enter the name of the expense.
- **Amount**: Enter the expense amount (numeric values only).
- **Category**: Select a category for the expense (e.g., Food, Travel, Shopping).
- **Add Expense Button**: Adds the entered expense to the expense list.

### 2️⃣ Displaying Expenses

- **Expense List**: View all added expenses dynamically updated with a `List`.
- **Expense Details**: Each expense displays its name, amount (formatted with a currency symbol), and category.

### 3️⃣ Filtering

 **Filter by Category**: Filter expenses based on selected categories (e.g., Food, Travel, Shopping).

### 4️⃣ Dark Mode Toggle

- **Theme Switcher**: Toggle between light and dark mode using a switch. The app's background and text colors adjust accordingly for optimal readability.

### 5️⃣ Bonus Features

- **Smooth Animations**: Enjoy smooth transitions when adding or sorting expenses.

### User Instructions

Adding an Expense


Enter the Expense Name in the text field. 

Use the Amount field (or Stepper) to enter the numeric value.

Select an Expense Category using the Picker.

Tap the Add Expense button to add the expense to the list.

Viewing Expenses


The app displays a list of all added expenses.

Filter expenses by category using the filtering option.

Switching Themes


Toggle between Dark Mode and Light Mode using the switch to customize the theme.
