All commands

General Commands

* Do `/comment <id> <comment>` to add a comment to a ticket
* Do `/mods` to see what mods are online (vanished players will not appear on this list)
* Do `/modhelp` to get the Help page 

For the normal player

* To file a ticket you can do `/modreq <message>`
* To check the status of your latest 5 tickets do `/status`
  * To check the info of 1 of your tickets do `/status <id>` 

For mods

* To get a list of all open tickets do `/check <page>`
    * You can also check claimed, closed and pending tickets by doing   `/check <closed / pending / claimed> <page>` 
* To check out a certain modreq you can either do `/check id <id>` or `/ticket <id>`
* To claim a modreq do `/claim <id>`
* To teleport to a modreq do `/tp-id <id>`
* To close a modreq do /done <id> <message
* To re-open a modreq do `/re-open <id> <message>`
* To set a ticket to pending do `/ticket setpending <id>`
    * Note that only people with the `modreq.claim.pending` permission can claim pending tickets, as well as see them in the normal `/check` list. They can still see the ticket using `/check pending` and `/check id`. That will be patched in the next update (2.5) 

For people with all the modreq permissions

* To reset the Database do `/cleartickets`
* To update modreq do `/updatemodreq`
* To reload modreq do `/modreload`