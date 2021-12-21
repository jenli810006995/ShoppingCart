# Django Project - Shopping Cart
#### Video Demo:  <https://youtu.be/I_03kLfnnZY>
#### Description:
  To create a website for e-shopping, such as Amazon or eBay. I used Django, JavaScript, and Python to build this website.
Under "store" app, I created 4 html pages - Main.html, store.html, cart.html and checkout.html. 

   ![image](https://user-images.githubusercontent.com/38231830/146858110-d0413b66-b019-4ddd-9ff2-504bba024685.png)

I created an administration account, to monitor what products, customers(authentication), and orders need to be added to the database.

   ![image](https://user-images.githubusercontent.com/38231830/146860204-3c46090a-6438-46d8-8333-efe9a27c9e4c.png)

When the user added items to the shopping cart, the terminal would print out the order id and quantity as below. 
However, on the admin page, the order history has not yet been built yet, and it is found that the payment method
has not built up completely yet. Hence, the admin cannot see when an order has been completed or not.
   ![image](https://user-images.githubusercontent.com/38231830/146858178-418c6d7c-069d-48ab-923c-f568b30e3bbd.png)

There are several features I have not managed to build or not successful. One is the number on the "cart" icon should have
been altered according to the number of items in the shopping cart. The reason why this failed was probably due to cart.js
code has not been created correctly. 

   ![image](https://user-images.githubusercontent.com/38231830/146856974-3e17f53f-f51c-4ae2-b7c9-acc404ce08c5.png)


The other problem is the shopping cart is failed to present a detailed list of the products for unauthorized users , which might be due to the settings of forms. 

> - Authorized User
    ![image](https://user-images.githubusercontent.com/38231830/146857350-3e9bf939-37e1-4b6c-96a8-653a3bab414a.png)

> - Unauthorized User
    ![image](https://user-images.githubusercontent.com/38231830/146857214-e3efa5ea-5c34-46cd-a6de-fe9da18ebbda.png)

Lastly, the "payment" button has not been ready yet. I built a function named "SubmitFormData" which should print out in console saying "Transaction 
completed." However, for some reasons, this feature has not built out succefully, might be due to JavaScript's CSRF-Token implementation. 

    ![image](https://user-images.githubusercontent.com/38231830/146859414-3b4aa850-6c13-4e88-8e29-a8103f6165cb.png)


In conclusion, "Shopping World" is my first Django project, and it has been a very inspiring and exciting experience. I would continue
exporing its power, adding Rest API and JavaScript, as well as advanced Python. Thanks to cs50 preparing me for all the foundations.
Hope one day I could be a front-end developer!
