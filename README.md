# How to hide full your minecraft plugins

SOON BY ARTEFFKODS

There are 4 ways to view plugins:

1. Commands method: `/pl` `/bukkit:pl` etc.
2. Tab method: `/ver [TAB]` `/about <TAB>`
3. TAB method: [TAB]:{commands}
4. Query plugins method: `bukkit.yml`

![image](https://github.com/ArteffKod/hide-full-plugins/assets/68272364/3f2e6981-7cea-4336-8a02-f3c8ccd0a457)



How to fix `1, 2, 3` methods:

- Use [Plugin Hide](https://www.spigotmc.org/resources/plugin-hide-1-13-1-20-choose-which-commands-players-can-execute-and-see.68767/)
  - With this plugin you can disable methods `1, 2, 3` methods


  How to fix `4` method:

  - Go to the `bukkit.yml` and sarch `query-plugins: true` -> **`query-plugins: false`**
    - This prevents plugins from being requested via port (Default query port: `25565`)
    - Query [WEBSITE](https://mcsrvstat.us/)

There are several clients that use these methods, e.g.: [MeteorClient](https://meteorclient.com/)
A developer created an [plugin](https://www.spigotmc.org/resources/plugin-hide-1-16-1-20-hide-plugins-from-hacked-clients.112271/) specifically against the meteor client that helps hide plugins
The plugin can log packets sent by meteor clients, so you can see if someone tries to use the methods

![image](https://github.com/ArteffKod/hide-full-plugins/assets/68272364/93e8488d-7067-44bc-8915-d03826d15007)

