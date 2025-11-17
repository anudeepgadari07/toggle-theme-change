# toggle-theme-change
# Theme Toggle Project - README

## 📌 Overview

This project demonstrates a simple **Light Mode / Dark Mode** toggle using HTML, CSS, and JavaScript. When the user clicks the toggle button, the displayed images switch between light and dark versions, and the button style updates accordingly.

---

## 📁 Files Included

* **index.html** – Contains the layout, button, and script for toggling.
* **lightImg1.png ... lightImg5.png** – Light theme images.
* **darkImg1.png ... darkImg5.png** – Dark theme images.
* *(Optional)* **styles.css** – External stylesheet, if separated later.

---

## 🚀 How It Works

* A button with ID `toggle` controls the theme switching.
* When clicked:

  * Text updates between *Light Mode* and *Dark Mode*.
  * Button styling changes.
  * Image sources (`src`) swap between light and dark versions.
  * A boolean variable `islight` keeps track of the current theme.

---

## 🔧 JavaScript Logic

* Event listener triggers on button click.
* Based on the `islight` flag:

  * Update button label
  * Update button styles
  * Replace image `src` paths
  * Toggle the `islight` flag value

---

## 🖼 Image Requirements

Place these files in the same folder as `index.html`:

```
lightImg1.png
lightImg2.png
lightImg3.png
lightImg4.png
lightImg5.png

darkImg1.png
darkImg2.png
darkImg3.png
darkImg4.png
darkImg5.png
```

---

## 🏃‍♂️ How to Run

1. Open **index.html** in any browser.
2. Click the **Light Mode / Dark Mode** button to toggle themes.

---

## 🎉 Enjoy!

Feel free to modify the button, animations, or theme to customize your project.
