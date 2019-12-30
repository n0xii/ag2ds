# a Adrenaline Gamer 2 Dedicated Server Installation Tutorial 
### Follow the steps carefully:

*  Download AG2 from either [ModDB](https://www.moddb.com/mods/adrenaline-gamer-2/) or [my github](https://github.com/n0xii/ag2).

*  Download Source SDK Base 2007 from steam.

*  Copy the folder "ag2" into Steam\steamapps\common\Source SDK Base 2007\

*  Create a .bat file containing this code:
```
srcds.exe -game ag2 -port 27015 +maxplayers 10 +map pg_lockdown
```

* Run the .bat file you created to launch the server. 
