<p align="center">
  <img src="pictures/natsuki.png" width="200" alt="Natsuki">
</p>

<h1 align="center">NatsukiClient</h1>

<p align="center">A 1.21.4 "hvh" multiserver client built because there arnt any good free clients out there.</p>

---

## what is it

its a fabric client for 1.21.4 made by zire. its pink, its free, and it doesnt look like every other skidded client out there. everything is drawn with our own renderer (NatsukiRender) so the gui and hud are smooth, frosted and actually readable

works on modern servers and on 1.8 servers through viafabricplus (its already bundled in so you dont need to grab it)

### stuff it just, does.
- entity culling so entities behind walls dont get rendered
- sodium and lithium are bundled in for fps
- fabric api is bundled in too so its just one jar

## clickgui

press **right shift** to open it. left click a module to toggle it, right click to open its settings. you can drag the window around by the top bar

## installing

1. install [fabric loader](https://fabricmc.net/use/) for 1.21.4
2. drop the jar in your mods folder
3. thats it, fabric api sodium lithium and viafabricplus are already inside the jar

## building

you need java 21

```bash
./gradlew build
```

the jar ends up in `build/libs/`

## credits

- made by zire
- [Sodium](https://modrinth.com/mod/sodium), [Lithium](https://modrinth.com/mod/lithium) and [ViaFabricPlus](https://modrinth.com/mod/viafabricplus) are bundled and belong to their own devs, check their licenses before you redistribute
- [Poppins](https://fonts.google.com/specimen/Poppins) font is under the OFL
- and claude for lwk making this readme just a tad bit
## disclaimer

using this on servers will probably get you banned, thats on you. dont use it where you arnt allowed to
