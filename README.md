# Mineline Create

Klientpakke for Create-serveren på Mineline (`create.129.241.100.225.nip.io`).

<p align="center">
  <a href="https://modrinth.com/app"><img alt="Last ned Modrinth App" src="https://img.shields.io/badge/1.%20Last%20ned-Modrinth%20App-1bd96a?style=for-the-badge&logo=modrinth&logoColor=white" height="44"></a>
  &nbsp;
  <a href="https://github.com/jotjern/mineline-create/releases/latest/download/Mineline-Create.mrpack"><img alt="Last ned Mineline-Create.mrpack" src="https://img.shields.io/badge/2.%20Last%20ned-Mineline--Create.mrpack-f59e0b?style=for-the-badge&logo=github&logoColor=white" height="44"></a>
</p>

<p align="center">
  3. Åpne <code>Mineline-Create.mrpack</code> i Modrinth App → trykk <b>Play</b> → koble til <code>create.129.241.100.225.nip.io</code>
</p>

| | |
|---|---|
| Minecraft | 1.21.1 |
| Modloader | NeoForge 21.1.256 |
| Mods | Create 6.0.10, Create Aeronautics 1.3.2, Create Nuclear 2.0.0, CC: Tweaked 1.120.2, JEI 19.57.0.451, MezzConfig 0.6.8, Sable 2.0.6 |

Versjonene er de samme som på serveren. Med andre versjoner blir du avvist med
«incompatible».

Har du allerede en eldre versjon av pakken: last ned på nytt og importer, eller
oppdater profilen i launcheren.

## Wiki og hjelp

- [Create-wiki](https://wiki.createmod.net/) – maskiner, kinetikk, tog
- [Create Aeronautics](https://modrinth.com/mod/create-aeronautics) – luftskip og flygende kontraptions
- [Create Nuclear-wiki](https://wiki.createnuclear.net/wiki) – reaktorer, brensel og stråling
- [CC: Tweaked-dokumentasjon](https://tweaked.cc/) – Lua-API for datamaskinene
- I spillet: hold **W** over en Create-gjenstand for Ponder-animasjoner, og bruk JEI for oppskrifter

## Installering

### Modrinth App (enklest)

1. Installer [Modrinth App](https://modrinth.com/app).
2. Last ned [`Mineline-Create.mrpack`](https://github.com/jotjern/mineline-create/releases/latest/download/Mineline-Create.mrpack).
3. Dobbeltklikk filen, eller dra den inn i Modrinth App. Den lager en ny profil
   med riktig Minecraft-versjon, NeoForge og alle modsene.
4. Trykk **Play**.

### Prism Launcher

1. Installer [Prism Launcher](https://prismlauncher.org/).
2. **Add Instance → Import** og velg `Mineline-Create.mrpack` (eller lim inn
   nedlastingslenken).
3. Logg inn med Microsoft-kontoen din og start profilen.

### CurseForge eller annen launcher

Lag en profil for **Minecraft 1.21.1** med **NeoForge**, og legg disse i
`mods`-mappen:

- [Create 6.0.10](https://modrinth.com/mod/create/version/UjX6dr61)
- [Create Aeronautics 1.3.2](https://modrinth.com/mod/create-aeronautics/version/44pLdPGg)
- [Sable 2.0.6](https://modrinth.com/mod/sable/version/fg9dTRz9)
- [Create Nuclear 2.0.0](https://modrinth.com/mod/createnuclear/version/TANOhO2C)
- [CC: Tweaked 1.120.2](https://modrinth.com/mod/cc-tweaked/version/1ewzHZYg)
- [JEI 19.57.0.451](https://modrinth.com/mod/jei/version/RI8WCow6)
- [MezzConfig 0.6.8](https://modrinth.com/mod/mezzconfig/version/idpM3DKC)

## Koble til

«Mineline Create» står allerede i serverlisten i profilen. Ellers legger du til:

```
create.129.241.100.225.nip.io
```

Denne adressen sender deg rett til Create-serveren. Med modpakken kan du **ikke**
bruke den vanlige adressen (`129.241.100.225`): lobbyen og survival kjører ikke
NeoForge, så du får «You are trying to connect to a server that is not running
NeoForge».

Vanlig survival og lobbyen (26.3) spiller du med vanlig Minecraft, uten denne
pakken.
