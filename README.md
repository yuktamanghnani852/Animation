# CSS Animation Examples

## 📌 Project Overview

This project demonstrates different **CSS animations** using HTML and CSS. It contains animated squares, a square-path animation, and a Google-style bouncing ball animation.

The project is useful for learning how CSS properties such as `transform`, `opacity`, `animation-duration`, `animation-delay`, and `animation-iteration-count` work.

## ✨ Features

The project includes the following animations:

* 🎨 **Color Animation** – Changes the background color.
* 🔄 **Rotate Animation** – Rotates an element from 0° to 360°.
* ↕️ **Move Animation** – Moves the square vertically.
* 🌫️ **Fade Animation** – Changes the opacity from invisible to visible.
* 🌀 **Spin Animation** – Creates a spinning loader effect.
* 🔍 **Pulse Animation** – Increases and decreases the size of the square.
* ⬛ **Square Path Animation** – Moves a box around a square-shaped path.
* 🔴🟠🟡🟢 **Google Animation** – Creates bouncing colored balls with different animation delays.

## 🛠️ Technologies Used

* HTML5
* CSS3
* CSS Keyframe Animations
* CSS Flexbox
* CSS Transformations

## 📂 Project Structure

```text
CSS-Animation/
│
├── index.html
└── README.md
```

## 🚀 How to Run

1. Create a file named `index.html`.
2. Copy the provided HTML and CSS code into the file.
3. Save the file.
4. Open `index.html` in any modern web browser.

You can also use **VS Code** with the Live Server extension to run the project.

## 🎯 CSS Animations Used

### 1. Color

The square smoothly changes between two background colors.

```css
@keyframes color {
    0% {
        background-color: crimson;
    }

    50% {
        background-color: rgb(167, 240, 165);
    }

    100% {
        background-color: crimson;
    }
}
```

### 2. Rotate

The square rotates continuously from 0° to 360°.

```css
@keyframes rotate {
    0% {
        transform: rotate(0);
    }

    50% {
        transform: rotate(180deg);
    }

    100% {
        transform: rotate(360deg);
    }
}
```

### 3. Move

The square moves vertically between two positions.

```css
@keyframes Move {
    from {
        transform: translate(0, 100px);
    }

    to {
        transform: translate(0, -100px);
    }
}
```

### 4. Fade

The square repeatedly becomes visible and invisible.

```css
@keyframes Fade {
    0% {
        opacity: 0;
    }

    50% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}
```

### 5. Pulse

The square grows and returns to its original size.

```css
@keyframes Pulse {
    0% {
        transform: scale(1);
    }

    50% {
        transform: scale(1.5);
    }

    100% {
        transform: scale(1);
    }
}
```

## 📚 Learning Objectives

After completing this project, you can understand:

* How CSS animations work.
* How to create animations using `@keyframes`.
* How to use `transform`.
* How to use `opacity`.
* How to use `animation-delay`.
* How to create continuous animations.
* How Flexbox can be used to arrange animated elements.

## 👨‍💻 Author

**Your Name**

## 📄 License

This project is created for
# Animation
