# EJOY Ecommerce Website
1. Build the template for the website
   1. Create EJOY folder
   2. create template folder
   3. create index.html and style.css files
   4. add default HTML code
   5. link index.html to style.css
   6. create header, main and footer
   7. style elements
2. Display Products
3. Create React App
   1. npx create-react-app frontend
   2. npm start
4. copy index.html content to App.js
5. copy style.css content to index.css
6. Create Rating and Product Component
7. Build Product Screen and HomeScreen.js
8. Start with the backend
   1. move products.js from frontend to backend
   2. create route for /api/products
9. Load Products From Backend
   1. add "proxy": "http://127.0.0.1:5000" in frontend package.json
   
10. Add redux to Home Screen to manage the state of the react application

11. Add Redux to Product Screen
   1. create product details constants, actions and reducers
12. Handle Add To Cart Button
   1. Handle Add To Cart in ProductScreen.js
   2. create CartScreen.js
13. Implement Add to Cart Action
   
14. Build Cart Screen
   
15. Implement Remove From Cart Action
   
16. Create Sample Users In MongoDB
   1. Installing mongoose
   2. npm install bcrypt for password security
   3. connect to mongodb
   
17. Create Sample Products In MongoDB
   
18. Create Sign-in Backend
   1. create /signin api
   2. check email and password
19. Design SignIn Screen
   1. create SigninScreen
   2. render email and password fields
   
20. Implement SignIn Action
   
21. Create Register Screen
   1. create API for /api/users/register
   2. insert new user to database
   3. return user info and token
   4. create RegisterScreen
   5. Add screen to App.js
   6. create register action and reducer
   7. check validation and create user
22. Create Shipping Screen
   1. create CheckoutSteps.js component
   2. create shipping fields
   3. implement shipping constant, actions and reducers
23. Create Payment Screen
   1. create payment fields
   2. implement shipping constant, actions and reducers
24. Design Place Order Screen
   1. design order summary fields
   2. design order action
25. Create Place Order API
   1. createOrder api
   2. create orderModel
   3. create orderRouter
   4. create post order route
26. Implement PlaceOrder Action
   1. handle place order button click
   2. create place order constants, action and reducer
27. Create Order Screen
   1. build order api for /api/orders/:id
   2. create OrderScreen.js
28. Order Payment step
29. Display Orders History
   1. create customer orders api
   2. create api for getMyOrders
   3. show orders in profile screen
30. show user information
31. Create Admin View and menu
32. Create product list for the admin
33. edit and update products for admin
34. Upload the image of the product for admin
35. Deleting products for admin
36. Create orderlist for the admin and show product on the screen
37. List users, edit or delete them
38. Implementing the seller's view
39. Create  Search Box and Search Screen
40. Adding advanced search with by price, by rating, and by average rating filters
41. Rate and give reviews on products