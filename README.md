# MERN shop119

# Topics

1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository
5. List Products
   a.create products array
   b.add product images
   c.render products
   d.style products
6. Add page routing
   a.npm i react-router-dom
   b.create route for home screen
   c.create router for product screen
7. Create Node.JS Server
   a.run npm init in root folder
   b.Update package.json set type: module
   c.Add .js to imports
   d.npm install express
   e.create server.js
   f.add start command as node backend/server.js
   g.require express
   h.create route for / return backend is ready.
   i.move products.js from frontend to backend
   j.create route for /api/products
   k.return products
   l.run npm start
8. Fetch Products From Backend
   a. Set proxy in package.json
   b. npm install axios
   c. Use state hook
   d. Use effect hook
   e. Use reducer hook
9. Manage State by Reducer Hook
   a. define reducer
   b. update fetch data
   c. get state from usReducer
10. Use React-bootstrap UI framework
    a. npm install react-bootstrap bootstrap
    b. update App.js
11. Create Product and Rating component
    a. Create Rating component  
    b. Create Product component
    c. Using Rating component in Product component
12. Create Product Details view
    a. Fetch products from backend
    b. create three boxes for image, details and process action
13. Create Loading and Message Component
    a. create loading component
    b. use spinner component
    c. craete message component
    d. create utils.js to define getError function
14. Implement Add to Cart
    a. Create React Context
    b. define reducer
    c. create store provider
    d. implement add to cart button click handler
15. Complete Add to Cart
    a. Check existed item in the cart
    b. Check count in stock in the backend
