# Rezsikövető – kipróbálható demó

**▶ Kipróbálás: https://gyuszko55.github.io/rezsikoveto-demo/**

A **Rezsikövető** Home Assistant-integráció a háztartás villany-, gáz-, víz- és szemétszállítási költségeit számolja a magyar
lakossági díjszabások szerint, mérőállásokból és számlákból, forintra pontosan:

- átalány és éves egyenleg, kedvezményes keret, sávkorrekció
- H-tarifa két regiszterrel (téli 1.81 / nyári 1.82)
- napelemes szaldó és bruttó elszámolás (1.8.0 / 2.8.0)
- számla-ellenőrzés reklamáció-tervezettel, éves elszámolási kimutatás, fizetések és határidők
- szigetüzemi energiamérleg (kísérleti, csak kWh)
- indítókártya az irányítópultra: vonalas ház a kifizetetlen számlák összegével, benti/kinti hőmérséklettel, fűtéskor füsttel

A demó a valódi panel, **kitalált otthonok generált adataival** (kertes ház, fonyódi nyaraló, újbudai bérlakás). Minden megnézhető és kipróbálható,
de módosítani nem lehet (mérőállás, számla, fizetés, mentés). Személyes adatot nem tartalmaz.

**Állapot:** fejlesztés alatt, még nem telepíthető. Ez a tároló csak a demó-oldalt tartalmazza, az integráció forráskódját nem.

---

© 2026 Gyuszko55, Krissz55555. **Minden jog fenntartva.** A demó-oldal és a benne lévő kód kizárólag megtekintésre szolgál;
másolása, visszafejtése, módosítása, terjesztése vagy más célú felhasználása a szerzők írásos engedélye nélkül nem megengedett.
A számítás tájékoztató jellegű, a szolgáltatói számlát nem helyettesíti.
