# Zombie:Reloaded 3.0 Beta 2 Features #

## Key features ##
  * Extended classes for both humans and zombies. 28 attributes to customize. These are the key class features:
    * Special flags that will make the class a mother zombie class and/or admin-only class.
    * Group permissions to restrict classes to players in certain groups in SourceMod.
    * Model attribute support predefined filters for randomly selecting a model in a certain model group.
    * Model alpha settings (transparency).
    * Custom vision overlay per class.
    * Napalm grenades (humans).
    * Health regeneration.
    * Jump boost.
  * Model configuration with separate groups for zombies, humans, mother zombies, admins or a user defined SourceMod group.
  * Save player settings in cookies so they are restored next time they connect.
  * ZMarket that will let humans by weapons from both CT and T teams.
  * Detailed weapon configuration for restricting or scaling individual weapon knock back.
  * Hit group configuration where knock back can be scaled per body part, or completely disabled.
  * Customizable suicide prevention for both zombies and humans, and before/after infection.
  * Anti-stick to automatically unstuck players.
  * Volumetric features with a anti-camp and class editor feature. (Currently experimental)
  * Admin authentication to give either moderation access (infect, teleport, spawn, etc.) or full configuration access.
  * User manual with configuration specification and guides.

## Other features ##

  * Map configs.
  * Logging with log type and module filtering (to only log what you need).
  * Validation of configuration files to avoid invalid values that might cause unexpected plugin behavior.
  * Multiple mother zombies.
  * Round end overlays.
  * Visual effects like dissolving dead players, modifying sky and controlling fog.
  * Respawn control. Players can either be respawned as humans or zombies after the first infection.
  * Spawn protection.
  * Teleport with separate limits and delays. In addition a auto-cancel distance can be set to abort teleport on players who tries to run away.
  * HP display for zombies.
  * Re-join abuse prevention on players who tries to rejoin the game to spawn as human.