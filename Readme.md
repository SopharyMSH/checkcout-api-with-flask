# Checkout API - Flask
	This is the sample code for integrating checkout API with Python/Flask.
## Requirements
		•	flask - Flask core framework
		•	faker - Fake name, email, address etc.
		•	requests - Connect to API server
## Integration Step
		### 1.	Merchant Registration
				To integrate with Bill 24, you must register as a merchant in Bill 24 by create an account with Bill 24 web application.
				Bill 24 Web Application Address: https://demo.bill24.net
					1.	Click on [បង្កើតគណនី] or [Create an account]
 
							![alt text](https://s3-ap-southeast-1.amazonaws.com/b24.web-user/screens/Sign_up_01.jpg)
							
					2.	Click on [បង្កើតក្រុមហ៊ុន] or [Create Company]
					
 						![alt text](https://s3-ap-southeast-1.amazonaws.com/b24.web-user/screens/Create+Company.jpg)
							
		### 2.  API Token
						Every merchant has their own token auto generated by Bill 24, with this token you can use to integrate your ecommerce website with Bill 24.
						
 					![alt text](https://s3-ap-southeast-1.amazonaws.com/b24.web-user/screens/api_token.jpg)
						
						#### 1.	Allow WebAPI Client to access our Checkout API
						#### 2.	Merchant can allow customer to pay later via bank agency, Bank App or Pay on Web Aagain.
						#### 3.	Enable Push Back for payment transaction to get data when customer pay by pay later feature.

		### 3. API Authorization
						To access the API, please use your API token from previous step to authorize with the API.
						API Address: https://checkoutapi-demo.bill24.net
 					![alt text](https://s3-ap-southeast-1.amazonaws.com/b24.web-user/screens/api_authorization.jpg)
