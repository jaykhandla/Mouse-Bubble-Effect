# Bubble Effect on Mouse Movement

<div align="center">
  <img src ="./Bubble effects.png" height="250px" width="70%" />  
</div> 

## Overview

The **Bubble Effect on Mouse Movement** is an interactive, web-based animation that creates visually captivating bubble-like effects whenever the user moves their mouse across the screen. As the mouse moves, small, colorful bubbles appear at the cursor's location and float away, adding a dynamic and playful touch to the webpage. This project demonstrates the power of **CSS animations** and **JavaScript** to create lightweight, real-time visual effects that engage users in an interactive experience.

## Features

- **Interactive Bubble Effects**: The page responds to mouse movements, generating colorful bubbles that appear at the cursor's position and drift outward in various directions.
- **Customizable Animation**: The size, speed, and direction of the bubbles are randomized, ensuring a unique visual experience each time the user interacts with the page.
- **Optimized Performance**: The animation is designed to be smooth and efficient, using minimal resources while providing an immersive visual effect.

## Technologies Used

- **HTML5**: Used to structure the webpage and create essential elements.
- **CSS3**: Applied for styling and animation, providing the dynamic bubble effect.
- **JavaScript**: Handles mouse movement detection and dynamically triggers the bubble animations.

## How It Works

When the user moves their mouse over the webpage, the **JavaScript** script listens for the `mousemove` event. Upon detecting the event, small circular elements (`<i>` tags) are created at the mouse pointer's position. These elements are styled using **CSS** to resemble small bubbles. The bubbles animate by moving outward in random directions, fading away, and eventually disappearing from the screen.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/jaykhandla/Mouse-Bubble-Effect.git
    ```

2. **Navigate to the project folder**:
    ```bash
    cd Mouse-Bubble-Effect
    ```

3. **Open `index.html` in your browser** to view the effect in action.

## Live Demo

You can view the live demo of this effect hosted on GitHub Pages [here](https://jaykhandla.github.io/Mouse-Bubble-Effect/).

## Customization

- **Bubble Size, Color, and Speed**: You can adjust the bubble size, color, and speed by modifying the relevant values in the **CSS** and **JavaScript** code.
- **Animation Properties**: Fine-tune the appearance of the bubbles, such as size, opacity, and movement direction, to match your desired aesthetic.