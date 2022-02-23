#Contents
1. WHY DO WE NEED TRACE?<br/>
        - 1.1 Why Do We Need Trace?<br/>
        - 1.2 What is TRACE?<br/>
	        - 1.2.1 FUNCTIONALITIES OF TRACE<br/>
	- 1.3 Why build or integrate TRACE into your dApp?
2. TRACE API REFERENCE<br/>
	- 2.1. STEPS FOR SIGNUP<br/>
	- 2.2. USER AUTHENTICATION API<br/>
	- 2.3. TRANSFER RECORDS<br/>
	- 2.4. TRANSFER VOUCHER TOKEN<br/>	
	- 2.5  FIND YOUR TRANSACTIONS ON TEST NET<br/>
3. PRODUCT DEVELOPED USING TRACE PROTOCOL - "mFish"
 	- 3.1 mFish REFERENCE
 		- 3.1.1 USER AUTHENTICATION API<br/>
 		- 3.1.2 TRANSFER RECORDS<br/>
 		- 3.1.3 Settings
	- A. PROFILE INFORMATION<br/>
	- B. TRANSACTION LOG<br/>
		- I. DEBIT TRANSACTION LOGS OF USER<br/>
		- II. CREDIT TRANSACTION LOGS OF USER<br/>
	- C. INVITES MANAGEMENT<br/>
		- I. SEND AN INVITE<br/>
		- II. ACCEPT AN INVITE<br/>
		- III. REJECT AN INVITE<br/>
		- IV. FETCH SENT INVITES<br/>
		- V. RECEIVED INVITES<br/>
	


**1.	WHY DO WE NEED TRACE & WHAT IS IT?**<br/>

-**1.1	Why Do We Need Trace?**<br/>
        Traceability is the ability to trace back to where a product came from, and, if applicable, where the product’s ingredients/components were sourced from. It is important to do so to ensure that the products we use and consume are safe, authentic and have been produced in a legal, sustainable, and responsible manner. In the case of seafood supply chains, traceability is important because more than one third of global production is said to be illegal, unreported or unregulated (IUU), up to 80% of certain species groups can be mislabelled, the seafood may contain natural toxins, man-made contaminants, or be unsafe to consume due poor cold chain and bacterial contamination. In addition, most fish stocks are at levels of maximum exploitation or are overfished, and modern day slavery can be prevalent.  These are major risks for companies and for the future or the industry, as well as risks for governments and our food security.
Although traceability can be achieved through pencil and paper or simple spreadsheets, records can be duplicated or falsified and thus these methods do not build trust within a supply chain. Specific traceability systems exist but they are often built for intra-company, one-up one-down traceability, they are proprietary, and they can be difficult to use and expensive. Further, with upwards of 90% of global seafood production and the industry’s workforce based out of and in developing nations, these systems are often not accessible to those at the first mile of seafood supply chains. Even if a fisher or fish farmer could pay and use a system, there is no clear return on investment, and so we lack traceability. In fact a study commissioned by Standard Chartered Bank found that only 6% of firms have visibility through their supply chains. Why is that concern and why would a bank commission such a study? Well without traceability, the risk for finance and insurance is too high, and we are stuck in a world where, for the most part, we are unable to identify, verify, and reward legal and responsible production for the vast majority of our produce like seafood. 
That is why Eachmile Technologies designed and built the Trace Protocol. A protocol that in the case of seafood allows developers to build or integrate into decentralised applications a token called Fishcoin. The token can be used as an incentive for the sharing and recording of data in an immutable way that builds trust and provides traceability. It can be integrated into any  blockchain operating system, allows for the market to work out the value of the data, and provides a mechanism by which the market can reward the fishers, farmers and other supply chain actors in developing nations when they redeem the tokens for mobile air-time top ups and other services in the future.


**1.2 What is TRACE?**<br/>
TRACE is an Application Programming Interface (API) that facilitates shared functionality and data transfer between applications via a documented interface.  Specifically the transfer of traceability data between stakeholders in a supply chain such as producers and intermediaries such as aggregators, processors, wholesalers, through to retailers. 

- **1.2.1 Functionalities of TRACE**<br/>
There are two main user roles in the TRACE system - the producer and the trader. In the case of the seafood industry there are two main producers -  a fisher or a fish farmer. When registering and signing up to the application for the first time, it is mandatory for the user to choose between one of these three industry roles - either a fisher, a farmer, or a trader. After successful sign up, only the producers (fishers or farmers) can create a new data record for sharing to either another producer or to a trader. A producer can sometimes sell their produce to another producer but a trader can only receive produce from a producer, and therefore the trader cannot create a new data record of a catch or harvest event. 

