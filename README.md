# Lunch Roulette App - "The Indecision Solver!"

Tired of the daily "What's for lunch?" debate? This fun and interactive roulette wheel app is here to save the day! Spin the wheel and let fate decide your next delicious meal.

This project is a simple web application built with HTML, CSS, and JavaScript, featuring GSAP for smooth animations and `canvas-confetti` for a celebratory touch when a choice is made.

**Live Demo:** [https://chulbrain.github.io/lunch-roulette-app/](https://chulbrain.github.io/lunch-roulette-app/)

## Features

* **Interactive Roulette Wheel:** A visually appealing pie-chart style roulette that spins dynamically.
* **Customizable Menu:** Easily add or remove lunch/dinner options to personalize the choices.
* **Menu Management:**
    * Input field to add new menu items.
    * List of current menu items with an option to delete each one.
* **Local Storage:** Your custom menu list is saved in your browser's local storage, so your preferences are remembered for the next visit.
* **Spin Animation:** Smooth spinning animation powered by GSAP, with the wheel gradually slowing down to reveal the chosen menu.
* **Text Readability:** Menu item names are displayed clearly on the roulette and remain upright (always facing the user) even while the wheel is spinning. The text color and shadow are optimized for readability against various background colors of the roulette slices.
* **Winning Celebration:** A pop-up modal announces the chosen menu with a fun confetti explosion effect.
* **Responsive Design:** Optimized for a good user experience on both desktop and mobile devices.
* **Engaging Title:** The app is titled "결정장애 해결! 점심 룰렛" (The Indecision Solver! Lunch Roulette) to clearly and humorously convey its purpose.

## Technologies Used

* **HTML5:** For the basic structure of the web page.
* **CSS3:** For styling the application, including responsive design elements and text effects for readability.
* **JavaScript (ES6+):** For the application logic, including:
    * Random menu selection.
    * DOM manipulation for adding/removing menu items.
    * Interaction with local storage.
    * Controlling animations and text orientation.
* **GSAP (GreenSock Animation Platform):** Used for the core roulette spinning animation and for updating text orientation during the spin.
* **Canvas Confetti:** For the fun confetti effect upon menu selection.

## How to Use

1.  **Open the App:** Navigate to the [Live Demo link](https://chulbrain.github.io/lunch-roulette-app/).
2.  **Manage Menu (Optional):**
    * Scroll down to the "메뉴 관리" (Menu Management) section.
    * To add a new menu item, type its name into the input field and click "추가" (Add).
    * To remove an existing menu item, click the "삭제" (Delete) button next to it in the list.
3.  **Spin the Wheel:** Click the "점심 메뉴 결정!" (Decide Lunch Menu!) button.
4.  **See the Result:** Watch the roulette spin and land on a randomly selected menu item. A pop-up will appear with the chosen menu and a confetti celebration!

## Setup for Local Development

If you want to run this project locally:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/chulbrain/lunch-roulette-app.git](https://github.com/chulbrain/lunch-roulette-app.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd lunch-roulette-app
    ```
3.  **Open `index.html` in your browser:**
    Simply open the `index.html` file in your preferred web browser.

No special build steps are required as this is a static website.

## Future Enhancements (Ideas)

* Option to share the chosen menu on social media.
* Different themes or color schemes for the roulette wheel.
* Ability to assign weights or probabilities to certain menu items.
* User accounts to save menu lists across devices (this would require a backend).
* Sound effects for spinning and winning.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests! If you have any suggestions or find any bugs, please open an issue on the GitHub repository.

---

Enjoy your decisive lunches!
