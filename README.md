#=======================   USER  =======================#


//register//


link:http://men3m.com/shops/users/register
method:post
parameters:
(email   pass   your_name   phone   city) *required
(fb   whatsapp   shop_place   shop_name   shop_details   shop_place_details )


=======================


//login//


link:http://men3m.com/shops/users/login
method:post
parameters:
(user   pass)


=======================


//logout//


link:http://men3m.com/shops/users/logout
method:get
parameters:no parameters


=======================


//get all user info//


link:http://men3m.com/shops/users
method:get
parameters: no parameters required -- * required login


=======================


//fast login//


link:http://men3m.com/shops/users/login_fast/7
method:get
parameters: no parameters required -- you can instead of 7 put user id to login with


=======================


//list all users//


link:http://men3m.com/shops/users/list_users


=========================


#=======================   product  =======================#


//get all products without any pagination

link:http://men3m.com/shops/product/all_products_no_pagination
method:get
parameters: no parameters required


==============================


//get all products with pagination

link:http://men3m.com/shops/product/all_products_with_pagination
method:get
parameters:
page ==> page number *required
products_per_page => number of products per page   *not required default 10

[ * ] attention
you can use link:http://men3m.com/shops/product/count_all_products
to use in paggination
it return the number of all products

==============================


//get one products

link:http://men3m.com/shops/product/single_product/5
method:get
parameters:
in the link (5)

==============================


//create product

*must be logged in

link:http://men3m.com/shops/product/create
method:post
parameters:
p_name
p_details
categ_id
quantity
price
sale  [ * ]can be empty


* use this lisk to test the function ==>> link:http://men3m.com/shops/product/upload
==============================


//delete product temprary

link:http://men3m.com/shops/product/delete_product_temprary/5
method:get
parameters:
in the link (5)


* you must log in

==============================



//delete product permanentely - it will remove the row with picture

link:http://men3m.com/shops/product/delete_product_permanently/5
method:get
parameters:
in the link (5)


* you must log in

==============================

//update the product


link:http://men3m.com/shops/product/update_product
method:post
parameters:

p_name
p_details
categ_id
quantity
price
sale  *can be empty


[ * ] Attention ==>> not test be me

=============================
