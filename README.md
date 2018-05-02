# lib_savevars

[Minetest Mod] Registers in file ````variables.tbl```` on LuaScript language the global variables and character variables that can be queried by other mods and by server administrator commands.

**Dependencies:**
 * ---- There are no dependencies ----

**Licence:**
 * [GNU AGPL v3.0](https://github.com/Lunovox/lib_savevars/blob/master/LICENSE)

**Developers:**
 * [Lunovox Heavenfinder](https://libreplanet.org/wiki/User:Lunovox)

**Automatically saved player info:**
 * last_ip ← Last IP that the player had when connecting to the server.
 * listed_ip ← All IPs that the player used to connect to the server.
 * last_login ← Records the time the player last logged in the server in integer numerical format "os.time" of Luacript.
 * last_logout ← Registers the moment the player last logged out on the server in integer numeric format "os.time" from Luacript.
 * time_played ← Records the total time in seconds in the integer numeric format "os.time" of Luacript that the player has been logged into the server.
 
 **Administrator Commands:**
 
