# Building Bots
Annotated source code for the book Building Bots: A guide to building bots for the popular chat client Slack by Paul Asjes

# Usage
Clone this repository and run `npm install` in each chapter directory to install the required packages.

Run `node index.js` in each directory to see the code in action.

# Errata
A mistake made its way into chapter 4 of the book's code. Instances of `channel.send(message)` should actually be `bot.send(message, channel)`. The code in this repository has been updated accordingly.