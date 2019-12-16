# FullAutoEasyScap
Lua unlocked version of the addon "EasyScrap". You can find it here: https://www.curseforge.com/wow/addons/easy-scrap

Automatically presses scrap button, full automation.

# How do I use

You have to have to unlock protected functions in WoW's Lua API. I recommend making your own, but there are Lua unlockers available for purchase at other places.

# What did you change

Nothing much, I added a one-liner in `addQueueItems` to simply click the scrapping button frame once the items have been queue'd. Hit `Queue All` once and it will continue scrapping until you are out of items. This saves you from having to click once every 9 items.
