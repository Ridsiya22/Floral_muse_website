# Floral_muse_website

FLORAL MUSE -ECOMMERCE FLOWER SHOP WEBSITE

A responsive and visually appealing flower shop website built with HTML5, CSS3, Bootstrap 5, and JavaScript. Features dynamic flower cards, a falling petal animation, and a smooth user experience for browsing     and purchasing floral arrangements.

FEATURES

1.Responsive Design - Fully compatible with all screen sizes using Bootstrap 5.

2.Dynamic Flower Cards - Generated via JavaScript with hover effects and smooth animations (using AOS library).

3.Falling Petal Animation - Custom canvas-based animation for a floral-themed background.

4.Buy Now Redirection - Clicking "Buy Now" redirects to a checkout page with product details.

5.Modern UI/UX - Clean layout, elegant typography, and interactive elements.

TECHNOLOGIES USED:

1.HTML5 - Semantic markup for structure.

2.CSS3 - Custom styles and Bootstrap 5 for responsive layouts.

3.JavaScript (ES6) - Dynamic content generation and interactivity.

4.Bootstrap 5 - Responsive grid, components, and utilities.

5.AOS (Animate On Scroll) - Smooth scroll-triggered animations.

6.Canvas API - Falling petal animation.

Project Structure:

text
Floral-Muse/
|- index.html                 # Main HTML file
|- buy-now.html               # Checkout page (referenced in script)
|- assets/                    # Images and other static files
|   |- p2.webp
|   |- heartb.jpeg
|   |- tulip.jpg
|   |- vase.jpg
|   |- sunset.jpeg
|   |- waterl.jpg
|   |- petal.jpg              # Petal image for animation
|- README.md                  # Project documentation
|- (Optional CSS/JS folders)  # If external CSS/JS files are added later
Setup & Usage

KEY CODE HIGHLIGHTS

1. Dynamic Flower Cards
Flower data is stored in an array and rendered dynamically:

2. Falling Petal Animation
   
 ->Uses HTML5 Canvas to create a calming petal fall effect:

 ->Flower class manages position, speed, and rendering.

 ->Animation loop updates and draws petals continuously.

3. Buy Now Redirection
=>Clicking "Buy Now" passes product details via URL parameters:
