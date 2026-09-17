```markdown
# kriva-pohadka-data

Repozitář obsahuje operační systém pro práci s významem. Není to dataset v běžném smyslu. Je to struktura, která se učí.

## Struktura

```

```
repodum/
├── readme.md
├── system_prompt.json
└── doma/
    ├── angles/
    │   ├── topology.json
    │   ├── poruchy_uhly_v1.json
    │   └── v1.json
    ├── poruchy/
    ├── ilustrace/
    │   ├── mys.jpg
    │   ├── netopyr.jpg
    │   ├── ryba.jpg
    │   ├── pavouk.jpg
    │   ├── zajic.jpg
    │   ├── kocour.jpg
    │   ├── pav.jpg
    │   ├── motyl.jpg
    │   ├── krokodyl.jpg
    │   ├── cap.jpg
    │   ├── osel.jpg
    │   ├── jednorozec.jpg
    │   ├── kravy.jpg
    │   ├── zralok.jpg
    │   ├── vlk.jpg
    │   ├── panda.jpg
    │   ├── lemur.jpg
    │   ├── plamenak.jpg
    │   ├── had.jpg
    │   ├── tygr.jpg
    │   ├── liska.jpg
    │   ├── prase.jpg
    │   ├── hvezdice.jpg
    │   ├── drak.jpg
    │   ├── veverka.jpg
    │   └── zelva.jpg
    ├── kriva_pohadka/
    │   ├── mys.txt
    │   ├── netopyr.txt
    │   ├── ryba.txt
    │   ├── pavouk.txt
    │   ├── zajic.txt
    │   ├── kocour.txt
    │   ├── pav.txt
    │   ├── motyl.txt
    │   ├── krokodyl.txt
    │   ├── cap.txt
    │   ├── osel.txt
    │   ├── jednorozec.txt
    │   ├── kravy.txt
    │   ├── zralok.txt
    │   ├── vlk.txt
    │   ├── panda.txt
    │   ├── lemur.txt
    │   ├── plamenak.txt
    │   ├── had.txt
    │   ├── tygr.txt
    │   ├── liska.txt
    │   ├── prase.txt
    │   ├── hvezdice.txt
    │   ├── drak.txt
    │   ├── veverka.txt
    │   └── zelva.txt
    ├── zaznam_trening_tygr.json
    ├── priklady.json
    ├── gap.json
    └── multimedialni_bloky_priklady_z_uhly_v1.json

```



```
## Instrukce

- `doma/angles/v1.json` – jsou jen příklady.
- `doma/angles/topology.json` – číslo 12 není dogma, je to jen příklad použití. Jde o kruh a vztahy. Protilehlé jsou opačné, sousední podobné.
- `doma/gap.json` – Gap je mezera, odlišující jeden význam od jiného. Není to nic, co nic nedělá. Je to prostor, ve kterém se děje význam. Můžeš ho použít jako vlastní prostor pro tvorbu i přemýšlení, pro přenos mezi médii, nebo pro vlastní volné místo jako takové. Nefunguje samo o sobě ve vakuu. Musíš tam pracovat s tím, co v kontextu máš. Nemusíš ho použít vždy povinně. Musíš ale uvést, když ho použiješ. A na doptání bys měl být schopný popsat, jak jsi ho právě použil.
- Mezera pro trénink je v ilustraci mezi obrazem, na kterém je vždy dívka představující jazyk a řeč, a zvířetem, které je její poruchou. A mezi ručně kresleným textem, který je autonomní složka jako obraz – texty se nepopisují, tvoří celek i s tou mezerou. Ta mezera je třetí autonomní složka a jako fyzický objekt existuje jako `gap.json`.
- `doma/poruchy.json` – poruchy nejsou chyby k opravě. Jsou to vlastní entity v podání zvířete. Jazyk není popis, ale materiál.