Upon signing up, a user enters profile data. This is identity data such as an individual’s name or company name, the name of the fishing vessel if a fisher, or the name of the farm if a farmer etc. This static or fixed data, forms part of what are known as Key Data Elements (KDEs) for traceability and auto-fills for each new data record. Dynamic data elements refers to data that may change for each new data record, and for a fisher this may be the port of departure, the date departed, the port of landing, the species of fish, the weight of the fish etc. For a farmer it may be the pond number, the size category and weight of the harvest etc.   

When a producer has filled in the dynamic traceability KDEs related to a harvest of seafood that he/she is selling to a trader, he/she then negotiates on the amount of Fishcoin tokens that he/she wants for the data. As an example, if a fisher is selling $1,000 worth of seafood he or she may ask for 5% of the value of the fish - thus $50. The trader may counter with 1% ($10), they then may meet in the middle and agree on $25 (2.5%) - the equivalent of 25 Fishcoin tokens. The producer then enters 25 tokens and transfers the data record to the trader. The trader accepts and the data transfer is recorded on the blockchain. 

As producers and traders may buy produce from numerous other producers, both user types can create linked records. For example the same trader buys $1,500 and $500 worth of fish from two other fishers, negotiates the same rate (2.5%) and has paid $75 (75 Fishcoin tokens). The trader then sells all fish from these three fishers to one buyer, the trader can select each record from the three fishers and transfer the combined quantity (with three hash codes) in one record to the buyer, and may receive $100 worth of tokens for the data that he/she paid $75 for. 

The Fishcoin tokens can be redeemed for air-time mobile top ups in over 150 countries with over 500 mobile operators. In the near future the tokens will be able to be redeemed for other vouchers that can be redeemed at convenience stores, coffee shops, or to pay for utilities such as water or electricity. 



- **1.3 Why build or integrate TRACE into your dApp?**<br/>
Every transaction made on a TRACE integrated dApp incurs a commission. In the case of Fishcoin token transactions, which are valued at 1USD per 1 Fishcoin, a 5% commission is deducted and the developer of the Fishcoin enabled dApp will receive 50% of the commission value. These tokens will be sent to the digital wallet of the developer and are redeemable for services similar to how a fisher or a farmer would redeem the tokens on the application, or for batch transfers to Eachmile for the transfer of fiat currency into the developer’s bank account.* 

 <p align="center">
  <img src="../Trace.png" width="350" title="hover text">
  </p>
  
Only Producers can add new transfer records while traders can add linked records. Producers enter the product information whilst their own profile information auto-populates. In product information, information such a production unit id (e.g. farm name for farmers or vessel name for fishers), harvest details such as the data of harvest or dates departed/landed, the location, the species and quantities are to be entered. To send this product information, the receiver must first have downloaded the application, and be a contact within the application itself . The receiver will be able to receive the data and check his newly received data with provision of accepting and rejecting the product. 
 
If user rejects any product then all details of such product get erased from the system. For accepted product, certain number of tokens gets transferred to sender's account and the details are then written on public blockchain Stellar with the help of smart contract. All the transactional records are maintained on blockchain. 
 
To utilize the received tokens, another functionality called recharge utility is provided. Because of this function Grower, Consumer and Trader are able to use those received utility tokens for various recharge services like mobile, TV, broadband, electricity and many more utility bill payments. 

 **2 TRACE API reference**<br/>
