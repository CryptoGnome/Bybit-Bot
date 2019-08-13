# Bybit-Bot
PLEASE NOTE THIS BOT IS FREE OF USE HOWEVER REQUIRES A AUTH KEY.
YOU CAN OBTAIN THIS BY CREATING A NEW ACCOUNT TO USE WITH THIS BOT,
WE CHECK BYBIT UID TO OUR AFFILATIE ACCOUNT TO AUTHORIZE THE USE.

Liquidation Hunter is a little bot written in Python that looks at
the liquidation feed via the Bitmex API for larger liquidation events
and counter trades them on Bybit where there is ZERO API friction and
we are able to get orders in very quickly without over load.

The theory is to trade very volatile moves when there are liquidations
present and get in quickly with a market order and use a tight Take Profit 
and Stop Loss. (Ride the Wave Dudddde)

Grab the Latest Release here:

https://github.com/CryptoGnome/Bybit-Bot/releases


Licence Keys:
---------------------------------------------------------------
You can use our link here:

https://www.bybit.com/home/en/index.html?affiliate_id=767&group_id=213&group_type=1

You can Register your UID with the BOT here:

https://forms.gle/qkRYbQUq6FwJcUde9

We also have a private discord channel for the BETA TESTERS here:

https://discord.gg/4gBBGjz

Please message @CryptoGnome#7769 on discord for the role to see the private BETA channels.


Installation:
---------------------------------------------------------------
Grab the latest release. This can be found in the pinned messages in the
private discord channel for support members.

Unzip Folder to location of you choice

Install Node & PM2 to Restart your bot if there are any crashes:
----------------------------------------------------------------
Install Node JS:

https://nodejs.org/dist/v12.8.0/node-v12.8.0-x64.msi

Run Install PM2 Using Included Bat File

Run The UPDATE Bat file included to update PM2 automaticlly


Edit Settings.py file with text editor:
---------------------------------------------------------------
Enter API Keys for ALL exchanges (Orders are only placed on Deribit - Bitmex is READ ONLY)
We use Bitmex for liquidations, Deribit for price calculation(Bybit does not have tick data), and bybit to place orders.


MAIN SETTINGS:
All of these settings effect the core strategy of the bot and there are descriptions next to them in the settings file.



How to Run Bot:
---------------------------------------------------------------
Use the Included Bat file <Bot Monitor> to launch PM2 Monitor.
Use the Included Bat File Named <Run Bot> to start Liquidation Hunter.
If you need to kill the bot use the Included Bat file named <Stop Bot>.

Common Errors:
---------------------------------------------------------------
`INFO - 2019-08-13 18:03:20,105 - Failed to retrieve access token: {
  "error": "invalid_grant",
  "error_description": "Invalid JWT: Token must be a short-lived token (60 minutes) and in a reasonable timeframe. Check your iat and exp values and use a clock with skew to account for clock differences between systems."
}`

Time Clock Sync is OFF use this:
http://www.timesynctool.com/

