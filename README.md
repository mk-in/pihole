# pihole

This repo is intended to hold personal categorized adlists. The idea is to create separate blocklists for porn, games, entertainment etc. These are best used with the group management feature 

Blocklists are segregated into 2 folders
-adlists
-parentalControl

## adlists
These lists are for general ad blocking, anti tracking etc


## parentalControl
These contain categorized block lists. Use it with group management to control at device level.
- Gaming
- Media
- Porn
- Other


## regex
Pihole does not support regex in adlists. Hence a separate file with regex. Bulk copy the regex you want into your clipboard, then paste those contents into the regex entry page (admin GUI > group Management > domains > regex)
