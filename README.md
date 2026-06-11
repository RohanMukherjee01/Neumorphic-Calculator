# 🧮 Neumorphic Calculator with Dark/Light Theme Toggle

A sleek, modern, and highly responsive web-based standard calculator built using pure frontend technologies. This project showcases advanced styling techniques like **Neumorphic Design (Soft UI)** and dynamic DOM manipulation using Vanilla JavaScript.

## 🚀 Tech Stack
* **Structure:** HTML5
* **Styling:** CSS3 (Custom Variables, Neumorphic Box-Shadows, Transitions)
* **Logic:** JavaScript (Vanilla JS, Event Listeners, String Evaluation)
* **Icons:** Ionicons Open-Source Library

## ✨ Key Technical Features

* **Neumorphic Glass/Soft UI:** Utilizes complex CSS `box-shadow` properties (combining both inset and outset shadows) to achieve a soft, extruded 3D tactile feel for the calculator body and keys.
* **Dynamic Theme Toggle:** Implements an instant Dark/Light mode switcher. JavaScript captures the click event on the toggle button, dynamically adds/removes the `.dark` class to the HTML `body`, and flips the background colors, text colors, and shadow intensities smoothly.
* **Smart Arithmetic Engine:** Leverages JavaScript's built-in `eval()` function to instantly compute complex string expressions entered by the user.
* **Robust Error Handling:** Wrapped in a `try-catch` block to handle edge cases elegantly. If a user inputs an invalid expression, the calculator cleanly displays `Error` instead of crashing.
* **Dynamic Asset Swapping:** Uses JS to dynamically update the `name` attribute of the theme icon (`moon-outline` vs `sunny-outline`) in real-time as the user switches modes.

## 📂 File Structure Explained
* **`index.html`**: Contains the semantic markup for the calculator layout, button wrappers, and the script logic handling key presses and theme toggles.
* **`design.css`**: Contains the core styling, responsive alignment via Flexbox/Grid, and smooth transition animations (`0.5s` fade) between light and dark themes.

## 🛠️ How to Run This Project Locally

Since this is a client-side application, you don't need any local servers (like XAMPP/Apache) to run it.

Developed with ❤️ by Rohan | Cloud & Infrastructure Engineer | Tech Educator
-
