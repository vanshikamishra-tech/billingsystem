Supermarket Billing System
An interactive web-based billing system that allows users to browse products, add items to their cart, apply discount codes, and generate a printable receipt — all in the browser using HTML, CSS, and JavaScript.

🔧 Features
- Product Selection & Quantity Input
Users can view available items, adjust quantities, and add them to their cart.
- Search & Filter
Real-time filtering based on product name.
- Cart Management
View added products, remove items, and see subtotal in real time.
- Checkout Flow
- Takes customer details
- Displays purchased items with total
- Option to apply discount codes
- Generates printable receipt
- Admin Discount Code Generator
Store discount codes in localStorage with dynamic percentage values.


Project Structure
.
├── index.html               // Product selection page
├── checkout.html            // Checkout interface
├── styles.css               // Styling for the UI
├── script.js                // Core logic & functionality
└── .vscode/                 // VS Code workspace settings



💾 Data Handling
- Cart items and discount codes are stored using localStorage for persistence between pages.
- All pricing calculations are dynamic and update in real time.

📸 Screenshots (Optional)
You can include screenshots or screen recordings here to illustrate how the interface works.

📝 Usage
- Open index.html to start selecting products.
- Click "Proceed to Checkout" to enter customer details.
- Apply a discount code (if any).
- Click "Generate Receipt" to view billing summary.
- Print receipt or start over.

🚀 Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- No external libraries required — lightweight and browser-friendly.

