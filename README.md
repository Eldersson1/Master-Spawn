# **Master Spawn**
Master Spawn is useful datapack that adds spawn command without any plugins or mods.  
# **Commands**
Public spawn command. 
```
/spawn
```
Setspawn command for admins. 

```
/setspawn
```
Reload command for admins
```
/masterspawn admin reload
```
# **Permissions**
**Reload command**
```
masterspawn.admin
```
**Spawn command**
```
masterspawn.spawn
```
**Setspawn command**
```
masterspawn.setspawn
```
# Config
<details>
<summary>config.yml</summary>

```
# Delay in seconds before teleporting to spawn
delay: 3
```

</details>

<details>
<summary>messages.yml</summary>

```
messages:
  spawnSet: "&aSpawn location set!"
  noPermission: "&cYou don't have permission to use this command."
  notPlayer: "&cThis command can only be run by a player."
  teleporting: "&aTeleporting in &l%d &r&a seconds... &cDon't move!"
  movementDetected: "&cMovement detected, teleport cancelled!"
  teleported: "&aTeleported to spawn!"
  spawnNotSet: "&cSpawn location not set yet!"
  configReloaded: "&aConfiguration reloaded!"
```

</details>




