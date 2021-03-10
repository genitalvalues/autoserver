# autoserver
Automagically sets up optimized Minecraft server 

# dependencies
`wget`

`bash`

`java`

# installation
## \*nix
```
git clone https://github.com/quisys/autoserver
cd autoserver
./autoserver.sh
```

# usage
to start the sever, switch to the `minecraft-server` directory (i.e `cd ~/minecraft-server`) and run `java -jar server.jar --nogui`

to stop it, type `stop`

# please note
Notice: by using this software you agree to the Minecraft server EULA

Notice 2: This doesn't automatically forward your ports. If your friends can't join, the problem is 99.9% that you aren't forwarding the host port (usually 25565).  Google is your friend here.
