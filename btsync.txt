	

    -------------------------------------------------------------------------------------------------------------------
                                                        What is BTSync?
    -------------------------------------------------------------------------------------------------------------------
    BitTorrent Sync by BitTorrent, Inc is a proprietary peer-to-peer file synchronization tool available for Windows, Mac, Linux, Android, iOS and BSD. It can sync files between devices on a local network, or between remote devices over the Internet via secure, distributed P2P technology. - Wikipedia
     
    -------------------------------------------------------------------------------------------------------------------
                                                       Setting up BTSync
    -------------------------------------------------------------------------------------------------------------------
    0)Follow every step. Seriously. Check it.
     
    1)Obtaining BTSync
            BTSync can be downloaded at the official site: http://www.bittorrent.com/sync/downloads
     
    2)Installing BTSync
            The installation should be pretty straight forward. Choose a location where you want to have the software installed. If it asks you to choose between standard or entering a secret already, choose "standard".
     
    3)Setting up the sync
            After you start BTSync you should see a simple GUI with Tabs on top labeled as
            "My Sync" - "Devices" - "Transfers" - "History" and "Preferences".
     
    3.0) Changing Device Name | Optional - highly recommended
            To have a maximum amount of privacy I suggest you to change the device name that can't be pointed to your nickname or personal informations. Hit the "Preferences"-Tab and search for "Device Name". You can enter whatever you like. I recommend to choose a random string of characters, one can be quickly obtained here: https://www.random.org/passwords/?num=1&len=24&format=plain&rnd=new
     
            Hit apply. A restart of the client is may needed.
     
     
    3.1) Setting up the folder
    Change to the "Folders"-Tab and hit "Add a Sync Folder". As secret enter "BLGUIZXK5IY2PTZ3VMLUXEZ2MAOY3RNW4" (without the " ofcourse). As folder select your ArmA3 folder within the Steam folder. It should look something like this:
    C:\Program Files (x86)\Steam\SteamApps\common\Arma 3
    Hit okay.
     
    Now you need to enable DHT. In My Sync, Right click on your SyncFolder and select Folder Info.
    Go to the Properties tab and tick 'Search DHT network'.
     
    If you already have the mods installed. Check the FAQ below - it should answer your questions about modified data.
    BTSync should start the syncing process automatically. It may take a while.
     
    3.2) Setting up ARMA3
    When the sync finishes you still have to install the 32 or 64 bit ACRE plugins for teamspeak. They are located in the "Readme" folder. For further information about setting up ACRE consult the ACRE tutorial found at http://pastebin.com/iZEkk8f0
     
    Further you still need to add the launch parameter to your arma installation. To do that, hit right click on arma3 in the steam list of games. Select "Properties" -> "Set launch options" and add in the end the following statement:  -mod=@a3gMP;@a3gCP;@A3MP;@a3gMaps
     
    4) Done
    You should now be ready to go. If you run into problems or have any other questions check the FAQ below.
     
    5) Status
    To check the status of your client against my host, goto http://176.28.15.153/a3g/btsync/ and enter your device ID. You will get some information about your client, the server and files that may be useful to find errors.
     
    -------------------------------------------------------------------------------------------------------------------
                                                     Frequently Asked Questions
    -------------------------------------------------------------------------------------------------------------------
     
    - What if I have modified files or want to modify files?
            If you already have modified files you need to backup the files before you start the sync and apply the changes after the sync has finished. You can apply any change you like and/or add more files after the sync has finished without it getting overriden/deleted. As long as the original file is not updated at our side it won't get updated. That also means if we update the file you made changes to, thos changes will be lost - therefor make backups of your modifcations (specially the userconfig folder).
     
    - Why do we use this?
            To simplify the installation process. To avoid people fucking it up, and to ditch Mega as hoster.
     
    - Do I have to use this Sync?
            Yes.
    - I can't write to my ArmA folder!
            Run BTSync as admin.
     
    - I still have a question!
            Check the unoffical BTSync FAQ here: http://forum.bittorrent.com/topic/17782-bittorrent-sync-faq-unofficial/
            If you still have questions: Google it.

