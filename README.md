# DripStore
Drip is an eCommerence web application developed by 4 software engineers following the client's business requirements document. This project is a foray into real development work - building key components of a complex whole and integrating those with the rest of the system. This project was divided into four different components: 
> Product Overview, Related Products, Questions & Answers, Ratings & Reviews.

## Table of Contents ##
* [Libraries/Tools](#librariestools "Goto librariestools")
* [Getting Started](#getting-started "Goto getting-started")
* [Product Overview](#product-overview "Goto product-overview")
* [Related Products](#related-products "Goto related-products")
* [Questions and Answers](#questions--answers "Goto questions--answers")
* [Ratings and Reviews](#ratings--reviews "Goto ratings--reviews")

## Libraries/Tools ##
* ReactJS
  * Material-UI
* ES6
* Express
* Firebase
* Enzyme
* Jest
* Webpack
* Babel

## Getting Started ##
1. NPM installations of dependencies
      ``` 
      npm install 
      ```
3. Build the application
      ```
      npm run build 
      ```
4. Generate a API token and follow the directions inside ```config.example.js```
    * __Reminder:__ _API TOKEN MUST BE HIDDEN_
5. Start the application
      ``` 
      npm run start 
      ```
7. Navigate to ```http://localhost:8008```

## Product Overview ##
Product Overview is a component that guides the user through selecting a specific style and size to add to their cart. It displays star ratings, price/sales price, product's title/description, category, slogan, and image. Below the description, the user can browse through the circular tuhmbnails to select various styles for the product. Below the style selector, there are two dropdown lists that contain size and quantity (_please note: if the quantity is out of stock, size won't show up_). The add cart button is disabled if there is nothing in stock, and if the user does not select a size or quantity the size dropdown will automatically drop down for the user to make a selection. The image gallery displays thumbnails of rows of 7 and is able to navigate the default view with the arrow buttons or clicking a specific thumbnail. When the default image is clicked, another window will pop up of the image with fullscreen view. When clicking it, the image will be zoomed in by 250%, and clicking it again will return it to 100%. 

## Related Products ##

## Questions & Answers ##

## Ratings & Reviews ##
