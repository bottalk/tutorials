# Use Alexa In-Skill Purchasing (ISP) with BotTalk

![Tutorial Learn Alexa In-Skill Purchasing Sell Digital Products with Voice](https://docs.bottalk.de/assets/images/social-bg-alexa-in-skill-purchasing-tutorial.png)

In-skill purchasing allows you to sell premium content directly from the Alexa Skills you created. Buying these digital products with voice is a seamless process to a user. A skill can suggest (upsell) a specific premium feature - and a user says something like "Yes, I want to buy **product name**". Customers pay for products using the payment options associated with their Amazon account.

In this tutorial, you learn how to implement in-skill purchasing (ISP) in your Alexa Skills using [online Skill building platform - BotTalk](https://bottalk.de).

---

## Table of Contents

* [What you’ll build](#what-youll-build)
* [Create in-skill products](#create-in-skill-products)
* [Add ISP support to your BotTalk scenario](#add-isp-support-to-your-bottalk-scenario)
* [Test your skill](#test-your-skill)

---

## What you'll build

As always, it's a great idea to draft a sample dialogue between a user and Alexa, before you start building the actual Skill.

That's what our voice user experience is going to look (sound) like:

> **User**: Hey Alexa, open **Apple Game**

> **Alexa**: Welcome to Apple Game! The world's largest virtual bio apple store! Here's what we have today to offer: Apple Pie. Apple Basket. What would you like to buy?

> **User**: I would like to buy an Apple Basket.

> **Alexa**: Great apples in a large bio basket. Prime members save $0.19. Without Prime, your price is $0.99 plus tax. Would you like to buy it?

> **User**: Sure.

> **Alexa**: Great! You now have Apple Basket. Would you be interested in Apple Pie?

> **User**: Yes.

> **Alexa**: Apple Pie. Prime members save $0.19. Without Prime, your price is $0.99 plus tax. Would you like to buy it?

> **User**: Yes.

> **Alexa**: Great! You now have Apple Pie. Is there anything else I can help you with?

> **User**: I would like a refund for an Apple Pie. 

> **Alexa**: For a refund, check out the link I sent to your Alexa app.

A lot is going on in this small dialogue. In the course of this tutorial, you learn about buying, upselling, refunding, and more. 

[So, let's get started!](https://docs.bottalk.de/tutorials/alexa-in-skill-purchasing#create-in-skill-products)