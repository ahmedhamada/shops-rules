#==================   USER  ==================#


//register//


link:http://men3m.com/shops/users/register
method:post
parameters:
(email   pass   your_name   phone   city) *required
(fb   shop_place   shop_name   shop_details   shop_place_details)


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
parameters: no parameters required -- *required login


=======================


//fast login//


link:http://men3m.com/shops/users/login_fast/7
method:get
parameters: no parameters required -- you can instead of 7 put user id to login with


=======================


//list all users//


link:http://men3m.com/shops/users/list_users


=========================
