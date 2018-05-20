# DeluxeMenus
## About
DeluxeMenus is the all in one inventory GUI menu plugin!  
You can create GUI menus that open with custom commands that will show stats or perform actions specific to the player who opened it.

Your menus are fully configurable. You can create menus that show specific items to different players, or perform different actions depending on what javascript requirement they have for the specific slot in a certain GUI (optional)

You can open a GUI menu 3 different ways:
* `/<custom command specified for the GUI>`
* `/dm open <menuName>` for yourself
* `/dm open <menuname> (player)` to open a GUI menu for another player (Requires `deluxemenus.open.others`)

## Dependency
DeluxeMenus depends on [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)

## Commands
* `/dm open <menuName>`  
Opens the menu <menuName> for yourself  
* `/dm list`  
Lists all menus you have access to  
* `/dm reloads`  
Reloads the menus and settings

## Configuration
Visit our [wiki](https://github.com/help-chat/DeluxeMenus/wiki) to get info about how to make GUIs, items, etc.  
If you need support, join our Help chat-Discord (Link below).

## Permissions
* `deluxemenus.admin`  
Gives access to admin-commands.  
Default: OP
* `deluxemenus.open`  
Lets you open a menu with `/dm open <menuName>`  
Default: OP
* `deluxemenus.open.others`  
Lets you open a menu for another player (`/dm open <menuName> [player]`)  
Default: OP
* `deluxemenus.open.bypass`  
Lets you open a menu regardless of if you have the permissions for it.  
Default: OP
* `deluxemenus.menu.*`  
Gives permission for all menus.  
Default: OP
* `deluxemenus.openrequirement.bypass`  
Lets you bypass the openrequirement of a menu.  
Default: OP

## Links
<a href="https://discord.gg/FtArYRQ" target="_blank"><img src="https://discordapp.com/api/guilds/164280494874165248/embed.png" alt="Discord"></a>  
[Wiki](https://github.com/help-chat/DeluxeMenus/wiki)  
[SpigotMC](https://www.spigotmc.org/resources/deluxemenus.11734/)