# Kingdom Storage Tracker

Een **client-side Fabric-mod** voor Minecraft **1.21.4** die de inhoud van kisten (en barrels/shulkers)
bijhoudt in een centrale database, met een handige in-game viewer. Ideaal om op een kingdom-/survival-server
te weten *wat er waar ligt* — boeken, enchants, gear, potions en meer.

> **Download de nieuwste versie** uit
> [de Releases van deze repo](https://github.com/yannickbm/kingdom-storage-mod-atla/releases)
> en zet 'm in je `mods`-map.

---

## Wat het doet

- 🧭 **Kisten volgen**: selecteer een kist met een **Nautilus Shell**; de inhoud wordt gelogd zodra je 'm opent.
- 🔎 **In-game viewer**: bekijk alle gevolgde items in een inventaris-achtig scherm met **zoeken**, sorteren op
  afstand, item-iconen, duurzaamheid en **klik-om-de-kist-in-de-wereld-te-markeren** (ook door muren, incl.
  dubbele kisten).
- ✨ **Enchants, custom namen, potions, trim & lore** worden herkend en zijn doorzoekbaar
  (bijv. `sharpness 5` of `sharpness v` toont alleen level 5).
- 👑 **Kingdoms + rollen**: kisten horen bij een kingdom; rechten worden server-side afgedwongen.
- 🔄 **Altijd actueel**: open je een kist, dan werkt de mod de inhoud automatisch bij voor elk kingdom dat die
  kist volgt en waar jij lid van bent.

---

## Vereisten

| Nodig | Versie |
|---|---|
| Minecraft | **1.21.4** |
| Fabric Loader | **0.16.0** of hoger |
| Fabric API | nieuw genoeg voor 1.21.4 |
| Java | **21+** |

Dit is een **client-side** mod: je installeert 'm in je eigen Minecraft, niet op de server.

---

## Installatie

1. Installeer **Fabric Loader** (0.16.0+) voor Minecraft 1.21.4.
2. Zet **[Fabric API](https://modrinth.com/mod/fabric-api)** in je `mods`-map.
3. Zet de nieuwste `kingdom-storage-tracker-x.y.z.jar` erbij in je `mods`-map.
4. Start Minecraft met het Fabric-profiel.

---

## Gebruik

- **Viewer openen**: stel een toets in via **Opties → Besturing → "Kingdom Storage"** (standaard niet
  gebonden), of **rechtermuisklik met de Nautilus Shell** in de lucht.
- **Kist volgen/ontvolgen** (admins): **sla een kist met de Nautilus Shell**. Nog eens slaan = ontvolgen
  (de gegevens van die kist worden dan verwijderd).
- **Inhoud bijwerken**: open simpelweg een gevolgde kist — de inhoud wordt automatisch gelogd/bijgewerkt.

---

## Rollen

- **Lid (member)** — kan gevolgde kisten bijwerken door ze te openen; geen beheer.
- **Kingdom-admin** — beheert z'n eigen kingdom (leden, rollen) en bepaalt welke kisten gevolgd worden.
- **Hoofd-admin** — kan alles, overal: kingdoms aanmaken/beheren, hoofd-admins toewijzen, enz.

---

## Versies

De nieuwste `.jar` staat altijd in de
[Releases van deze repo](https://github.com/yannickbm/kingdom-storage-mod-atla/releases).
Spelers hebben enkel die losse download nodig; de server-kant hoeft niet per speler bijgewerkt te worden.
