# Tracking pricing of Lightspeed products and sending text message notifications

First, this project was heavily inspired by this great post by Tim Knight:  
http://timmknight.github.io/2015/scraping-the-web-with-node/

## Goals
This is the beginning of a project that incorporates Node web scrapping with Twilio's phone API. 
I am currently tracking the pricing page of Lightspeed and storing the data in a JSON file.
When the price changes, the Node application will check and compare the new price with the store dprice.
When the price is different, it will update the stored price and send a text message to my cell phone. 

## Twilio 
Their slogan "Power modern communications. Build the next generation of voice and SMS applications." is very accurate. 
When demonstrating their technology to coworkers it's like magic. I can automatically send myself phone notifacations 
when something changes on the internet. 
I highly recommend using their fre API

## Requirements
#####Twilio https://www.twilio.com/  
#####cheerio https://github.com/cheeriojs/cheerio  
#####request https://github.com/request/request  
#####nodemon https://github.com/remy/nodemon (recommended)  

