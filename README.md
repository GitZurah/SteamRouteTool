# SteamRouteTool
A tool for blocking routes in Steam games that use network_config.json
Updated by zaxo7, forked to provide a compiled binary to download.

Note: This will automatically clear any CSGORoutingTool firewall rules upon launch (to save the need to clear those rules in that application).

## Supports:
Blocking specific routes for games that use Valve's network_config.json (e.g. Counter-Strike: Global Offensive & Dota 2).

## How to use
* Click the checkbox of the route(s) you'd like to block.
* Click the route name to reveal additional routes at that location (if available).
* Click "Blocked" to toggle all checkboxes.
* Click a ping value to re-ping that specific route.
* Clear Rules will clear all firewall rules.
* Ping Routes will ping all routes and update their values.

## Credits
#### Froody
Tool creation.
#### Newtonsoft
Newtonsoft.Json package, licensed under MIT. https://github.com/JamesNK/Newtonsoft.Json/
#### Icon
https://github.com/feathericons/feather#feather
#### zaxo7
For providing the patch to stop crashing
