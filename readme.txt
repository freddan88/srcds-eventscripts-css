Author: Fredrik Leemann

Links:
------
WebPage: http://www.leemann.se/fredrik
Donate: https://www.paypal.me/freddan88
YouTube: https://www.youtube.com/user/FreLee54
GitHub: https://github.com/freddan88

Download:
http://www.leemann.se/fredrik/file_downloads/srcds_eventscripts-css.zip

Mattie eventscript
http://mattie.net/cs

####################

I take no responsibility for this script, use at your own risk

----------------------

This scriptpack includes 3 scriptfiles to use with Mattie eventscript
All addons are tested in CentOS, Windows and are working for Counter-Strike Source

-------------------------------------------------------

cstrike\addons\eventscripts\end_motd


Unload addon: es_unload end_motd
Load addon: es_load end_motd

-------------------------------------------------------

cstrike\addons\eventscripts\quota

Description: 
Script to dynamically manage bot_quota based on players connected - Configuration in scriptfile
When there is 1 player 3 bots shall connect to the server 
When there are 2 players there shall be 2 bots on the server
When there are 3 players or above 3 there shall be no bots on the server

When you play ex gungame it can feel unfair if one team have one bot 
and the other team is represented by two humans, this script was made in an attempt to ease that.

Unload addon: es_unload quota
Load addon: es_load quota

Requires: eventscript

------------------------------------------------------

cstrike\addons\eventscripts\r_msg


Unload addon: es_unload r_msg
Load addon: es_load r_msg

Print messages in the chat every new round, configure in cstrike\addons\eventscripts\r_msg\es_r_msg.txt

Requires: eventscript

------------------------------------------------------

cstrike\addons\eventscripts\end_motd

Unload addon: es_unload end_motd
Load addon: es_load end_motd

Requires: eventscript, sourcemod, m3motd by KaOs (https://forums.alliedmods.net/showthread.php?t=66795)

Configuration:
Change "sm_motd_url" to the website you like to show in server.cfg

-----------------------------------
Display end off map motd to players
