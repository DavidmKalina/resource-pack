# Server resource pack

The resource pack for my Minecraft server (26.3, pack format 97). The server's ResourcePack plugin sends players the
link to `resource-pack.zip` when they join, so there's nothing to install by hand.

`resource-pack.zip` is built from the `pack/` folders of the server's plugins by `resource-pack/tools/build_pack.py`;
don't edit it by hand. What's in it:

- `assets/fierywings/`: the fiery elytra wings worn with a Fiery Winged Chestplate (FieryWings plugin)
- `assets/ghastbreath/`: a happy ghast that has had dragon's breath looks like a regular ghast, with or without a
  harness (GhastBreath plugin)
- `assets/inventory/` and `assets/minecraft/items/iron_chain.json`: two crossed chains on /tidy auto's Priority frames
  (an iron chain with custom model data `tidy_priority`; ordinary chains look as usual)
- `assets/minecraft/textures/`, `assets/minecraft/lang/`: beetroots look like bananas (green while growing, yellow
  when ripe) and are called Banana, Banana Seeds and Bananas; beetroot soup is "Cumpot", a cheesecake gone wrong
- `assets/ctweaks/`: models for the extra slabs and stairs of the CraftingTweaks plugin
- `assets/worldevents/`: textures for the items the server's events drop (WorldEvents plugin)
- `assets/jackolanterns/` and `assets/minecraft/blockstates/`: placed jack o'lanterns and carved pumpkins get a random
  face. The faces are from [More Jack-o-Lantern Faces (Pumpkin Pack)](https://www.planetminecraft.com/texture-pack/more-jack-o-lantern-faces/)
  on Planet Minecraft, credit ImagineerSkyy
