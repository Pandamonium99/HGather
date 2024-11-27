# HGather
This is a simple Digging / HELM / Farm / Fish tracker for FFXI. This addon works with Ashita v4. 

## HELM
In order to handle HELM macros that rely on <lastst> the addon defaults to whatever HELM activity you have active in the addon if it can not determine what type of target resource you are farming.

Example macro page:
```
/item "Pickaxe" <stnpc> <wait5>
/item "Pickaxe <lastst> <wait5>
/item "Pickaxe <lastst> <wait5>
/item "Pickaxe <lastst> <wait5>
/item "Pickaxe <lastst> <wait5>
/item "Pickaxe <lastst> <wait5>
```

## Farm / Fish
Currently experimental, enable through the /hgather settings as "Hunt" and "Fish" modes.

## Commands
/hgather or /hgather editor - Opens the configuration menu

/hgather show/hide - Shows or hides the addon window

/hgather update - Updates the pricing for items based on what you entered in your settings

/hgather report - Prints the dig data to chatlog (only dig data currently)

/hgather clear - Clears the hgather session data

## Pricing
Pricing for items is listed under the configuration window under the Items tab. Make sure the format is as follows:

**Format**: item name:itemprice

**Example:** pebble:100

This would price pebbles at 100g.

If you update the prices while in game, make sure to use the **/hgather update** command to update the prices.

