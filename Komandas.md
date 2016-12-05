# Komandas

Manager
-------
|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | Uzstādīt maksimālo AFK laiku |
|!botname | (botname) | Nomaina esošā bota lietotājvārdu |
|!bouncer+ | | Ieslēdz/izslēdz bouncer+ |
|!skippos | X | Uzstāda pozīciju uz kuru palaiž DJ |
|!clearchat | |Iztīra čatu |
|!cycle | | Ieslēdz/izslēdz DJ ciklu |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |
|!language | (language) | īpašā valoda kuru izmanto bots |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled |
|!logout | | Iziet no bota ja tas tiek hostots |
|!refresh | | refreshes the browser of whoever runs the bot |
|!usercmdcd | X | set the cooldown on commands by grey users |
|!usercommands | | Ieslēdz/izslēdz lietotāju komandas |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit. |

Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | Pievieno lietotāju gaidītāju sarakstam |
|!afkremoval | | Ieslēdz/izslēdz AFK taimeri |
|!autoskip | | Automātiski skipo dziesmu ja tā nosprūst uz loop buga |
|!deletechat | @user | Izdzēš čatus īpašam spēlētājam |
|!lock | | Aizslēdz whitet/r Nepieciešami papildspēki, meklē|
|!lockdown | | lock down the room: only staff can chat |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
|!remove | @user | remove user from the waitlist |
|~~!roulette~~ | | ~~start a roulette~~ |
|!songstats | | toggle song statistics |
|!unlock | | unlock the waitlist |
|!welcome | | toggle the welcome message on user join |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!afkreset | @user | resets the afk time of user |
|!afktime | @user | shows how long user has been afk |
|!autodisable | | toggle the autodisable |
|!ban | @user | bans user for 1 day |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
|!commanddeletion | | toggles if bot commands gets deleted |
|!blinfo | | get information required to blacklist a song |
|!cycleguard | | toggles the cycleguard |
|!dclookup / !dc | (@user) | do dclookup for user |
|!english | @user | ask user to speak english (asked in the language they set plug to) |
|!eta | (@user) | shows when user will reach the booth |
|!filter | | toggles the chat filter |
|!forceskip | | forceskips the current song |
|!historyskip | | toggles the history skip |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!kill | | shut down the bot |
|!lockguard | | toggle the lockguard |
|!lockskip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
|!mute | @user/(X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!reload | | reload the bot |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
|!sessionstats | | display stats for the current session |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!status | | display the bot's status and some settings |
|!timeguard | | toggle the timeguard |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unban | @user | unban user |
|!unmute | @user/all | unmute user |
|!voteratio | @user | display the vote statistic for a user |
|!whois | @user | returns plug related information about user |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!link | | Izsniedz linku uz esošo dziesmu |YouTube|



User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!commands | | Izsniedz linku uz komandu lapu |
|!cookie | (@user) | Iedod kādam savu cepumu |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | Links kurā ir visi smaidiņi |Emoji| |
|!eta | | shows how long before you reach the booth |
|!ghostbuster | @user | Parbauda vai spēlētājs ir spoks, spokojas |
|!gif | (message) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!help | | Links kurš aizsūta tevi uz plug.dj pamācību |
|~~!join~~ | | ~~Vari pievienoties ruletei, ja aktivizēta~~ |
|~~!leave~~ | | ~~Vari pamest ruleti, kurā piedalies~~ |
|!link | | Vari pastīties YouTube linku no esošās dziesmas |
|!op | | links to the OverPlayed list (if set in the settings) |
|!ping | | pong! |
|!purchase | | returns link to purchase more plug notes |
|!rules | | links to the rules (if set in the settings) |
|!theme | | links to the room's theme (if set in the settings) |
|!thor | | users get moved to position 1 in the waitlist if they're worthy of Thor's hammer. |
|!website | | links to the room's website (if set in the settings) |
|!youtube | | links to the room's youtube page (if set in the settings) |

