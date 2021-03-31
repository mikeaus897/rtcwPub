The folders and files here are "extra" server files. These are files that aren't required to start and run a server, but may enhance the quality (slightly) of your server, if they apply.
In order for any of these folders to be used, they have to be placed in a main folder.

botfiles:
Files for running q3 bots in wolf dm. Most, if not all, of the files are settings and characteristics for the bots. They define how the bots act.

dmscripts:
.script files that are for deathmatch only (g_deathmatch set to 1). These scripts are used to remove certain obstacles and objectives from maps that do not apply to deathmatch, or may even make playing deathmatch impossible.

maps:
.spawns files contain entities that you want to spawn into the world on map load (g_customSpawns must be set to 1). The file name is the map name that the spawns are for (i.e. mp_base.spawns). There are two different types of .spawns files; normal ones (g_customSpawns) and those ending in _ffa. The ones ending in _ffa are loaded automatically if g_ffa is set to 1.
.rts files are for the bots. The entries within that file are routes that help the bots get around a bit better.

scripts:
More bots stuff. The bots.txt file tells the bot system which of the bots can play in the server (i.e. Doom, Daemia, etc..).

main:
All of the above folders as well as .cfg files for the server.