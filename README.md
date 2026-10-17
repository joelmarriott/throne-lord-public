# Throne Lord Banners & Thrones Discord Bot

Public Information for the [Banners &amp; Thrones](https://bannersandthrones.com/) "Throne Lord" Discord Bot founded by Duo Forge Games.

[Command Reference](#command-reference)

## Buy Me a Coffee
Throne Lord will always be free. You can help me cover hosting costs or say thank you for the utilities by buying me a coffee!

https://buymeacoffee.com/joelmarriott

Thank you! 😎

## Contact

### Creator

joel.marriott on discord

### Development Discord

https://discord.gg/3bfngHsUXJ

## Adding Throne Lord to Your Discord Server

Simply click the link below and select the server Nobility should join.  
_Note: You must have administrator permissions on the server to invite a bot_

https://discord.com/oauth2/authorize?client_id=1558140702284587158

# Feature Requests and Bugs

Create an issue on the issues tab, alternatively join the development discord!

# Command Reference
[Worlds](#worlds)\
[Help](#help)\
[Banner Information](#banner-information)\
[Player Information](#player-information)\
[Villages](#villages)\
[Mapping](#mapping)
## Worlds
### /set_world \<scope> \<world>
*Sets the world for the current server (guild) or channel*

**Scope:** `server` or `channel`\
**World:** Select a world from the up-to-date list e.g. `world-1`
### /world
*Returns information about the current world*

## Help
### /about, /help, /discord, /report, /support
*Provides help information and useful links for Throne Lord*

## Banner Information
### /banner \<banner name or tag>
*Get information about the selected banner. On the information screen, you can choose one of the buttons to get further information (Time-out after 3 minutes)*

## Player Information
### /player \<player name>
*Get information about the selected player. On the information screen, you can choose one of the buttons to get further information (Time-out after 3 minutes)*

## Villages
All coordinates can be provided in the following formats: `500 500` `500|500` `500:500`
### Co-ordinate Recognition
Incoming messages and embeds are checked for co-ordinates and the villages output to the same channel.

Webhook embeds are scanned, incoming notifications will yield more detailed information.
### /distance \<origin> \<destination>
*Calculates the distance between two villages and shows the travel time for all units*

## Mapping
It is possible to generate maps based on a variety of optional data.\
When a map is requested, it enters a queue and will be posted to the channel it was requested in - when it has finished generating.\
This may take some time depending on the queue size.

### /map \[banner_or_player] \[optional_list], \[conquers], \[barbarians], \[players]
`banner_or_player` Highlight banners or players.\
*Default: Don't highlight*\
`optional_list` Where banner or player highlighting has been chosen, comma seperated (no spaces) list of players/banner tags.\
*Default: Top 20.*\
`conquers` Days to show conquers for.\
*Default: 0*\
`barbarians` Show barbarian villages (True/False)\
*Default: True*\
`players` Show non-highlighted players (True/False)\
*Default: True*