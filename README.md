# KAHOOTINAT😈R
Launch at [https://mittaldev.com/kahootinator/](https://mittaldev.com/kahootinator/)

## What does it do?

Kahootinator can deploy hundreds of kahootinator bots to infiltrate and take over any public Kahoot game!

You can set the bots' name, how the bots will answer questions, and how many bots to send.

Simply enter any kahoot game's PIN code, customize your bots, and press KAHOOTINATE!

## How does it work?

When you press KAHOOTINATE!, the web page sends an HTTP GET request to a REPL I created for this tool.

The GET request contains the information you chose for the bots.

The REPL, upon receiving the request, makes sure the information is valid, and if it is, sends the bots.

To communicate with the Kahoot game server, I used a library called Kahoot.js-updated (on NPM).

Each bot is sent after a small random delay to reduce the chance of Kahoot's server recognizing that they're bots.
