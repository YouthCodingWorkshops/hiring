# Challenge 3: Ordering Discord Bot

* Technologies: Python, NextCord, SQLite3
    - Discord.py is no longer actively maintained
* Tests: Required
* Documentation: Required, in a `README.md` file

Your goal in this challenge is to build a discord bot that allows individual users to place orders in a restaurant. It should employ slash commands and message components so the user can easily interact with your bot.

Here are the basic requirements:
* Each user (denoted by their Discord UUID) starts off with a set amount of money
* The user should be able to order items on the menu
* Each user looks like this:
    * id
    * balance
    * ordered_items[]
* Menu items look like this:
    * id
    * name
    * description
    * cost
* When the user is ready to place their order, subtract their total from the money they have
* The user should be able to view the items they've **ordered** and **placed orders for**
* The user should be able to remove menu items from their current orders

The user should be able to intuitively interact with your bot, leveraging controls like buttons and dropdowns. You should probably also use message embeds.

#### Reminders

1. Make sure to have proper error handling
2. The point of using a database is to keep you away from storing all your data in a single giant python dictionary
3. Include tests
