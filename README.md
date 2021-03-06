## Baskit, the next generation

These are the voyages of the Minecraft server wrapper, it's mission to seek 
out new servers and minecraft communities, and to boldly run minecraft where
no one has before

### What is Baskit?

Baskit is a UNIX-specific Minecraft Server manager.  It uses a screen session to detach the server from the main console, but still allow for interactivity.

### Usage Instructions

* Run baskit help for usage instructions.
* [Video Tutorial](http://www.youtube.com/watch?v=DBM1LF93O4k) - YouTube Link


### Installation Instructions

* Install pre-reqs: screen & java
* Install Baskit via pip or easy_install: pip install baskit
* Create a base location for your minecraft server (e.g. /opt/minecraft): mkdir /opt/minecraft
* Change into the new directory: cd /opt/minecraft
* Run baskit to create the directory structure: baskit server
* Optional: Move baskit.conf to /etc or to ~/.baskit.conf
* Optional: adjust the environment line in baskit.conf to match your base folder (e.g. /opt/minecraft)

### Migrating an existing installation into baskit

* Once you have the baskit base structure in place, its simply a matter of copying your server data into the env folder. (e.g. /opt/minecraft/env)
* Also, either modify the binary config line or rename your existing server binary to server.jar

NOTE: you can also modify the server_* config lines to match your existing server binary's, as they will not be updated until you update the server within baskit.

### Status

__Whats Working__:

* Most Everything

__ToDo__:

* BukGet Plugin management support.
