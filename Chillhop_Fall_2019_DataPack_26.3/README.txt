CHILLHOP ESSENTIALS - FALL 2019 | MINECRAFT JAVA 26.3 | FIXED
================================================================
UPDATED: fixed the minecraft:jukebox_playable recipe result and give function
from the outdated pre-1.21.5 object to the required song ID string.
The full track, custom texture, song definition, recipes and namespaces are unchanged.

INSTALL ON PAPER 26.3
1. STOP your Paper server completely.
2. DELETE the old ZIP from <server>/<world>/datapacks/:
   Chillhop_Fall_2019_DataPack_26.3.zip
3. Copy Chillhop_Fall_2019_DataPack_FIXED_26.3.zip into that datapacks folder.
4. Start the server. Check the console for datapack errors.
5. Players must enable Chillhop_Fall_2019_ResourcePack_26.3.zip, same as before.
6. As an operator in-game: /function chillhop:give_fall_2019
7. Put the disc into any regular jukebox.

SINGLEPLAYER
- Put the FIXED datapack ZIP in .minecraft/saves/<world>/datapacks/.
- Put the resource-pack ZIP in .minecraft/resourcepacks/ and enable it.
- Run /reload, then /function chillhop:give_fall_2019.

SURVIVAL CRAFTING (CRAFTING TABLE)
  [empty] [orange dye] [empty]
  [copper ingot] [music_disc_13] [copper ingot]
  [empty] [oak leaves] [empty]

CONTENTS
- Music disc: Chillhop Essentials - Fall 2019, full mix ~66:42.
- Item model and warm fall center-label texture.
- Datapack: song definition, shaped crafting recipe, give function.
- Resource pack: Ogg Vorbis sound file, sounds.json, item definition/model/texture.
- Namespace: chillhop | Song: chillhop:fall_2019
- No scheduled tick function, suitable for multiplayer.

MULTIPLAYER RESOURCE PACK
- Each player needs the resource pack. It can be hosted with a direct-download URL
  configured as resource-pack in server.properties.
- For reliable resource pack refreshes, set resource-pack-sha1 to the SHA-1 of the
  exact resource-pack ZIP (see below). resource-pack-id is optional; Minecraft
  warns and uses a default when omitted. These warnings do not prevent startup.

REPLACING AUDIO
- Inside the resource pack ZIP, replace assets/chillhop/sounds/records/fall_2019.ogg
  with Ogg Vorbis audio. Update song length_in_seconds in datapack if needed.
- Redistribute the updated resource ZIP and update its SHA-1 in server.properties.
- Ensure you have permission to distribute the track.

SHA-1 OF UNCHANGED RESOURCE PACK ZIP:
resource-pack-sha1=f17c1de66e27697426c72a8c97b73a66751c8f10
