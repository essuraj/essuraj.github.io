---
title: Building a bot using API.ai
date: 2017-08-24 20:50:02
tags: 
- bot
- api.ai
- AI
- machine-learning
---

Recently I found myself wandering into the concept of bots and conversational programming if I may call it so, I stumbled upon [API.AI](https://api.ai), a website promoted by google to create conversational user experience for a much natural approach to app interactions.

It seemed quite simple to understand at first and then all the stuff gets confusing. But eventually it slowly sunk in. Let me give you a quick bite on how to begin make a bot in api.ai.
<!-- more -->
Begin by signing in with your google account. After this you will begin by creating a new Agent.

{% image fancybox center fig-100 group:travel 1.JPG 1.JPG "Creating a new agent wizard" %}

Google does provide you with some sample data that will be populated into your agent if you want to understand its potential, but we will begin with a clean slate. I do encourage you to check those sample data out to get a better understanding of how stuff were meant to be used.

An agent has 3 major components. 
- Intents
- Entities
- Response 

{% image fancybox center fig-100 group:travel api.ai.png api.ai.png "Creating a new agent wizard" %}

### Intents
There are the inputs what people usually ask the bot.
{% image fancybox center fig-100 group:travel 2.JPG 2.JPG "Intents are what the user says, the highlighted portions are the entities that were detected in the intent" %}

### Entities
These are what people categorize data into. More like a variable in development terms.
{% image fancybox center fig-100 group:travel 3.JPG 3.JPG "Detected entities are shown here." %}

We can create our own entities from the entities page
{% image fancybox center fig-100 group:travel 3.1.JPG 3.1.JPG "The entities section" %}

Here we create an entity called options. It well have 2 possible results. Agree or disagree ..and a set of words that will mean either of those options. API.AI also gives you some inbuilt entities under the @sys namespace. 
{% image fancybox center fig-100 group:travel 3.2.JPG 3.2.JPG "Creating the entities section" %}

You can add new ones. You can make entities compulsory. If so you can prompt the user until he/she supplies the information.  
{% image fancybox center fig-100 group:travel 4.JPG 4.JPG "Questions that need to be prompted for the required entities" %}

### Response
The reply that is sent to the user after you have satisfied all that you needed to know from the user's intent.
{% image fancybox center fig-100 group:travel 5.JPG 5.JPG "The reply that the bot gives after your requirements are met" %}


## Testing our work
{% image fancybox center fig-100 group:travel 7.gif 7.gif "Testing with the panel on the right" %}

Where do we go from here...
If you dial into the options, you'll find a ton of integrations with api.ai that will save you a lot of time and engage with users in a great collection of platforms.
{% image fancybox center fig-100 group:travel 8.png 8.png "Integrations" %}



