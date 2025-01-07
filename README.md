# ProductDetails
Subject of the  project :-
* Displaying the product details by adding products and we ccan edit the specific product details along with admin functionality *

1:- For Admin Login Functionality
a:- For admin login functionality I have created the login page with validations as we you put username and password correct it is automatically get redirect to products page by displaying all products includling one button to create the product and edit button in product list.
b:- If username and password is incorrect then it shows Invalid username and password alert comes 
c:- The correct Username and Password is:-(Username=admin,Password=admin@123)


2:- Product Form:-
a:- On click on create new product button the Product form gets opened with fields name,amount,description,Image(Optional) wirth create button such that Onclick the create button will create the product and form will get closed and redirect to previous page in whcih in product list the product gets add.there are validations for product form.

3:- Edit Product:- 
a:- There is edit link button in display product list, as when you click on that link button the edit Product Form gets opened by fetching the previous details of product.In This you can change the product details and update.
b:- On Edit click the product gets updated and edit form get closed and redirect to previous page with updated details in product list.

4:- Search Facilility:-
a:- As for this above the list we have given 3 options name,amount,description to filter product details based on this 3 filters. When you put some name or amount or description or all 3 options and click on filter button then on filter button click based on criteria the product get filter

5:- Product Pagination:-
a:- As i have added pagination for the product details as on each page i ahve set PageSize=2 ssuch that on each page 2 product will get displayed.


6:- Api Creation for Product Details:-
a:- As in code I have created one ProductApiController To create api for products as we can hit this api on any frontend framework to display the details of product.










