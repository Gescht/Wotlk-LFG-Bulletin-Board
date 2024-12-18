# LFG-Bulletin-Board
Dungeon Request chat filtering
GBB provides an overview of the endless requests in the chat channels. It detects all requests to the classic dungeons, sorts them and presents them clearly way. Numerous filtering options reduce the gigantic number to exactly the dungeons that interest you. And if that's not enough, GBB will let you know about any new request via a sound or chat notification. And finally, GBB can post your request repeatedly.
Currently, English, German and Russian dungeons are recognized natively. But it is easily possible to adapt GBB to any language.

![Imgur](https://i.imgur.com/EBpf3Yp.jpg)
Usage

GBB searches the chat messages for dungeon requests in the background. To whisper a person, simply click on the entry with the left mouse button. For a "/who" a shift + left click is enough. The dungeon list can be filtered in the settings. You can also fold this by left-clicking on the dungeon name.
Old entries are filtered out after 150 seconds.

 

Slash Commands
<value> can be true, 1, enable, false, 0, disable. If <value> is omitted, the current status switches.
 
`/gbb notify chat <value>` - On new request make a chat notification
 
`/gbb notify sound <value>` - On new request make a sound notification
 
`/gbb debug <value>` - Show debug information
 
`/gbb reset` - Reset main window position
 
`/gbb config/setup/options` - Open configuration
 
`/gbb about` - open about
 
`/gbb help` - Print help
 
`/gbb chat organize/clean` - Creates a new chat tab if one doesn't already exist, named "LFG" with all channels subscribed. Removes LFG heavy spam channels from default chat tab


 `/gbb` - open main window

todo

making it load to the end
    --LibGPIOptions.lua
    --LibGPIMinimapButton.lua
    --LibGPIToolBox.lua
    --Chat.lua
    --Localization.lua
    --dungeons\wrath.lua
    --CustomCategories.lua
    Dungeons.lua
    Tags.lua
    RequestList.lua
    Options.lua
    GroupList.Lua
    GroupBulletinBoard.lua
    LfgToolList.lua
    GroupBulletinBoard.xml


initial check
    LibGPIOptions.lua
    LibGPIMinimapButton.lua
    LibGPIToolBox.lua
    Chat.lua
    Localization.lua
    --dungeons\wrath.lua
    CustomCategories.lua
    Dungeons.lua
    Tags.lua
    RequestList.lua
    Options.lua
    GroupList.Lua
    GroupBulletinBoard.lua
    LfgToolList.lua
    GroupBulletinBoard.xml

double check 
    LibGPIOptions.lua
    LibGPIMinimapButton.lua
    LibGPIToolBox.lua
    Chat.lua
    Localization.lua
    dungeons\wrath.lua
    CustomCategories.lua
    Dungeons.lua
    Tags.lua
    RequestList.lua
    Options.lua
    GroupList.Lua
    GroupBulletinBoard.lua
    LfgToolList.lua
    GroupBulletinBoard.xml
