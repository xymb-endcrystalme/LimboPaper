# LimboPaper - Paper optimized for queue plugins

Disabled chunk and entity ticking
Disabled player ticking
Disabled time progression
Disabled achievements
Disabled join/leave messages

Most serverbound packets are ignored, chat is the only way for a player to interact with the server.

LimboPaper sends chunks to players, it just ignores thier actions. You can make a lobby that looks some way, but can't be interacted with.

## Compiling

```
./gradlew applyPatches
./gradlew createReobfPaperclipJar
```

Your compiled .jar will be in `build/libs/`.
