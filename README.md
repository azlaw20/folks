# folks
An e-commerce app built on MERN stack (MongoDB, Express, React and Node) with Stripe Checkout to handle payments. 
Just testing my skills,for details,  
Please checkout: 
https://github.com/shubham1710/MERN-E-Commerce
an e-commerce app built on MERN stack (MongoDB, Express, React and Node) with Stripe Checkout to handle payments.

Features present in the app :-

1. Authentication using JSON Web Tokens (JWT).
2. Option to add, edit, view and delete all the items in our store.
3. Option to add items or remove items from the cart for the user.
4. Display the total bill of the cart and update it as soon as the cart is updated by the user.
5. Using Local Storage to store the JWT so that we only allow logged-in users to buy items.
6. Option to pay using Stripe Checkout and thus creating a new order and emptying the cart after payment is successful.
7. Option to view all your past orders along with the bill amount for each.
---
# Install

**Backend**

1.  **Configure default configs**. In `config/default.json`, set your variables.

	1. `dbUrl`: It can be set as `mongodb://localhost/MernECommerce`.
NOTE: This is very basic, one without any username and password. This can be configured as per your requirement.
  2. `jwtsecret`: This is the key used sign jwt tokens. It can be set as `dummySecret`.
  3. `StripeAPIKey`: Create your account here [register](https://dashboard.stripe.com/register).
2. Install dependencies with `npm i`.
3. Server will start running on [port 4000](http://localhost:4000).
  16  client/README.md 
@@ -68,3 +68,19 @@ This section has moved here: [https://facebook.github.io/create-react-app/docs/d
### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


# Install
**Client**
1. Go into `client` and install dependencies with `npm i`. 
2. Run the client with `npm run start`. 
3. Install redux dev tools for your browser. Same for firefox can be found here [here](https://addons.mozilla.org/en-US/firefox/addon/reduxdevtools/).
Client app will start running on [http://localhost:3000](http://localhost:3000).

# Running the client
(Make sure the server is running on port 4000).
1. Register a user using [register](http://localhost:3000/home).
2. Add a new item on the next page. i.e. [add item](http://localhost:3000/addItem).
3. Go to home and you can see all the items that you added.
4. Add an item to the cart. 
5. Go to [cart](http://localhost:3000/cart) to checkout your products.

