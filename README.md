# Blog with Lazy Loading

This is a simple blog project developed to practice the Lazy Loading functionality. The main goal is to optimize image loading, especially for users with slower internet connections, providing a better browsing experience.

## Features

- **Lazy Loading of Images:** Images in this blog are loaded only when they enter the visible area of the screen, reducing the initial page load time.
- **Simple Blog Structure:** The project includes a basic blog layout with a title, text, and images.

## Technologies Used

- **HTML5:** For the blog structure.
- **CSS3:** For styling and layout of the page.
- **JavaScript:** To implement the Lazy Loading functionality.

## How It Works

This project uses the Intersection Observer API to implement Lazy Loading for images. The images are observed, and when they enter the viewport, their `src` is updated to load a higher resolution version.
