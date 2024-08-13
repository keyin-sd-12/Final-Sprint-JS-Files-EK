1. **`index.html`**: This is the main HTML file that sets up the structure of the webpage. It links to a CSS file for styling and a JavaScript file for functionality. The page displays the title "TECH SAVY U" and a "Warehouse Report" header.

2. **`store.css`**: This file contains the CSS styles for the webpage. It defines the appearance of various elements, including the background color, text alignment, and table styles. Specific styles are applied based on stock levels and product age to highlight different statuses.

3. **`store.js`**: The JavaScript file is responsible for fetching a JSON file containing warehouse data, processing this data, and generating an HTML report. It includes functions to calculate product age, list products, calculate total costs, and dynamically generate HTML content. Products are highlighted based on stock levels (low, medium, high) and age (for clearance).

4. **`store.json`**: This JSON file contains the warehouse data, structured with sections, subsections, and products, each with specific details such as ID, product name, price, stock, and availability date.
