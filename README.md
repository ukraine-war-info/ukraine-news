# ukraine-news

Get news about the war in Ukraine!

## This bot is using a modified version of DevFlocks discord bot! You can find his python bot [here](https://github.com/DevFlock/ukraine-news-bot)

This uses bbc.co.uk and there API.

I do plan to support backdoors (Such as onion) to fetch API requests.


# How it works

1. We set a request to the BBC api every 1 minute and display the content (A image URL will be provided if found)
2. BBC changes the news IDs so we scan for the new ID and change it.
3. We repeat all this!


# Plans
 - [ ] Built in VPN
 - [ ] Support onion version on BBC
 - [ ] Go back and get old posts

If you have any more ideas please make an issue :)


This repo will auto save news to a file using the DMY format [More info](https://en.wikipedia.org/wiki/Date_and_time_notation_in_Ukraine) (This can be disabled)


Langs supported: EN