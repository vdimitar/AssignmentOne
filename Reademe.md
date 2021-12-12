## Summary of the project

First, the aim of the project is to create a front-end web application and the requirement is to build a new web application for the student shop of Uclan (UNIVERSITY OF CENTRAL LANCASHIRE). On the first page, which is the home page, I provide a logo and 3 buttons, that are linked to the other pages. Also, on the body of the page, there are two videos, for the one I use the functionality of iframe, and the other is a standard video.



On the second page, I display all the products from the resources file using JavaScript and I provide two buttons, one for the description of the product and the other to be added to the card. The one- which is for the description uses session storage and the other uses local storage. If we press the button for the description of the products opens a new page with the name products and there includes a button for the product to be added to the cart. Moreover, I also include a top button which when you press it pops you to the top of the page.



The third page is the cart page which displays all the products which were selected from the product and products pages and there is a button that uses the functionality to clean the entire local storage.

## Home Page
The home page is the main page of the website, were you can see what the website does and some aditional infomation. There are marketing videos that are useful for our shop. 
On the home page you can see teh header which is the same as the rest of the pages there you can navigate to the different pages Product and Cart. On the footer you can see the information about the Student shop like location and link to the home page.

## Product Page


Inside the product page we can show more information of each product using `sessionstogare` which is a javascript functionality to get and store an item and be available only during the session, if we close the page the item will be cleared.
With this line of code `sessionStorage.selected = JSON.stringify(products[index]);` we populate the `sessionstorage` key `selecteditems` and then we are able to access it anywhere during the current session.

Another functionality we have is "Add to cart" which uses a `localstorage` functionality of the javascript programming language which stores an item in the local storage and it can be available all over the pages and display it, In our case we store the products the users wish to buy and they are displayed in the 
cart page. In order to clear that we need to call ``localstorage.clean()`` which clears the stored items. 



## Cart Page
