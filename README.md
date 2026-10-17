# Throne Lord Banners & Thrones Discord Bot

Public Information for the [Banners &amp; Thrones](https://bannersandthrones.com/) "Throne Lord" Discord Bot founded by Duo Forge Games.

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
### /map \[banner_or_player] \[optional_list], \[conquers], \[barbarians], \[players]