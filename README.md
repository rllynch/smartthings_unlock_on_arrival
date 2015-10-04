# smartthings_unlock_on_arrival
With the introduction of SmartThings Routines in the fall of 2015, it's possible to use a routine to unlock a door when someone returns home and SmartThings transitions from "Goodbye!" to "I'm Back!".  However, when a second person returns home, "I'm Back!" will not be called again, and the second person will be stay locked out. This simple SmartApp solves this issue and unlocks a door whenever anyone returns home.

# Usage
1. Log into https://graph.api.smartthings.com/ and under My SmartApps, create a new SmartApp with the code in smartthings_unlock_on_arrival.groovy.
2. Open the SmartThings app, click on the Marketplace icon in the bottom right corner.
3. Select the SmartApps tab, choose My Apps from the bottom, and choose Unlock On Arrival.
4. Choose which presence sensors returning home should unlock the lock, then choose which lock(s) to unlock.
5. Tap Done in the top right corner to install.
