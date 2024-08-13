**`index.html`** The main HTML file, sets up the structure of the webpage. It links to a CSS file for styling and a JavaScript file for functionality.

**`store.css`** CSS styles for the webpage (the appearance of various elements, including the background color, text alignment, and table styles). Specific styles are applied based on stock levels and product age to highlight different statuses.

**`store.js`** JavaScript code for fetching a JSON file containing warehouse data, processing this data, and generating HTML report. It includes functions to list products, calculate total costs, and dynamically generate HTML content. Products are highlighted based on stock levels (low, medium, high) and product age (for clearance events).

**`store.json`** Contains the warehouse data, structured with sections, subsections, and products, each with specific details such as ID, product name, price, stock, and "first available" date (is used to calculate the product age).
