# xTeam-Project
Banking System

Title: “XBanking”  

Members: Harrison, Riza, Cameron, Roshan

Problem: Banking can be hard. How do you let people access their accounts? What if they have multiple accounts? It can be hard to keep track. 

Primary Stakeholder: Any bank who needs to manage a lot of accounts 

Data structure: HashTable of Clients. Each Client may have multiple accounts. Hash function will be full name no spaces absolute value hashcode modulo 7(will need to be changed). Use quadratic probing to deal with collision.

Possible formatting of file to save and load data:
	Client1Key
	Account1
	Account2
		.
		.
	Client2Key
	Account1
	Account2
		.
		.
	Client3Key
	.
	.
	.
This file will list each client followed by each of their accounts.

Need to touch up GUI

Basically this will add a new Class Client to the HashTable. The Client object will contain: First name, Last name, Account number(s) probably just saving and checking, Balance(s) again saving and checking, and Date of creation. The Output will just display all this info to the screen, the Input will be pre-created client objects. Originally this didn't handle creation of the client objects, I added an option but I think that it will be easier if we assume all the clients are already there.

GOOGLE SLIDES EDIT LINK : https://docs.google.com/presentation/d/18Bfxw0kbqm-eoN79lvVo4gjJOuR4bcPSlsvVcyChnKc/edit?usp=sharing


