# Project Proposal

Yard Bot is a software platform that utilizes social media to streamline the yard waste pickup process. Yard Bot will be backed by a fleet of drivers operating in the City of Chicago to aid in the leaf disposal process.

## Introduction

Yard Bot is a Facebook Messenger bot that allows persons with a Facebook account to post requests for yard waste pickup. Information from the request saved in a database is analyzed for optimal pickup route. 
The pilot program will be a crowd-sourced recruitment of 50 drivers in the first year of the program. Drivers will make a weekly salary for meeting required quota, delivering yard waste to specialized city composting facilities. Sign-ups requires drivers with qualified pickup trucks and a smartphone, wagons can be rented for increased performance.

## Rationale & Significance

The current method to contact the City of Chicago for leaf pickup is through an online form. The filing process requires filling textboxes asking for redundant information. The obscurity of the form and instructions on filling it out may not be intuitive for the average users. 
The City of Chicago’s leaf disposal program had transitioned from scheduled pickup to 311 requests.  But technical miscommunication from the city officials has resulted in minimal to no 311 requests made for leaf disposal. 

A large number of our users already have accounts on Facebook, making the Messenger bot as one of the best platforms to reach all of our users without having to go through a signup process.
Having a Messenger bot platform allows Chicagoan to post their leaf pickup request on any web-compatible device without having to take too much time to fill out a form. 
The Facebook platform allows us to grab Facebook profile making the request, location is retrieved with a pop-up and a drag of a pin, and an image as a description of the pickup location.

Funding for the drivers will come from environmental and economic foundations and the City of Chicago as a way to create seasonal jobs to low-income areas of the city.

## Plan of Action

### Scope

Current software is a prototype that shows its application and is not ready to be used in public. More work may be done upon receiving approval from city officials.

### Methods

The Messenger bot prototype currently stores 311 requests to a database without guarantees of the data’s validity.
The scope of this project contains the research of the City of Chicago’s yard waste disposal program and a prototype of a software to test its feasibility with users. 

### Task Breakdown

* A project proposal with components covered in the corresponding chapter of your textbook;

Haosheng and Minhua

* A comparison of Chicago’s program with three comparable cities (two from the U.S. and one international city), along with data visualizations that effectively compare program costs and waste stream diversion (or comparable metrics);

Mack

* A website that showcases your proposal and links to other relevant information;

Vinesh

* A public social media account with some example posts illustrating how you will encourage program participation;

Minhua

* Instructions for the new pick up procedure and other home disposal methods;

Minhua

* A promotional card, brochure, or other items for distribution to households.

Haosheng

### Problem Analysis

The potential problem with the Facebook Messenger bot includes user interactions, spam filters, and validity of requests. The Facebook platforms allow us to easily identify persons’ profile interacting with the Messenger bot. This will prevent spams and improve the validity of requests. Creating an intuitive interaction with the users will require user testing and feedback on the Messenger bot.

Passing the City’s approval, continuation in Messenger bot would including adding features such as an algorithm to maximize the number of pickup per miles driven. This will require methods to analyze its performance and validity of the algorithm.

## Facilities and Equipment

The Messenger bot may require a web accessible device to allow the viewing of requests made by the public. If employees do not have a modern smartphone to access the web, this requirement can be easily satisfied with a one-time purchase. An adequate device under $100 dollars such as Raspberry Pi and monitor will be able to view Messenger bot requests.
The City could also provide rental wagons for drivers to increase their leaf pickup load. The cost of wagon rental should be enough to pay back the wagon’s one-time purchase.

## Personnel (Management Proposal)

Social media director, one person should be enough to sufficiently manages the Facebook page and Messenger platform.
Facebook developer, as a possible future goal of this project or a one-time contract of the initial Messenger bot application and a retainer agreement for future updates and maintenance of the application.

## Budget (Cost Proposal)

Personnel Cost: 

Facebook Developer salary will have to be negotiated. 

Driver Salary: 

$440/month 

$5,280 for the season

Starting off with 50 drivers for 600,000 pickups (current data of 3% of people calling in for yard waste pick up), the total cost spent on driver salary is about $260,000. 
The average cost of a wagon is about $300. 

## Conclusion

Yard Bot is a social media Messenger bot that promotes the collection of yard waste. Users will rake and put their yard wastes into bags and send a message to Yard Bot whenever it is ready for pick up. Yard Bot’s goal is not only to streamline the yard waste pickup process, but it will also provide a seasonal job opportunity for drivers to make up to $5, 280. Drivers will have to meet a weekly quota by going to these locations collected by Yard Bot, pick up the yard waste and dispose it at a local landfill. 

This program will resolve two issues that are seen with the current yard waste program. It utilizes a very popular way to reach homeowners/renters: social media. The process requires sending a message to our bot, which people are commonly doing on their smartphone nowadays, making the usability at a very easy level; it eliminates the whole process of going through an automated calling system. The second problem it will resolve is cutting down the cost. The cost of this program is on the scale of $100,000 versus a multi-million dollar program of sending drivers out to collect yard waste, similar to the garbage collection program now. In the case of a higher demand in pick up, our program’s cost will not increase due to the seasonal pay. Rather than paying these drivers pay-per-pickup, they are getting paid seasonally. The budget will only increase if the number of drivers increases. 

## Appendices

### Appendix A: Messenger Bot

The webhook for the Messenger bot is currently hosted on glitch at glitch.com/~complete-musician. 

Access to this bot is only available to administrators, developers, and testers of the Facebook app until it’s published for public use.

The script running the responses for the Messenger bot currently does not check for known or unknown exceptions that could be made by the users. 

The flow of the current Messenger bot requires a prompt. Its response will ask for a location with a button. After providing a location, it’s recommended that an image is uploaded. The request data along with the Facebook username will be uploaded onto Firebase upon pressing the post button.
