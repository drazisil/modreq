# All permissions

Some of the permission nodes have changed in the 2.4 update. All of them can be found here, including descriptions.

By default people get the following permissions:

* `modreq.mods`
* `modreq.request`
* `modreq.status` 
    
    This permission allows them to see what people with the modreq.check permission are online, as well as submit a ticket and check the status of it. 

All of the other permissions are given to people with OP by default. These permissions are:

* `modreq.check`
  
  Allows a person to do /check and /check id. Also makes a person appear in the /mods list 
* `modreq.claim.normal`
        
    Allows a person to claim open tickets. 
* `modreq.claim.pending`
   
   Allows a person to claim pending tickets. 
* `modreq.setpending`
   
   Allows a person to set a ticket to pending. If a ticket is set to pending people without the modreq.claim.pending permission will not see the ticket in the /check list. They will also not be able to claim it 
* `modreq.close`
   
   Allows a person to close a ticket they claimed. 
* `modreq.reopen`

    Allows a person to reopen any ticket. This will change in the next update (2.5) 
* `modreq.overwrite.claim`

    Allows a person to claim any ticket, even if it is claimed by another staff member 
* `modreq.overwrite.close`

    Allows a person to force close a ticket. 
* `modreq.overwrite.commentlimit`

    Allows a person to overwrite the commentlimit defined in the config.yml 
* `modreq.update`

    Allows a person to download the latest version of ModReq into the modreq folder. This does not install the latest version! 
* `modreq.cleartickets`
    
    Allows a person to delete all the tickets, even if the ticket has not yet been closed. (This will most likely change in version 2.5) 
* `modreq.reload`

    Allows a person to reload ModReq 

Last but not least I added these permissions to make it easier to setup.

* `modreq.moderator`

    This enables a person to do `/check`, as well as claim open tickets, teleport to tickets, set tickets to pending and close tickets they claimed. 
* `modreq.admin`

    This gives people the `modreq.moderator` permissions, but also allows them to reopen tickets. On top of that they get all the overwrite permissions and can claim pending tickets.

