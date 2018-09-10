Bugs:
-update E-Mail feature
-and many more

Echelon v.2 is a Big Brother Bot project that it is currently under development. Echelon is a web investigation tool for B3 administrators to study detailed statistics and other helpful information: about the B3 bot; game server clients; and admins. Echelon v.2 is not all about just inspecting information, it is also about interacting with the B3 bot; the gameserver; and the B3 MySQL databse.

## Echelon Development v2 ##
All the files are copyrighted by Eire.32 (eire32designs.com) and Bigbrotherbot (bigbrotherbot.com)

# Echelon is a web interface for the B3 administator program for gameservers.

# This is a is a developing version of Echelon
# It is nearly finished but there are still a few features not finished, and errors/bugs not solved
# The Dev. Team are no offering any support other than this readme
# Currently the version here is changing at least once a week, so 'updates' are frequent enough

## Requirements ##
- Webserver (Aphace currently, other support coming soon)
- Version 5+ PHP
- MySQL DB (your B3 DB will work, but a seperate  one is advised)
- A MySQL user with connection rights to your B3 databases
- RCON details for the servers running B3 (RCON support is currently being phased out of Echelon)

## Installtion ##
// This is by no means a comprehensive guide, it is a quick guide to get any of you started
- Create a MySQL user to connect your B3 database from your Webserver
- Run the echelon.sql file on your database to create the Echelon tables
- Go to http://example.com/path/echelon/ and follow the installer
- Delete the install folder once the web installer is done
- Login to Echelon using the credentials that were emailed to you
- Setup and config your Echelon to your needs

## NOTE ##
Please understand that there are large portions of Echelon that are unfinished. Please check back to this repo for the latest version.
There is also spotty support for BFBC2, (rcon will not work and will most likely error)
