# recroom-metadata
global-metadata.dat for each custom build of RecRoom

Place the modified `global-metadata.dat` into a folder named the SHA1 hash of the corresponding `GameAssembly.dll`.

YARNS (and possibly other standalone RecNet servers) can download these and place them into `<RecRoom_Data,Recroom_Release_Data>/il2cpp_data/Metadata/` after renaming the original in order to point the game to a different server.

Please include a text document in the folder that includes the modified strings & their original/previous strings.
