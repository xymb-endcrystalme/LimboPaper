# LimboPaper - Paper optimized for queue plugins

Why not something like [Limbo](https://github.com/LOOHP/Limbo)? It's bound to be faster, but it's not compatible with Bukkit plugins.

On LimboPaper basically all of your queue Bukkit plugins will work.

# Features

* Disabled chunk and entity ticking
* Disabled player ticking
* Disabled time progression
* Disabled achievements
* Disabled join/leave messages
* Most serverbound packets are ignored, chat is the only way for a player to interact with the server.
* LimboPaper sends chunks to players, it just ignores thier actions. You can make a lobby that looks some way, but can't be interacted with.

## Compiling

```
./gradlew applyPatches
./gradlew createReobfPaperclipJar
```

Your compiled .jar will be in `build/libs/`.
