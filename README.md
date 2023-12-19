<div align="center">
   <img src="https://i.imgur.com/BMpvtWP.png">
</div>

## Releases
- [Download latest stable AutoPlug-Client.jar.](https://github.com/Osiris-Team/AutoPlug-Releases/raw/master/stable-builds/AutoPlug-Client.jar)
- [Download latest beta AutoPlug-Client.jar.](https://github.com/Osiris-Team/AutoPlug-Releases/raw/master/beta-builds/AutoPlug-Client.jar) 



## Steps (first install)
The recommended/easiest way of installation is via the installer at https://autoplug.one/installer.
If you don't want to, follow the steps below:
- If you want to test it first or create a new server, put the jar into a new empty directory. Otherwise put it into 
the same directory as your server executable (server jar).
- Create a start script with `java -Dfile.encoding=UTF-8 -jar AutoPlug-Client.jar` inside, run it and you are done.

<details>
<summary>Show/Hide scripts</summary>

Linux/Unix:
```sh
mkdir my-server
cd my-server
curl -o AutoPlug-Client.jar https://github.com/Osiris-Team/AutoPlug-Releases/raw/master/beta-builds/AutoPlug-Client.jar
java -Dfile.encoding=UTF-8 -jar AutoPlug-Client.jar
```

Windows:
```
mkdir my-server
cd my-server
bitsadmin /create myjob
bitsadmin /addfile myjob https://github.com/Osiris-Team/AutoPlug-Releases/raw/master/beta-builds/AutoPlug-Client.jar .\AutoPlug-Client.jar
bitsadmin /info myjob
java -Dfile.encoding=UTF-8 -jar AutoPlug-Client.jar
```

Each line explained:
1. Create a new directory at your current location
2. Go into the new directory
3. Download the jar
4. Start the jar
</details>

## Steps (install update)
Updating AutoPlug is pretty easy if you have the self-updater enabled (it is by default), so update by...
- ...waiting for your server to restart.
- ...entering .r to restart your server.
- ...manually by downloading the jar and replacing the existing one with it.

## Notes
- This is the only, official downloads repository. Do not download for anywhere else.
- Beta releases contain experimental, poorly tested features, which may not work properly.

## Links
    
<div>
   <p>
      <a href="https://github.com/Osiris-Team/AutoPlug-Releases">AutoPlug-Releases</a> |
      <a href="https://github.com/Osiris-Team/AutoPlug-Client">AutoPlug-Client</a> |
      <a href="https://github.com/Osiris-Team/AutoPlug-Plugin">AutoPlug-Plugin</a> |
      <a href="https://bit.ly/acprogress">AutoPlug-Client-Development</a> |
      <a href="https://bit.ly/approgress">AutoPlug-Plugin-Development</a> |
      <a href="https://www.spigotmc.org/members/osiristeam.935748/">Spigot</a> |
      <a href="https://discord.com/invite/GGNmtCC">Discord</a>
   </p>
</div>
