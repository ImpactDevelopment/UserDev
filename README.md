# Vanilla UserDev

This is a userdev jar for use with forgegradle projects that wish to work directly on modlauncher, rather than using Forge.

Add a maven repo containing builds from this project and then add `minecraft net.impactclient:userdev:${minecraft.version}` to your dependencies.

## TODO

- [x] Fork forge's [userdev launch class](https://github.com/MinecraftForge/MinecraftForge/tree/734a3d76aa738b25e134789cb1305cc0c7c44e37/src/userdev/java/net/minecraftforge/userdev)
- [x] Correctly build a patch/userdev jar
  - [ ] Double check
- [ ] Add a publish task to send builds to maven
- [ ] Consider changing package name (maybe use `net.minecraft:userdev` or `net.minecraft:vanilla` or `net.minecraft:modlauncher` or something)
- [ ] Auto detect version from git tag or env or something
