# Victron Thethinbox
Monitor Victron Multiplus inveter using the Mk2 Usb interface on Thethingbox.io raspberry and log to emoncms.org

1. Install http://thethingbox.io
2. Setup account on emoncms.org (or setup on local server)
3. Paste node red code (Settings->import->clipboard)


Bottom of the screen logs to local server, if you don't have one, just delete those nodes
If don't want to log to online, just remove that nodes as well

### Default settings

Log every 10 seconds to emoncms.org  (simple time check delay before posting online)
Log every 1 second to local 

