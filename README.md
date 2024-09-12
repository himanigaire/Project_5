# Responsive Grid Layout

This project demonstrates a responsive grid layout using HTML and CSS Grid. It features a flexible grid that adapts to different screen sizes, making it ideal for creating modern, responsive web pages.

## Project Structure

- `5.html`: Contains the HTML structure for the responsive grid layout.
- `5.css`: Contains the CSS styles that define the layout and appearance of the grid.

## Features

- **Header and Footer**: Both sections have a dark background with white text, centered content, and padding for a clean look.
  
- **Grid Layout**: The grid layout is created using CSS Grid with the following features:
  - **Responsive Columns**: Uses `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));` to create a flexible number of columns that automatically adjust based on the screen size.
  - **Grid Gaps**: A gap of 20px is applied between grid items for clear spacing.
  - **Grid Items**: Each item is styled with background colors, padding, and borders:
    - **Item 1**: Spans two columns.
    - **Item 2**: A shorter item with centered text and a specific text color.
    - **Item 3**: Spans from the second to the fourth row and has a distinct background color.
    - **Item 4 & Item 5**: Share the same column span from the second to the fifth column with a green background.
    - **Item 6**: Spans three columns with a distinct background color.

- **Responsive Design**: A media query adjusts the grid to a single-column layout when the screen width is 600px or smaller, ensuring usability on mobile devices.

## How to Use

1. Clone or download the repository.
2. Open `5.html` in a web browser to view the responsive grid layout.
3. Modify the CSS in `5.css` to experiment with different grid and flexbox properties.


## Author

Created by: Himani Gaire.
