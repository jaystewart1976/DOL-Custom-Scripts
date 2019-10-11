DoL-Custom-Scripts
Dawn of Light - Dark Age of Camelot Server Emulator (DOL)
DOL Server is a server emulator for the game Dark Age of Camelot written by the Dawn of Light community
It does the following:
Provides the network communication needed to allow a DAOC game client to connect to the server
Provides a database layer between the server and MySQL~SQLite to allow storage of characters, npcs, items and so on
Provides a persistent world framework for customisation of game rulesets and behaviours

Latest Release 1.109 client: https://github.com/Dawn-of-Light/DOLSharp/releases/latest
Latest Release 1.124+ client: https://github.com/Los-Ojos/DolServer-1124
How To Use
Just copy the working folder for the version of DOL you are using to: dolserver/scripts/customnpcs and start server like usual.
BPTransferNpc.cs needs 1 code change to work on both versions
GamePlayer.cs line 187 change: internal DOLCharacters to: public DOLCharacters.
Then save file and recompile DOLServer

•	Coding: Wiki Home
