# ChristoffelsMenu-FinalPOE

🍽️ ChristoffelMenu — Final PoE
Introduction

ChristoffelMenu is a React Native (Expo) application built for Chef Christoffel, a private chef who offers personalized dining experiences. The app allows him to manage his digital menu by adding, removing, and editing dishes while clients can view and filter the available menu by course.

This project was developed as part of the Mobile Application Development PoE and showcases the use of TypeScript, React Native components, navigation, and dynamic data handling to create a seamless user experience across Android and iOS devices.

🌟 Features Implemented

View Full Menu: Home screen displays all current dishes.

Add / Remove Menu Items: Chef can add new dishes with a name, description, course, and price, and remove old ones.

Filter by Course: Guests can filter the menu to view only Starters, Mains, Desserts, or Beverages.

Average Price Display: Home screen shows the average price per course.

Dynamic Data Handling: All items are stored in arrays using TypeScript variables.

Navigation: Smooth transitions between Home, Add Item, and Filter Screens using React Navigation.

Reusable Functions: Functions organize code logic for adding, removing, and calculating averages.

Loops Used: for, while, and for in loops implemented for calculations and data handling.

🛠️ Change Log (Since Part 2)
Date	Description of Change
2025-09-20	Implemented feedback from Part 2 and removed placeholder code.
2025-09-21	Created a separate Add Menu Item Screen (moved logic from Home Screen).
2025-09-21	Added a filter screen that allows guests to filter menu items by course.
2025-09-22	Implemented average price calculation per course using a for loop.
2025-09-22	Added functionality to remove items from the menu array.
2025-09-23	Refactored the app into multiple files (HomeScreen.tsx, AddItemScreen.tsx, FilterScreen.tsx, MenuListScreen.tsx) for cleaner structure.
2025-09-23	Added helper functions for adding/removing items and calculating totals.
2025-09-24	Improved UI styling and spacing for better readability.
2025-09-25	Final testing, debugging, and recording video demonstration.
🔁 Refactoring Summary

To improve performance and readability:

Moved logic from App.tsx into individual screen files.

Created utility functions to handle adding/removing items and calculating averages.

Replaced inline logic with reusable functions.

Introduced loops (for, while, for in) for calculations instead of repetitive code.

Cleaned up component imports and organized file structure.

🚀 How to Run the Project

Clone this repository:

git clone https://github.com/Olwethu-Tshabalala/Formative-2-Part-2-MAST.git


Navigate into the folder:

cd ChristoffelMenu


Install dependencies:

npm install


Start the project:

expo start


Scan the QR code on your phone using the Expo Go app.

🎥 Demonstration Video

📺 Watch the app in action here:
YouTube Demo (Unlisted)

👨‍🍳 Developed by

Olwethu Tshabalala
Mobile Application Development PoE — Part 3
Date: 11 November 2025
