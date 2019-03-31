//This guide is meant to give examples of simple macros, to allow people to better write their own. Important notes:
//1: Always have #showtooltip at the beginning (you can specify a spell, like #showtooltip polymorph)
//2: Spell / item names are case sensitive; heaRThstone won't work, but Hearthstone will.

//QUICK KEYS
//An example of a simple key modifier macro. Pressing shift will cause you to cast Solar Wrath, otherwise it'll cast Regrowth.
#showtooltip
/use [mod:shift] Solar Wrath; Regrowth

//This model can be used for any spell, or item, for example...
#showtooltip
/use [mod:shift] Dalaran Hearthstone; Hearthstone

It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)