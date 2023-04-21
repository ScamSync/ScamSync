## About


ScamSync was created as a tool for Discord guilds to collaborate in addressing the growing issue of fraudulent activities in the Crypto and NFT communities. These activities are perpetrated by individuals who masquerade as support staff or administrators, offering assistance with the ulterior motive of stealing funds from unsuspecting victims. Typically, these individuals are reported to guilds through dedicated channels, and their unique Discord identification numbers or usernames are added to a ban list.

With ScamSync integrated into a guild's channel, administrators gain access to ban reports from other channels. This feature allows them to prohibit individuals from accessing their own channels, irrespective of whether they are presently active in them.

With an increasing number of channels utilizing ScamSync, the collaborative effect of guilds in curbing fraudulent activities within the wider community is strengthened.

![](https://github.com/ScamSync/ScamSync/blob/main/img/report01.png)


## Installation

To incorporate ScamSync bot into your Discord guild, please use the link provided below.

[Discord Link](https://discord.com/api/oauth2/authorize?client_id=1086433535688196167&permissions=2147519494&redirect_uri=http%3A%2F%2Fscamsync.dev%2Flarascord%2Fcallback&response_type=code&scope=guilds.join%20bot%20applications.commands) 

Upon successful integration of the bot into the guild, it is necessary to designate two channels to receive global ban alerts and guild reports.

```bash
  /setup banschannel
```

Global ban alerts refer to notifications that are triggered when a user gets banned from a guild. You will receive these alerts, and subsequently have the option to review the ban and decide whether or not to ban the user from your Discord server, regardless of whether the user has joined your server or not.

```bash
  /setup reportschannel
```
   
The Reports Channel is designed for guild members to submit reports by using the slash command /report, which requires them to enter the offender's Discord name (e.g. @ScamSync#0001) or the user's snowflake ID (if developer mode is activated). After that, the user is prompted to provide a screenshot, which will be uploaded to Discord. If needed, an optional second image can also be uploaded. At this point, the user can submit the report, which will be published in the Reports Channel.

## Demo

![](https://github.com/ScamSync/ScamSync/blob/main/img/bot.gif)

## Features

ScamSync offers the following features:

    Enables the use of designated channels for ban and report alerts, such as #ban-channel or #reportchannel.
    
    Allows for image uploads when creating a report, which can be shared across all Discord guilds where the bot is installed.
    
    Facilitates the sharing of ban data across Discord guilds, allowing for due diligence by permitted roles to approve or deny ban requests.
    
    Provides the option to enable auto-acceptance of ban requests (true or false).
   
    Supports a maintenance message for when the bot is down for maintenance.
    
    Provides dev statistics, including total bans, suggested bans, and total servers where the bot is installed.
    
## To Do


    A WebUI feature will be implemented for authorized guild users to view the list of bans.
    
    The WebUI feature will include an option to search for a snowflake ID.
    
    Additionally, the WebUI feature will allow authorized guild users to add or remove bans from the global list (guild-specific).


