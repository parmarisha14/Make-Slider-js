Live Project:: https://make-slider-js.vercel.app/


![Screenshot 2025-06-10 211356](https://github.com/user-attachments/assets/7b61eefc-d802-481a-a646-4a4e95dad3f8)



📝 Project Title

Custom Image Carousel Using HTML, CSS, Bootstrap, and JavaScript

📌 Objective

To create a simple, responsive image carousel that allows users to navigate through images using custom left and right navigation buttons.

🧱 Technologies Used

HTML5 – Page structure

CSS3 – Custom styling

Bootstrap 5 – Responsive design and button styles

JavaScript (Vanilla) – Carousel functionality

📁 File Structure



├── index.html                  # Main HTML file

├── style.css                   # Custom CSS styles

├── script.js                   # Carousel functionality

└── /images                    # Folder containing image1.jpg, image2.jpg, image3.jpg

📄 File Details

✅ index.html

Contains the layout of the carousel.

Uses Bootstrap grid system to center the carousel.

Loads three images inside .carousel-item elements.

Includes two custom navigation buttons (left/right) with Bootstrap Icons.

JavaScript file script.js is linked at the bottom.


🎨 style.css

Applies basic styling to remove default margins and paddings.

Defines the size, overflow, and appearance of carousel elements.

Uses object-fit: cover to ensure images fill the container proportionally.


⚙️ script.js

Controls the active slide with JavaScript.

Implements nextSlide() and prevSlide() functions to cycle through images.

Dynamically updates the .active class to show the correct image.


🎯 Features

Fully responsive using Bootstrap grid.

Smooth image transitions.

Simple and clean UI with rounded images and custom buttons.

Lightweight with minimal external dependencies.

🔧 How to Use

Open the index.html file in a browser.

Use the left (<) and right (>) buttons to navigate between images.

📈 Future Improvements
Add slide indicators (dots).

Add automatic slide transitions with setInterval.

Support swipe gestures for mobile devices.
