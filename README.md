# restaurant-menu    ![npm](https://img.shields.io/npm/v/restaurant-menu.svg?label=restaurant-menu)
Basically it is restaurant menu api. It contain more than **300** items with its price               

# Installation   
Either through cloning with [git](https://github.com/Chougle-saud/restaurant-menu.git) or by using [npm](http://npmjs.org) (the recommended way):

```bash
npm install restaurant-menu
```

# Usage

```bash
   [
      {
        "name": "VEG SOUP",
        "items": [
          "Sweet Corn Soup",
          "Manchow Soup",
          "Clear Soup",
          "Hot & Sour Soup",
          "Cream of Tomato Soup",
          "Veg Noodles Soup",
          "Veg Lemon Coriander Soup"
        ],
        "price": [90, 100, 80, 100, 80, 100, 130]
      }
   ]
```
example:
```bash

   const menu = require("restaurant-menu");
   
   console.log(menu[0].name);   // it will return "VEG SOUP"
   console.log(menu[0].items);  // it will return [ 'Sweet Corn Soup','Manchow Soup','Clear Soup','Hot & Sour Soup','Cream of Tomato Soup','Veg Noodles Soup','Veg Lemon Coriander Soup' ]
   
   console.log(menu[0].price);  // it will return [ 90, 100, 80, 100, 80, 100, 130 ]
   
   // similarly you can get remaining objects.
   
```
