
<h2> eMenu | “Changing the Way the Order is taken” </h2>

<h6>It is a Real-Time Order placement, monitoring and management system.</span></h6>    
 
<h3>What is Change?</h3>
<span>Feel a new touch of technology ‘place your food-order yourself’. No more wait for ‘Waiter’ to take your order.</span>


<h3>Real-Time Attraction</h3>
o	Here order is done on device there it is received on the kitchen-dashboard and saved in cloud database.
o	Items can be removed (in case of not available today, no more running, or short of today)
o	Items can be added (in case of new flavor or previously removed is available now)
o	Items can be updated (name and price)

The all above scenarios are handled real-time say device is in customer’s hand and she is now ordering some of pizza flavors (management is changing mango-shake price in same time) and now she is swapping to shake category she will find new price ‘how cool isn’t it?’ Manage from ‘One place’.

<h3>Order Types</h3>


-	Unplaced Order  
      --  Order which is not yet placed (neither sent to kitchen nor saved in database).
-	Live Order  
      --  Order which has been placed (might be it is served) but not billed yet.
-	Closed Order  
      --  Order which is billed it is closed by waiter who placed it.

<h3>Roles in Application</h3>
o	Waiter  
    •	This actor(windows8 device) will login with credentials provided by Admin, it handles orders   
    •	place new order 
    •	edit order  
    •	add or cancel items in unplaced order or ‘Live Order’   

o	Admin 
    •	This role has power to create new accounts for waiters  
    •	To add or remove items to different categories  
    •	To edit or update price of existing items 
    
o	Kitchen 
    •	Kitchen is provided with a Dash-board where orders are shown with time-stamp  
    •	Kitchen is also synced when a ‘Live Order’ is updated 

o	Owner 
    •	This account is indented to show sell-summary of whole day.   

<h3>Screens</h3>
o	Login Screen  
    •	Default Logo  
    •	This page will be containing two fields for username and password respectively, and a button to login. After login user will be navigated to corresponding page.  
    •	Next page will be role dependent for example Owner, Kitchen, Waiter or Admin. 



o	Menu Screen 

  

o My-Order Screen  


o Edit My-Order Screen  
 
<h3>Target Machine</h3>
Windows 8 Surface, Android Tablets, iPad, iPhone, Android Smartphones, Windows Phone 8.

<h3>Target OS and Technologies and Services</h3>
Windows 8 (Microsoft’s latest OS for Tablets/Touch based Devices), Cloud Databases, SAAS, also Server Instance on Cloud Service Provider like Windows Azure/Heroku/Nodester, WNS/WebSocket for communication.

<h3>What Next?</h3>
After this next attempt will be to try to clone UI for website to facilitate ‘Take Away’ and ‘Delivery’ services
“Changing the Way the Order is taken”.
