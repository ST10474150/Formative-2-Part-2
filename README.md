Christoffel Chef Menu App – Part 2

Overview
This is a React Native mobile application.  
The app acts as a digital menu management tool for Christoffel, a private chef, allowing him to:

- Add new menu items dynamically
- View all menu items on the home screen
- See the total number of dishes
- Select dish details such as name, description, course, and price

This version (Part 2) focuses on core UI functionality. The data is not stored permanently and will reset when the app reloads.

---

Features

1. Home Screen
   - Displays all menu items in a scrollable list
   - Shows dish name, description, course, and price
   - Shows the total number of dishes
   - Button to navigate to the Add Menu Item screen

2. Add Menu Item Screen
   - Input fields for dish name, description, and price
   - Dropdown (Picker) to select course: Starters, Mains, Desserts
   - Save button adds the item to the menu
   - Navigation button back to Home Screen
   - Validation to ensure dish name and price are entered

3. Animations
   - Fade-in animation on Home Screen title and image

4. Navigation
   - Stack navigation between Home and dd Menu Item screens using React Navigation

---

Video





git clone <your-github-repo-link>
cd chef-menu
