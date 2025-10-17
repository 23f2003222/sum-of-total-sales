# Sales Summary Application

This is a simple single-page web application designed to fetch sales data from a CSV file, calculate the total sales, and display the summary.

## Features

*   Fetches `data.csv` asynchronously.
*   Parses CSV data to extract sales figures.
*   Calculates the sum of all sales.
*   Dynamically updates the page title with the sales summary.
*   Displays the total sales on the page.
*   Responsive design using Bootstrap for a consistent user experience across devices.
*   Includes error handling for file fetching and parsing.

## Setup and Usage

1.  **Save the files:** Ensure `index.html` and `data.csv` are in the same directory.
2.  **Open `index.html`:** Open `index.html` in your web browser.
3.  **View Sales Summary:** The application will automatically fetch `data.csv`, calculate the total sales, and display it.

### `data.csv` Format

The `data.csv` file should be a comma-separated values file with a header row. It **must** contain a column named `sales`. Example:

```csv
product,category,sales
Laptop,Electronics,1200.50
Mouse,Electronics,25.99
Keyboard,Electronics,75.00
Monitor,Electronics,300.25
```

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **JavaScript (ES6+):** For fetching data, parsing CSV, and dynamic content updates.
*   **Bootstrap 5:** For responsive styling and UI components.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.