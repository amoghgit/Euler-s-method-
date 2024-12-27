Euler's Method: JavaScript Implementation

Overview

This project implements Euler's Method to solve the first-order differential equation:

The program calculates the solution numerically and visualizes the results in both tabular and graphical forms. It is implemented in pure JavaScript, HTML, and CSS, utilizing the Chart.js library for graphing.

Features

Numerical Solution: Solves the differential equation using Euler's Method.

Dynamic Table: Displays the computed values of  and  in a structured table.

Interactive Graph: Plots the -values against -values on a graph using Chart.js.

Responsive Design: The layout adjusts dynamically for an optimal user experience.

Technologies Used

HTML: Structure of the web page.

CSS: Styling for the table and layout.

JavaScript: Logic for Euler's Method and dynamic DOM manipulation.

Chart.js: Library for creating the interactive graph.

Files in the Repository

index.html: Main HTML file containing the structure and script for the project.

README.md: This documentation file.

Usage

Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge).

No additional setup is required as all dependencies are included via CDN.

Running the Program

Clone or download the repository to your local machine.

Open index.html in any web browser.

View the solution table and the corresponding graph dynamically generated.

Example Output

Solution Table

x

y

0.0

1.000000

0.1

1.000000

0.2

1.010000

0.3

1.030400

0.4

1.062300

...

...

Graph

The graph plots the -values against -values, illustrating the numerical solution computed by Euler's Method.

Code Description

Euler's Method Function: The eulersMethod function iteratively calculates -values for given -values and step size .

Dynamic Table Generation: The JavaScript dynamically populates the solution table based on computed values.

Graphing with Chart.js: The solution graph is rendered with Chart.js for better visualization.

Future Enhancements

Allow users to input custom differential equations, initial conditions, and step sizes.

Add error analysis to compare the numerical solution with an analytical solution.

Include options for different numerical methods (e.g., Runge-Kutta).

Acknowledgments

Chart.js: For providing an excellent graphing library.

MDN Web Docs: For detailed JavaScript and HTML references.

