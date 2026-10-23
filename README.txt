COLLEGE CANTEEN PRE-ORDER SYSTEM
================================
A front-end prototype built with HTML, CSS and JavaScript.

FEATURES
- Food menu with prices
- Add to cart, increase/decrease quantity, total amount
- Place order (demo order number is generated)
- Order tracking: Order Placed -> Preparing -> Ready for Pickup

PROJECT STRUCTURE
CollegeCanteenPreOrder/
  index.html      - page structure
  css/style.css   - design and layout
  js/script.js    - menu, cart, order and tracking logic
  README.txt      - this file

HOW TO RUN
1. Unzip the folder.
2. Open it in VS Code (File > Open Folder).
3. Right-click index.html > "Open with Live Server"
   (or just double-click index.html to open in a browser).
4. Add items, click Place Order, then click "Demo: Update Status".

NOTE
Orders are simulated in the browser (localStorage). A real system would need
a backend (e.g. Node.js/Java + MySQL) so orders are shared across devices.
