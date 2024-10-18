Restaurant Menu Selection System
Project Overview
This project is an interactive restaurant menu system where customers make their meal selections by choosing physical objects of various colors and shapes. Each color represents one of four food groups: starters, snacks, main courses, and desserts. Additionally, each color contains objects in three different shapes, each corresponding to a specific dish within its food group.

By leveraging Object-Oriented Programming (OOP) and OpenCV for image processing, the program reads an image of the selected objects, identifies the customer's choices, confirms the order, and calculates the total amount to be paid.

Features
Four Food Groups: Starters, Snacks, Main Courses, Desserts
Three Dish Options Per Group: For each food group, there are three different dish choices, represented by objects of different shapes.
Color-Coded Groups: Each food group is associated with a different color.
Image Processing with OpenCV: The program uses image recognition to identify the chosen objects from an image, matching them with the corresponding dishes.
Order Confirmation: The system confirms the recognized order by asking the customer, "Your order is [dish names], do you confirm?"
Total Price Calculation: After confirmation, the program calculates the total price of the order and displays the amount.
Requirements
Python: The project is written in Python.
OpenCV: Used for image processing to detect selected objects.
NumPy: A fundamental package for numerical operations in Python.
Object-Oriented Programming: Ensures modular and scalable code for food items, prices, and object recognition.
Setup Instructions
Clone the repository:

bash
git clone https://github.com/yourusername/restaurant-menu-system.git
cd restaurant-menu-system
Install required packages:

bash
pip install opencv-python numpy
Run the program: After ensuring your system has OpenCV installed, you can run the main program:

bash
python main.py
Upload an Image of the Order: The program will prompt you to upload an image file (e.g., yourorder.png) containing the selected objects. The program will then analyze the image to recognize the colors and shapes of the objects and interpret them as dishes.

How it Works
Dish Representation: Each food group is represented by a different color (e.g., red for starters, green for snacks). Each group contains three dishes, represented by different shapes (e.g., circles, squares, triangles).
Order Input: A customer chooses one object from each food group by selecting physical objects on their table.
Image Processing: The program reads an image of the objects using OpenCV and identifies the chosen dishes based on color and shape recognition.
Order Confirmation: After recognizing the selected dishes, the program asks the customer for confirmation of their order.
Total Calculation: Once confirmed, the program calculates the total price based on the selected dishes.
Object-Oriented Design
Classes: The program is designed using OOP, with distinct classes for food groups, dishes, and menu items. Each dish has attributes like name, price, color, and shape.
Modular Design: The use of classes makes it easy to extend the system by adding new dishes, groups, or functionality in the future.
Sample Menu
Starters: Soup, Cheese Platter, Garlic Bread
Snacks: Crispy Chicken, Fish & Chips, Omelet
Main Course: Meatballs, Casserole, Fajitas
Desserts: Souffle, Tiramisu, Cheesecake
Future Enhancements
Adding support for more complex dish combinations and customization.
Implementing more advanced object recognition for multi-object detection in images.
License
This project is licensed under the MIT License.

Feel free to contribute, report issues, or suggest improvements to enhance the system!