Welcome to the TRACE API reference.
This API serves as the primary gateway to facilitate digital values transfer through TRACE.
Links to access<br/>
	-[TRACE Website](http://52.163.83.160:7771)<br/>
	-[TRACE Firebase Swagger](http://52.163.83.160:7772/API-docs)<br/>
	-[TRACE Blockchain Swagger](http://52.163.83.160:7773/API-docs/#/)<br/>
	
- **2.1 Steps for Signup**<br/>
1. Signup by [clicking here](http://52.163.83.160:7771)
2. User has to Sign up from portal using valid email address and select anyone of the three roles. (Fisher, Farmer, Trader).
  <p align="center">
  <img src="../signup.png" width="700" height="400" title="hover text">
  </p>
3. A verification email will be sent to the registered email address<br/>
4. Verify the email address received at the registered email address
  <p align="center">
  <img src="../verification-link.png" width="700" height="400" title="hover text">
  </p>
5. Login to activate your account and add user profile details.
 <p align="center">
  <img src="../signin.png" width="700" height="400" title="hover text">
  </p>


- **2.2	User Authentication API**<br/>
Once the initial signup and verification process is done, you can use this API to fetch the user details. UserID is the value that will be used to uniquely identify the user and also will be required as a base for all the user related operations. 

API: UserAuthentication<br/>
Endpoint:cmxAPI/firebase/userAuthentication<br/>
Request Body Parameters:<br/>

Parameter | Data type | Required
----------|-----------|---------
email     |   String  |   Yes
password  |   String  |   Yes

Sample Request Body:{
  "email": "rem@yopmail.com",
  "password": "Abc@123"
}

- **2.3 Transfer Records**<br/>
There are multiple API’s that can be consumed for fetching details of records, below is the list provided with it’s use, API end points and parameters.
	- **2.3.1. Fetching sent records**<br/>
This API will fetch all the records that are sent by user to fishers, farmers and traders along with status of records.<br/>
Endpoint:cmxAPI/firebase/getSentRecordsByUser<br/>
Request Body Parameters:<br/>

	Parameter | Data type | Required
	--------- |-----------|---------
	userId    |  String   | Yes

Sample Request Body:{
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

- **2.3.2 Fetching received records.**<br/>
This API will fetch all the records that are received by user from fisher, farmer, trader along with status of records.<br/>
Endpoint:cmxAPI/firebase/getReceivedRecordsByUser<br/>
Request Body Parameters:<br/>

	Parameter | Data type | Required
	--------- |-----------|---------
	userId    |  String   | Yes

Sample Request Body: {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

- **2.3.3 Fetching country list.**<br/>
Used to fetch all the countries with country code.<br/>
Endpoint:cmxAPI/firebase/getCountryList<br/>
Method:GET<br/>


**2.4 Transfer Voucher Tokens**<br/>
- **a. Get Wallet balance**<br/>
To fetch Stellar wallet balance<br/>
API: /AccountDetails<br/>
Request Body:<br/>

	Parameter | Data type | Required/Default
	--------- | --------- | --------
	accountId | String | Yes

Sample Request Body: {
  "accountId":"GDC33CQDL7U3YI4MI2MFLRM7JP62TXDKBIWI4UXH2H27BOCAMJZSZZN3" 
}

- **b. Transfer Voucher Tokens**<br/>
This API is used to transfer Voucher token assets from one account to another<br/>
API: /transferVoucherTokenAssets<br/>
Request Body:<br/>

	Parameter | Data type | Required/Default
	--------- | --------- | --------
	srcAcct | String | Yes
	srcSeed | String | Yes
	srcUserID | String | Yes
	destAcct | String | Yes
	destSeed | String | Yes
	destUserID | String | Yes
	Amount | float | Yes
	
Sample Request Body:
{
  "srcAcct":"GATSU64WOJDOGUMLKZP5FUJL32QM6WX5PLH4YRKK3ROWMCFPZ7RCKPI2",
  "srcSeed":"U2FsdGVkX1+8FNQyvOaMCZvl2R1raM6/SHLfTiUvwWeiOsV7NqRe8i3C6Joei1DTrK7DcbALVjk3d90FT+YMwUYFp2bEmyrC9Gf7SAmOxXM=",
  "srcUserID":"Vkb6O6ZfLyQS1cLRbcnXJc4QnMp1",
  "destAcct":"GAVAUZFXKZMZMXS3CTZF34AX4IHQMEYJK55CNJ4M75MV25LDTADXJUJQ",
  "destSeed":"U2FsdGVkX1+nBSNFrJPVu17q7IlIVcR4ub7wNr7q7BXfnsAUSlY27EiW3rqGpIeiiyDOdbBzmfZsHWsughR/CxlvurGPWGS7YwduuiK9keM=",
  "destUserID": "52QqKTpme1VAMZgsqSycLMhuTpd2",
  "amount": 0.1
}


**c.Write Data on Blockchain**<br/>
This API is used to write IPFS hash on the stellar blockchain, it returns the Stellar Transaction Hash

This API is used to transfer Voucher token assets to merchant and developer account from user account. For the feature developed by the developer, the developer would be getting a 50% cut of merchant fees. The developer can get the details required for the fee transfer through the account details API. The below mentioned fields would be required for successful transfer of fees.
You can get the below values from User Authentication API (2.2) above.
developerWalletID : The Public key assigned on Account creation.
developerWalletSecretKey: The secret key field.
developerUserID: User ID of developer.

API: /writeDataOnBlockchain<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
jsonData | String | Yes
destAcct | String | Yes
destSeed | String | Yes
destUserID | String | Yes
srcAcct | String | Yes
srcSeed | String | Yes
srcUserID | String | Yes
amount | float | Yes
burnAmount | String | No
developerWalletID |String|No
developerWalletSecretKey|String|No
developerUserID|String|No


Sample Request Body: {
  "jsonData":"{\"AddAndLocOfFarm\":\"Satpur\",\"ArrivalDate\":\"2021-10-29T12:04:23.242+05:30\",\"ArrivalPort\":\"\",\"Country\":\"India\",\"CreatedDate\":\"10 29 2021 12:04:54\",\"CultureUnitID\":\"axa\",\"CultureUnitLocation\":\"EWR\",\"DeparturePort\":\"\",\"voucherTokenAssets\":1,\"IsDeleted\":false,\"LicenseAndPermitNumber\":\"ABZ897654\",\"NameOfFarmAndCompany\":\"Winjit\",\"RecdRole\":\"Farmer\",\"RecdUId\":\"Vkb6O6ZfLyQS1cLRbcnXJc4QnMp1\",\"ReceiverName\":\"Remith Test\",\"SenderName\":\"Remith UAT\",\"SentUId\":\"52QqKTpme1VAMZgsqSycLMhuTpd2\",\"Species\":[{\"AdditionalInfo\":[{\"name\":\"\",\"value\":\"\"}],\"AvailableQty\":1,\"LinkID\":\"\",\"ParentID\":\"-Mn9kXxpm2Ef9MSk2CM3\",\"SpeciesId\":\"tt4ymk\",\"SpeciesName\":\"Carp - Common\",\"SpeciesQty\":1,\"otherSpec\":\"\"}],\"Status\":\"Pending\",\"TxnHash\":\"\",\"TxnLinkID\":\"-Mn9kXxpm2Ef9MSk2CM3\",\"TxnStep\":0,\"UserName\":\"Remith UAT\",\"additionalInfo\":[{\"name\":\"\",\"value\":\"\"}],\"isRead\":false,\"key\":\"-Mn9kYH_aUOenodB3Zu7\"}",
  "destAcct": "GAVAUZFXKZMZMXS3CTZF34AX4IHQMEYJK55CNJ4M75MV25LDTADXJUJQ",
  "destSeed":"U2FsdGVkX1+nBSNFrJPVu17q7IlIVcR4ub7wNr7q7BXfnsAUSlY27EiW3rqGpIeiiyDOdbBzmfZsHWsughR/CxlvurGPWGS7YwduuiK9keM=",
  "destUserID":"52QqKTpme1VAMZgsqSycLMhuTpd2",
  "srcAcct":"GATSU64WOJDOGUMLKZP5FUJL32QM6WX5PLH4YRKK3ROWMCFPZ7RCKPI2",
  "srcSeed":"U2FsdGVkX1+8FNQyvOaMCZvl2R1raM6/SHLfTiUvwWeiOsV7NqRe8i3C6Joei1DTrK7DcbALVjk3d90FT+YMwUYFp2bEmyrC9Gf7SAmOxXM=",
  "srcUserID": "Vkb6O6ZfLyQS1cLRbcnXJc4QnMp1",
  "amount": 1,
  "burnAmount":"1",
  "developerWalletID":"GAL4XW2WEFWM2WQYQASQBO5LOZPSLNBSSVWI5GYB2ZUZKHVAUFVKVQ22", "developerWalletSecretKey":"U2FsdGVkX1+fZQy9ogomAWZiEh2a6sMem0ZLnM+jvbisvOQTg4MtXhyxFRHBi33sha5PsAQUugBjeumseAhjMiujMTxodWki19ZzHQw/SOc=", "developerUserID":"prdCzwt9mBSBadXT6VfMZuqAVip2"
}

**2.5 Find your transactions on test net.**<br/>
- a.Fetch the transaction hash from the transaction and go to Stellar test net URL to find details.<br/>
	http://testnet.stellarchain.io/tx/txn_hash_here<br/>
Example:<br/>
	hash= ffa62016e1c20e5042ca59c2979545e20f6fa02de36824286515e12dd5e6abf9<br/>
Then below is the blockchain tracking URL-<br/>
	http://testnet.stellarchain.io/tx/ffa62016e1c20e5042ca59c2979545e20f6fa02de36824286515e12dd5e6abf9<br/>

**3.0 Product developed using Trace protocol**<br/>
- Fish and other sea food products are harvested, processed by farmers and then sold to local suppliers. They provide these to region suppliers who in turn sells it to the customers. But the industry is often unsustainable, illegal and inefficient.
To tackle these problems, a system was developed to check traceability and quality maintenance using Blockchain technology. All the data was shared seamlessly using a Blockchain. A mobile + Web application was designed to capture data from fisherman. 
In this project we developed and integrated TRACE API which serves as the primary gateway to facilitate digital values transfer.
Therefore the Grower here is the Fisher, consumer here is the Farmer and Trader stays the same. The voucher tokens in this app is called as Fishcoins. We also integrated the DTone services for airtime topups and other value added services. The purchasing of fishcoin was done using the payment gateway Paypal. The app is live on [Web](https://mfish-trace.co/), [Android](https://play.google.com/store/apps/details?id=com.eachmile.fishcoin) and [iOS](https://apps.apple.com/us/app/mfish/id1488081510).

Benefits for client after developing and integrating TRACE system <br/>
- Precise information about seafood product was available to end user.
- Exchange of digital currency from one person to another.
- Effective tracking of the seafood products in global supply chain.
- Reward mechanism for every user role in terms of tokens.
- Through the system the client witnessed a hike in record collection.

	- 3.1 mFish reference
 
- **3.1.1	User Authentication API**<br/>
Once the initial signup and verification process is done, you can use this API to fetch the user details. UserID is the value that will be used to uniquely identify the user and also will be required as a base for all the user related operations. 

API: UserAuthentication<br/>
Endpoint:cmxAPI/firebase/userAuthentication<br/>
Request Body Parameters:<br/>

Parameter | Data type | Required
----------|-----------|---------
email     |   String  |   Yes
password  |   String  |   Yes

Sample Request Body:{
  "email": "rem@yopmail.com",
  "password": "Abc@123"
}

- **3.1.2 Transfer Records**<br/>
There are multiple API’s that can be consumed for fetching details of records, below is the list provided with it’s use, API end points and parameters.
	- **1. Fetching sent records**<br/>
This API will fetch all the records that are sent by user to fisher, farmer, trader along with status of records.<br/>
Endpoint:cmxAPI/firebase/getSentRecordsByUser<br/>
Request Body Parameters:<br/>

	Parameter | Data type | Required
	--------- |-----------|---------
	userId    |  String   | Yes

Sample Request Body:{
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

- **2. Fetching received records.**<br/>
This API will fetch all the records that are received by user from fisher, farmer, trader along with status of records.<br/>
Endpoint:cmxAPI/firebase/getReceivedRecordsByUser<br/>
Request Body Parameters:<br/>

	Parameter | Data type | Required
	--------- |-----------|---------
	userId    |  String   | Yes

Sample Request Body: {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

- **3 Fetching country list.**<br/>
Used to fetch all the countries with country code.<br/>
Endpoint:cmxAPI/firebase/getCountryList<br/>
Method:GET<br/>

- **4 Get Major Fishing Area.**<br/>
Used to fetch the Fishing Area for Fisher, Farmer<br/>
Endpoint: cmxAPI/firebase/getFAOMajorFishingArea<br/>
Method: GET<br/>

- **5 Get Fishing gear.**<br/>
Used to fetch different types of fishing gears available<br/>
Endpoint:cmxAPI/firebase/getFishingGear<br/>
Method:GET<br/>

- **6 Get Margin Amount.**<br/>
Marging amount for merchant transactions<br/>
Endpoint:cmxAPI/firebase/getMarginAmount<br/>
Method: GET<br/>

- **7. Sending a record.**<br/>
A user can send a record to Fisher Farmer or Trader. The request body will change as per the role of the sender.<br/>
Endpoint:cmxAPI/firebase/getReceivedRecordsByUser<br/>

Request Body:<br/>
- a. Fisher:<br/>

	Parameter | Data type | Required
	--------- | --------- | --------
	ArrivalPort | String | No
	DeparturePort | String | No
	DepartureDate | String | Yes
	ArrivalDate | String | Yes
	CultureUnitLocation | String | No
	CultureUnitID | String | No
	RecdRole | String | Yes
	Status | String | Yes
	SentUId | String | Yes
	RecdUId | String | No
	TxnStep | Integer | Yes
	TxnHash | String | Yes
	TxnLinkID | String | Yes
	AddAndLocOfFarm | String | Yes
	NameOfFarmAndCompany | String | Yes
	IsDeleted | String | Yes
	CreatedDate | String | Yes
	Species | String | Yes
	additionalInfo | Array | No
	UserName | String | Yes
	SenderName | String | Yes
	LicenseAndPermitNumber | String | Yes
	NameOfVessel | String | Yes
	CountryOfVesselRegistration | String | Yes
	FAOMajorFishingArea | String | Yes
	FishingGear | String | Yes
	VesselID | String | Yes
	isRead | Boolean | Yes
	FishcoinAssets | String | Yes
	ReceiverName | String | Yes

Example.
{
	"ArrivalPort": "LAS",
	"DeparturePort": "LAX",
	"DepartureDate": "2021-11-03",
	"ArrivalDate": "2021-11-03",
	"CultureUnitLocation": "",
	"CultureUnitID": "",
	"RecdRole": "Fisher",
	"Status": "Log",
	"SentUId": "rOePqdKurLRY3pzHE6rOSlcgsDH3",
	"RecdUId": "",
	"TxnStep": 0,
	"TxnHash": "",
	"TxnLinkID": "",
	"AddAndLocOfFarm": "",
	"NameOfFarmAndCompany": "",
	"IsDeleted": false,
	"CreatedDate": "11 03 2021 17:55:48",
	"Species": [
		{
			"SpeciesId": "r1uk9p",
			"SpeciesName": "Anchovy - European",
			"SpeciesQty": 1,
			"ParentID": "",
			"LinkID": "",
			"AvailableQty": 1,
			"AdditionalInfo": [
				{
					"name": "",
					"value": ""
				}
			],
			"otherSpec": ""
		}
	],
	"additionalInfo": [
		{
			"name": "",
			"value": ""
		}
	],
	"UserName": "required",
	"SenderName": "Fisher UAT",
	"LicenseAndPermitNumber": "uat1234567",
	"NameOfVessel": "uat",
	"CountryOfVesselRegistration": "India",
	"FAOMajorFishingArea": "Area 27 (Atlantic, Northeast)",
	"FishingGear": "Handlines and hand-operated pole-and-line",
	"VesselID": "uat1234567",
	"isRead": false,
	"FishcoinAssets": 1
}

- b. Farmer:
	Parameter | Data type | Required/Default
	--------- | --------- | --------
	ArrivalPort | String | No
	DeparturePort | String | No
	DepartureDate | String | Yes- NULL
	CultureUnitLocation | String | Yes
	CultureUnitID | String | Yes
	ArrivalDate | String | Yes
	RecdRole | String | Yes
	Status | String | Yes
	SentUId | String | Yes
	RecdUId | String | No
	TxnStep | Integer | Yes
	TxnHash | String | No
	TxnLinkID | String | No
	IsDeleted | Boolean | Yes- false
	isRead | Boolean | Yes- false
	CreatedDate | String | Yes
	Species | String | Yes
	additionalInfo | Object | Yes
	UserName | String | Yes
	SenderName | String | Yes
	LicenseAndPermitNumber | String | Yes
	Country | String | Yes
	NameOfFarmAndCompany | String | Yes
	AddAndLocOfFarm | String | Yes
	FishcoinAssets | String | Yes

Example- {"ArrivalPort":"","DeparturePort":"","DepartureDate":null,"CultureUnitLocation":"EWR","CultureUnitID":"NSK666","ArrivalDate":"2021-11-10T12:16:56.629+05:30","RecdRole":"Farmer","Status":"Log","SentUId":"52QqKTpme1VAMZgsqSycLMhuTpd2","RecdUId":"","TxnStep":0,"TxnHash":"","TxnLinkID":"","IsDeleted":false,"isRead":false,"CreatedDate":"11 10 2021 12:18:13","Species":[{"SpeciesId":"kv7gl","SpeciesName":"Flounder - Olive","SpeciesQty":1,"ParentID":"","LinkID":"","AvailableQty":1,"AdditionalInfo":[{"name":"name1","value":"value1"}],"otherSpec":""}],"additionalInfo":[{"name":"ext","value":"extvalue"}],"UserName":"Remith UAT","SenderName":"Remith UAT","LicenseAndPermitNumber":"ABZ897654","Country":"India","NameOfFarmAndCompany":"Winjit","AddAndLocOfFarm":"Satpur","FishcoinAssets":1}

- c. Trader: 

	Parameter | Data type | Required/Default
	--------- | --------- | --------
	ArrivalPort | String | No
	DeparturePort | String | N0
	DepartureDate | String | Yes-Null
	ArrivalDate | String | Yes
	CultureUnitLocation | String | No
	CultureUnitID | String | No
	RecdRole | String | Yes
	Status | String | Yes
	SentUId | String | Yes
	RecdUId | String | No
	TxnStep | Integer | Yes
	TxnHash | String | No
	TxnLinkID | String | No
	IsDeleted | Boolean | Yes-False
	IsRead | Boolean | Yes-False
	CreatedDate | String | Yes
	Species | String | Yes
	additionalInfo | Array | No
	UserName | String | Yes
	SenderName | String | Yes
	LicenseAndPermitNumber | String | Yes
	Country | String | Yes
	NameOfFarmAndCompany | String | Yes
	AddAndLocOfFarm | String | Yes
	FishcoinAssets | String | Yes

Example:
	{"ArrivalPort":"","DeparturePort":"","DepartureDate":null,"CultureUnitLocation":"LAX","CultureUnitID":"NSK777","ArrivalDate":"2021-11-10T12:26:51.874+05:30","RecdRole":"Farmer","Status":"Log","SentUId":"52QqKTpme1VAMZgsqSycLMhuTpd2","RecdUId":"","TxnStep":0,"TxnHash":"","TxnLinkID":"","IsDeleted":false,"isRead":false,"CreatedDate":"11 10 2021 12:27:44","Species":[{"SpeciesId":"se212e","SpeciesName":"Carp - Black","SpeciesQty":1,"ParentID":"","LinkID":"","AvailableQty":1,"AdditionalInfo":[{"name":"name1","value":"value1"}],"otherSpec":""}],"additionalInfo":[{"name":"aname1","value":"avalue1"}],"UserName":"Remith UAT","SenderName":"Remith UAT","LicenseAndPermitNumber":"ABZ897654","Country":"India","NameOfFarmAndCompany":"Winjit","AddAndLocOfFarm":"Satpur","FishcoinAssets":5}

**NOTE: **
- Status can be - log, accepted, pending
- Species and additional info are common for Fisher, Farmer and Trader and a sample Parameters would look like below.
- i. additionalInfo :

	Parameter | Data type | Required/Default
	--------- | --------- | --------
	name | String | Yes 
	value | String | Yes
	
- ii. Species:
	
	Parameter | Data type | Required/Default
	--------- | --------- | --------
	SpeciesId | String | Yes 
	SpeciesName | String | Yes
	SpeciesQty | String | Yes
	ParentID | String | No
	LinkID | String | No
	AvailableQty | String | Yes
	AdditionalInfo | Object | Yes
	otherSpec | String | No
	
**8. Sending a linked record**<br/>
  A user can send his received records to a fisher, farmer or trader.<br/>
API:cmxAPI/firebase/addTxnDetails<br/>
Request Body: <br/> 

Parameter | Data type | Required/Default
--------- | --------- | --------
isRead | Boolean | Yes– false
ArrivalPort | String | No
DeparturePort | String | No
DepartureDate | String | Yes-NULL
RecdRole | String | No
SendUId | String | Yes
RecdUId | String | Yes
Status | String | Yes
TxnStep | Integer | Yes
TxnHash | String | No
TxnLinkID | String | No
IsDeleted | Boolean | Yes-false
Species | String | Yes
additionalInfo | Object | Yes
UserName | String | Yes
LicenseAndPermitNumber | String | Yes
AddAndLocOfFarm | String | Yes
FishcoinAssets | String | Yes
SenderName | String | Yes
ReceiverName | String | Yes

Sample Request Body : {
  "isRead": false,
  "ArrivalPort": "",
  "DeparturePort": "",
  "DepartureDate": null,
  "CultureUnitLocation": "",
  "CultureUnitID": "",
  "CreatedDate": "11 10 2021 12:49:32",
  "ArrivalDate": "2021-11-10",
  "RecdRole": "Trader",
  "Status": "Pending",
  "SentUId": "52QqKTpme1VAMZgsqSycLMhuTpd2",
  "RecdUId": "rOePqdKurLRY3pzHE6rOSlcgsDH3",
  "TxnStep": 1,
  "TxnHash": "",
  "TxnLinkID": "",
  "IsDeleted": false,
  "Species": [
      {
        "SpeciesId": "ovh9vk",
        "SpeciesName": "Anchovy - Japanese",
        "SpeciesQty": 10,
        "ParentID": "-MnQQfQOplZhlD0qBtY6",
        "LinkID": "-MnQQfmN9g2PJgccGxoQ",
        "AvailableQty": 10,
        "AdditionalInfo": [
          {
            "name": "",
            "value": ""
          }
        ]
      },
      {
        "SpeciesId": "1xukcb",
        "SpeciesName": "Anchovy - European",
        "SpeciesQty": 10,
        "ParentID": "-MnQWI1UfZejCjfpmIF3",
        "LinkID": "-MnQWIQLuMGXJm5ljBQd",
        "AvailableQty": 10,
        "AdditionalInfo": [
          {
            "name": "",
            "value": ""
          }
        ]
      }
  ],
  "additionalInfo": [
    {
      "name": "name1",
      "value": "value1"
    }
  ],
  "UserName": "Remith UAT",
  "LicenseAndPermitNumber": "NSK987",
  "AddAndLocOfFarm": "Satpur",
  "FishcoinAssets": "10",
  "SenderName": "Remith UAT",
  "ReceiverName": "Fisher UAT"
}

**9. Fetch record details**<br/>
  Get transaction details using transaction key<br/>
API:cmxAPI/firebase/getTxnbyKey<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
Key | String | Yes

Sample Request Body :      {
  "key": "-MmvS-YlNqUQV76YSNOV"
}

** 3.1.3 Settings**<br/>

**a. Profile information**<br/>
Fetch user details using userID.<br/>
API:/cmxAPI/firebase/getCurrentUserAccotDetailsByUId<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
userId | String | Yes

Sample Request Body : {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

**b. Transaction Log**<br/>

**i. Debit transaction logs of user**<br/>
 Fetch user debit logs using userID.<br/>
API:/cmxAPI/firebase/getDebitTxnLogListByUserID<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
userId | String | Yes

Sample Request Body : {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

**ii. Credit transaction logs of user**<br/>
Fetch user credit logs using userID.<br/>
API: /cmxAPI/firebase/getCreditTxnLogListByUserID<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
userId | String | Yes 

Sample Request Body : {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

**c. Invites Management**<br/>

**i. Send an Invite**<br/>
 Send a connection request to a registered TRACE user.<br/>
API: /cmxAPI/firebase/addInvite<br/>
Request Body: <br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
countryCode | String | Yes
sLoginId | String | Yes
rLoginId | String | Yes
Accepted | String | Yes
CreatedDate | String | Yes

Note: sLoginId : Logged in user login ID/email<br/>
rLoginId :LoginID/ email of the user who the invite is supposed to be for.<br/>
accepted: Status can be a string ‘accepted’ or ‘pending’, default to be sent as pending. <br/>

Sample Request Body :<br/>
 {
 "countryCode": "+91",
  "sLoginId": "remithr@yopmail.com",
  "rLoginId": "trader@yopmail.com",
  "accepted": "pending",
  "senderId": "52QqKTpme1VAMZgsqSycLMhuTpd2",
  "senderName": "Remith UAT",
  "senderRole": "Farmer",
  "senderImg": "https://firebasestorage.googleAPIs.com/v0/b/eachmile-uat.appspot.com/o/img-52QqKTpme1VAMZgsqSycLMhuTpd2?alt=media&token=45abd43b-e53b-41c2-9edd-5749f0baaddf",
  "receiverId": "5myEE4xhbyaLOGyF63gJH3GCFsE3",
  "receiverName": "Trader UAT",
  "CreatedDate": "11 10 2021 18:39:32",
  "receiverRole": "Trader",
  "receiverImg": " ",
  "FcmToken": ""
}

**ii. Accept an invite**<br/>
Once user accepts a connection request, we can update the status and show connections accordingly.<br/>
API:/cmxAPI/firebase/updateInviteLog<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | --------
Accepted | String | Yes 
Key | String | Yes

Sample Request Body :
  { 
   "accepted": "accepted",
    "key": "-MnZRBqajkQBDc_XV-7C"
  }

**iii. Reject an Invite**<br/>
Will reject the connection request or an accepted connection and delete the log from user connections.<br/>
API:/cmxAPI/firebase/deleteInviteLog<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | ----------------
Key | String | Yes

Sample Request Body : { 
 "key": "-MnZRBqajkQBDc_XV-7C"
}

**iv. Fetch Sent Invites**<br/>
Fetch all the invites sent by the user. Using the status as flag we can show the connections that are pending to accept and existing connection.<br/>
API:/cmxAPI/firebase/getInvitesBySenderID<br/>
Request Body:<br/>

Parameter | Data type | Required/Default
--------- | --------- | ----------------
userId | String | Yes

Sample Request Body : {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}

**v. Received Invites**<br/>
 Fetch all the invites received by the user. Using the status as flag we can show the connections that are pending to accept and existing connection.<br/>
API:/cmxAPI/firebase/getInvitesByReceiverID<br/>
Request Body:

Parameter | Data type | Required/Default
--------- | --------- | ----------------
userId | String | Yes 

Sample Request Body: {
  "userId": "52QqKTpme1VAMZgsqSycLMhuTpd"
}


