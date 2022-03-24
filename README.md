# food-ordering-app

## Project Proposal  

1. What goal will your website be designed to achieve?
    food-ordering-app for a business that sales healthy juices 
2. What kind of users will visit your site? In other words, what is the demographic of your users?
    Everyone looking for a healthy meal
3. What data do you plan on using? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain.

    - A Weather API from openweathermap.org - this will add to the app valuable information for the app user
    - Motivational quote App  - https://github.com/lukePeavey/quotable


4. In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). 
    - This is a food ordering app for a juices business. Customers can submit their order through out the app in the store. Similar to a self-checkout station. 
    - a nice feature in the app is that customers can sign up for a membrecy in the app and all customers with a membrecy they get 10% of the order every time they purchase at least $10 dollars or more. 
    - The app will allow the customer to enter their phone number to pull up their account in the system. So, there would be two options: sing up and sing in. 

            if (cusotmerChoice == singUp) sing up windows shows up
            if (customerChoice == singIn) The customer enter their phone number and if customer is found in the database, a greet statment shows up with the name of the customer at the top of the app. "Hello Liliana " 
    

Answer questions like the ones below, but feel free to add more information:  


    a. What does your database schema look like?  


        The customer has The following juice options

        - Cranberry-Pear Juice
        - Beet-Orange Juice (can’t believe I Ioved it!)
        - Strawberry Frappe
        - Mango-Pineapple Smoothie
        - Orange, Carrot and Celery Juice
        - Pineapple Coconut Milk
        - The Green Smoothie

        Also, they can make their own juice selecting from a list of ingridents available: fruits, veggies, liquid(type of milk, water), and nuts

        There is also a note box for the client to put special notes about how they want thier juice. 

    b. What kinds of issues might you run into with your API?
        ---
    c. Is there any sensitive information you need to secure?
        Yes, the phone number 
    d. What functionality will your app include?
    - Place an order
    - sign up/sing in
    - pay

    e. What will the user flow look like?

    start order button -> customer select what they want -> at the pay screen, they recive a notification about sing in/sing up -> if the customer chose to sign up they will get 20% off just for singing up. -> customer payment is sucessful - The app shows a custom message with the customer name: "Dear Liliana, we wish you a great day."

    f. What features make your site more than CRUD? Do you have any stretch
    goals?

        I think a nice feature in the app is the customer database which implies adding authentication to the app 



