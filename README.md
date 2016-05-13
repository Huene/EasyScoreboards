#Easy Scoreboard
A Sponge plugin to create easily scoreboards
for things such as lobbys.

##Features
1. Easy setup
2. Change the scoreboard texts by commands OR by config
3. Use colors
4. Use styles
5. Use the players name
6. Use the number of online players

##Setup
1. Place the plugin file in the mods folder
of you Sponge server
2. Start the server
3. Edit the text by commands

##Links (Download)
Lastest Release (Download): https://github.com/byYottaFLOPS/EasyScoreboards/releases/latest

This guide: http://byyottaflops.github.io/EasyScoreboards/

Github page: https://github.com/byYottaFLOPS/EasyScoreboards

##Commands
    !!Changes are instantly applied for all players!!

`/setscoreboard <Line> <Text>`

`<Line>` is the line of the scoreboard and can be anything between 0 and 15. The line 0 is the title of the scoreboard.

`<Text>` Is the text the line will contain. To use spaces the hole text must be in quotation marks (see examples).

    !!You can only use one color and one style per line!!

`/clearscoreboard` will clear the scoreboard and remove
it from every player.

##Replacements
In the `<Text>` argument the following strings will
be replaced.
###Colors
`AQUA`
`BLUE`
`GOLD`
`GREEN`
`YELLOW`
`RED`
`LIGHT_PURPLE`
`DARK_AQUA`
`DARK_BLUE`
`DARK_GREEN`
`DARK_RED`
`DARK_PURPLE`
`WHITE`
`GRAY`
`DARK_GRAY`
`BLACK`

These will be replaced with the equivalent color.

###Styles
`BOLD`
`OBFUSCATED`
`ITALIC`
`STRIKETHROUGH`
`UNDERLINE`

###Other
`PLAYER` will be replaced with the name of the player
who sees the scoreboard

`ONLINECOUNT` will be replaced with the number of online players

    Using "PLAYER" and "ONLINECOUNT" together is not recommended
    because it is computationally intensive at a large number
    of concurrent players

##Examples
`/setscoreboard 0 "BOLDGREENHello PLAYER"`

`/setscoreboard 1 "REDWelcome to the server"`

`/setscoreboard 1 "YELLOWYou are currently in lobby 1"`

`/setscoreboard 1 "GREENWebsite:"`

`/setscoreboard 1 " server.com"`

Result:
![Result](https://github.com/byYottaFLOPS/EasyScoreboards/blob/master/screenshots/screenshot1.png?raw=true)