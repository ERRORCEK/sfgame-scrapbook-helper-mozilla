# sfgame scrapbook helper

A firefox scrapbook helper extension for Shakes & Fidget. Useful if you don't have the holy grail yet. It will show you the maximum number of items you can get and name of the player (useful in arena screen)

It works purely by scanning http requests, so you shouldn't be worried.
It justs parse the data that is already loaded to you.

## How to use

1. Install the extension
   1. For now open [about:debugging#/runtime/this-firefox](about:debugging#/runtime/this-firefox) in your address bar
   2. Press `Load Temporary Add-on...`
   3. Open the provided `.zip` file
2. Open your scrapbook so the tool can scan it
3. Browse players in the hall of fame or open the arena and the tool will show you how many of their items you're missing

> Note: You will have to wait a while before scanning the same player repeatedly as sfgame seems to cache the inventories.
