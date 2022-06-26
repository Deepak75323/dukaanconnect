# dukaanconnect
🚀 Project: सब local
सब local is a web app developed for connecting local shops to their regular customers by online
mode and thus also maintaining social distancing, here shops can ask for a donation if they really 
need some financial help, shops can also put up advertisements for offers on the website.

🎯 Final prototye of project:
The final prototype of our project is able to perform these actions.
1. Login/Register a new user as a customer.
2. Login/Register a new user as a shop owner.
3. Shop owner can add his/her shop to our website.
4. Donation feature for shops who need donation.
5. Customers will be able to see local shops and number of people in the queue at the shop.
   For performing this filter process customer will have to follow these three steps.
   a) First filter on the basis of pincode.
   b) Second filter on the basis of area/locality.
   c) Third filter on the basis of shop name.
6. Customer will be able to add himself to queue at any shop with his list of goodies needed by registering through his phone number.
7. Customer will receive notification via sms on his registered phone number about his posion in the queue and his expected time to visit the shop.
8. Shop owner will be able to mention offer or other details obout his shop on his shop's dashboard which will be visible to the customers.
9. Shop owner will be able to modify queue on the basis of FIFO (First in first out algorithm).


💻 Tech used:
1. Node.js
2. Express.js
3. SMS API (fast2sms)
4. HTML
5. CSS
6. Javascript
7. Mongodb
8. Passport

📋 Work-flow:
This is the logical order we followed for building our webapp- 

General:
Local-server -> Landing page -> Basic-info on landing page -> Login/Sign up feature ->
Donation, Add Shop and Shop now feature

From customers perspective:
Search box for pincode filter -> Drop down for areas under the pincode -> Display Shops list in that area(pincode) ->
Display dashboard of selected Shop -> Adding himself/herself to queue -> Successful page

From shop owners perspective:
Shop owner's dash board -> About shop, this can be edited by shop owner -> Deque feature -> Message to customer feature

📌 Note:
a) If you want to receive messages after adding yourself to queue, use your original phone number during queue addition.
b) Message facility will be available from 9 AM to 9 PM.

🛠️ Installation:
1. Cloning repository.
      git clone <repo link> or locally download zip folder.
      
2. Install all dependencies.
      npm install ...
      
3. Set all enviorement variables in .env file.
      mongodburl=<MONGODB URI>
      API_KEY=<SMS API key>
   
4. Run web-app on local host.
      node server (entry js file)
