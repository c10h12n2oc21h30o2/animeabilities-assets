# animeabilities-assets

Archivos que los clientes de Minecraft descargan para AnimeAbilities (cuyo repo es privado). Este repo es público solo
por eso.

- `packs/AnimeAbilities-pack-<sha1>.zip`: cada versión del pack Java, con su SHA-1 en el nombre, para que ningún cliente
  ni la caché de GitHub sirvan una versión vieja. El plugin apunta a ella con `pack.url` y `{sha1}`:
  `https://raw.githubusercontent.com/c10h12n2oc21h30o2/animeabilities-assets/main/packs/AnimeAbilities-pack-{sha1}.zip`
- `AnimeAbilities-pack.zip` (+ `.sha1`): la última versión, para descargarla a mano.
