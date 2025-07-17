# Namaste react
#Namaste Food
/**
 * Header
 *  -Logo
 *  -Nav Items
 * Body
 *  -Search
 *  -RestaurantContainer
 *   -RestaurantCard
 *     -Img
 *     -Name of Res, Star Rating, cuisine, delery tie
 * Footer
 *  -Copright
 *  -Links
 *  -Address
 *  -Contact 
 */


Two types of Export/Import

-Default Export/Import

 export default Component;
 import Component from "path";

-Named Export/Import

 export const Component;
 import {Component} from "path";

 # React Hooks
 (Normal JS utility functions)
- useState() - Used to generate superpowerful state in react.
- useEffect()

# 2 types Routing in web apps
- Client Side Routing
- Server Side Routing

# Mounting
Constructor (dummy)
Render (dummy)
      <HTML Dummy>
Component Did Mount
       <API Call>
       <this.setState> -> State variable is updated

-----UPDATE
        render(API data)
        <HTML (new API data)>
        componentDid Update

# Redux Toolkit
- Install @reduxjs/toolkit and react-redux
- Build our store
- Connect our store to our app
- slice (cartSlice)
- dispatch(action)
- Selector

# Types of testing (developer)
-Unit Testing
-Integration Testing
-End to End Testing - e2e testing

# Setting up testing in our app
- Install React Testing Library
- Installed jest
- Installed Babel dependencies
- Configure Babel
- Configure Parcel Config file to disable babel traspilation
- npx create-jest
- Install jsdom library
- Install @babel/preset-react - to make JSX work in test cases
- Include @babel/preset-react inside my babel confige
- npm i -D @testing-library/jest-dom