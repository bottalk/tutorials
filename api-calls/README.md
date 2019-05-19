# Make an API Call from an Alexa Skill and Action on Google

No Alexa Skill or Action on Google lives in the vacuum. The more intersting voice application you have in mind, the more likely it is that you need to request some external data.

Learn how to build a task management [voice application](https://docs.botalk.de/#what-are-custom-alexa-skills-and-actions-on-google) that can call [Trello Rest API](https://developers.trello.com/reference) to read, create, update and delete cards with voice.

---

## Table of Contents

* [What you’ll build](#what-youll-build)
* [Requesting Trello API key and Token](#requesting-trello-api-key-and-token)
* [Understanding Trello Rest API](#understanding-trello-rest-api)
* [List the cards in the TODO column with GET](#list-the-cards-in-the-todo-column-with-get)
* [Create a new card with POST](#create-a-new-card-with-post)
* [Move a card from DOING to DONE with PUT](#move-a-card-from-doing-to-done-with-put)
* [Delete a card with DELETE](#delete-a-card-with-delete)
* [Source Code](#source-code)

---

## What you’ll build

Before we start building any Alexa Skill or Google action, it's good idea to take a minute or two and write a sample dialogue first. 

This dialogue reprents a **happy path** - when the interaction between a voice assistant and a user runs perfectly:

> **User**: Hey Alexa / Google, open **Task Manager**

> **Assistant**: Here is what you need to do today. [LIST OF TASKS]

> **User**: Create a new task called "Walk the dog tonight".

> **Assistant**: Creating a new task: "Walk the dog tonight".

> **User**: Move the last task from TO DO into DOING.

> **Assistant**: Moving "Walk the dog tonight" to "DOING".

> **User**: Delete the last task from "DONE".

> **Assistant**: Deleted "Record YouTube Video" from "DONE"


The cool thing is, the voice application we're build interacts with the Trello API. And you can see the results of your voice commands on your screen - in your Trello board.

[Let's get started!](https://docs.bottalk.de/tutorials/api-calls-from-alexa-skill-and-google-action#requesting-trello-api-key-and-token)