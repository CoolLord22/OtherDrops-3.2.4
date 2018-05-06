OtherDrops
==========

OtherDrops is a plugin for the Minecraft Bukkit API that lets you completely
customize what blocks and dead mobs drop when they are destroyed. Apples from
leaves, no more broken glass, and much, much more.

OUTDATED: Please see the project page for full details here: <https://dev.bukkit.org/projects/otherdrops>

Please see the spigot page for more download information here: <https://www.spigotmc.org/resources/otherdrops-updated.51793/>

Building from source
--------------------

These instructions assume you have already forked and/or cloned the project and have on your computer.

Change the plugin.yml (as generated by plugin.yml.template) to fix the version, potentially by adding your name with a dash (3.1.3-Name)

OtherDrops comes with most dependencies already stored in the repository (for simplicity) however
you need to download a Bukkit build and place into the `lib` folder - rename it to `bukkit.jar`

Then build using your IDE or:

    $ ant jar

Use `ant -p` to see a complete list of Ant tasks.
