# Online Store with admin panel using Express.js and mongoDB

You can access the admin panel in route: /admin  
super admin user is:  
email : admin@gunners.com  
pass: 123456

only logged in admins or super admin can access the admin panel.  
only super admins can access and edit in the users page in admin panel.

logging in route: /views/login.html or by clicking the user button in the home nav

# features

1- User can add to or remove from cart
2- User can search products by name
3- User can view product page by clicking on product card either in store or in search-box
4- Cart items are saved in local storage
5- User is authenticated before checking out
6- Payment is processed through stripe api
7- Store products can be filtered by price or category and can be sorted by price or name
8- admin can add,remove, or edit products in the admin dashboard
9- admin can search products from the admin dashboard
10- admin can keep track of sales through chart
