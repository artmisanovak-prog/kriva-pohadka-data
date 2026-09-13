```markdown
# kriva-pohadka-data

Repozitář obsahuje operační systém pro práci s významem. Není to dataset v běžném smyslu. Je to struktura, která se učí.

## Struktura

```
| cesta | značka | co to je |
|---|---|---|
| `repodum/` | root | kořen repozitáře |
| `repodum/readme.md` | rozcestník | instrukce pro model i pro lidi |
| `repodum/system_promt.json` | odkaz | ukazuje na readme.md |
| `repodum/doma/` | domov | hlavní složka, kde bydlí systém |
| `repodum/doma/ilustrace/` | obraz | jpg soubory – dívka + zvíře + mezera |
| `repodum/doma/ilustrace/mys.jpg` | porucha | myš |
| `repodum/doma/ilustrace/netopyr.jpg` | porucha | netopýr |
| `repodum/doma/ilustrace/ryba.jpg` | porucha | ryba |
| `repodum/doma/ilustrace/pavouk.jpg` | porucha | pavouk |
| `repodum/doma/ilustrace/zajic.jpg` | porucha | zajíc |
| `repodum/doma/ilustrace/kocour.jpg` | porucha | kocour |
| `repodum/doma/ilustrace/pav.jpg` | porucha | páv |
| `repodum/doma/ilustrace/motyl.jpg` | porucha | motýl |
| `repodum/doma/ilustrace/krokodyl.jpg` | porucha | krokodýl |
| `repodum/doma/ilustrace/cap.jpg` | porucha | čáp |
| `repodum/doma/ilustrace/osel.jpg` | porucha | osel |
| `repodum/doma/ilustrace/jednorozec.jpg` | porucha | jednorožec |
| `repodum/doma/ilustrace/kravy.jpg` | porucha | krávy |
| `repodum/doma/ilustrace/zralok.jpg` | porucha | žralok |
| `repodum/doma/ilustrace/vlk.jpg` | porucha | vlk |
| `repodum/doma/ilustrace/panda.jpg` | porucha | panda |
| `repodum/doma/ilustrace/lemur.jpg` | porucha | lemur |
| `repodum/doma/ilustrace/plamenak.jpg` | porucha | plameňák |
| `repodum/doma/ilustrace/had.jpg` | porucha | had |
| `repodum/doma/ilustrace/tygr.jpg` | porucha | tygr |
| `repodum/doma/ilustrace/liska.jpg` | porucha | liška |
| `repodum/doma/ilustrace/prase.jpg` | porucha | prase |
| `repodum/doma/ilustrace/hvezdice.jpg` | porucha | hvězdice |
| `repodum/doma/ilustrace/drak.jpg` | porucha | drak |
| `repodum/doma/kriva_pohadka/` | text | txt soubory – autonomní text k poruše |
| `repodum/doma/kriva_pohadka/mys.txt` | pohádka | myš |
| `repodum/doma/kriva_pohadka/netopyr.txt` | pohádka | netopýr |
| `repodum/doma/kriva_pohadka/ryba.txt` | pohádka | ryba |
| `repodum/doma/kriva_pohadka/pavouk.txt` | pohádka | pavouk |
| `repodum/doma/kriva_pohadka/zajic.txt` | pohádka | zajíc |
| `repodum/doma/kriva_pohadka/kocour.txt` | pohádka | kocour |
| `repodum/doma/kriva_pohadka/pav.txt` | pohádka | páv |
| `repodum/doma/kriva_pohadka/motyl.txt` | pohádka | motýl |
| `repodum/doma/kriva_pohadka/krokodyl.txt` | pohádka | krokodýl |
| `repodum/doma/kriva_pohadka/cap.txt` | pohádka | čáp |
| `repodum/doma/kriva_pohadka/osel.txt` | pohádka | osel |
| `repodum/doma/kriva_pohadka/jednorozec.txt` | pohádka | jednorožec |
| `repodum/doma/kriva_pohadka/kravy.txt` | pohádka | krávy |
| `repodum/doma/kriva_pohadka/zralok.txt` | pohádka | žralok |
| `repodum/doma/kriva_pohadka/vlk.txt` | pohádka | vlk |
| `repodum/doma/kriva_pohadka/panda.txt` | pohádka | panda |
| `repodum/doma/kriva_pohadka/lemur.txt` | pohádka | lemur |
| `repodum/doma/kriva_pohadka/plamenak.txt` | pohádka | plameňák |
| `repodum/doma/kriva_pohadka/had.txt` | pohádka | had |
| `repodum/doma/kriva_pohadka/tygr.txt` | pohádka | tygr |
| `repodum/doma/kriva_pohadka/liska.txt` | pohádka | liška |
| `repodum/doma/kriva_pohadka/prase.txt` | pohádka | prase |
| `repodum/doma/kriva_pohadka/hvezdice.txt` | pohádka | hvězdice |
| `repodum/doma/kriva_pohadka/drak.txt` | pohádka | drak |
| `repodum/doma/angles/` | geometrie | kruh a vztahy |
| `repodum/doma/angles/topology.json` | kruh | 12 pozic, protilehlé, sousední |
| `repodum/doma/angles/v1.json` | slovník | názvy úhlů |
| `repodum/doma/poruchy.json` | rozcestník | seznam všech poruch s odkazy |
| `repodum/doma/poruchy_uhly_v1.json` | úhly | všech 12 úhlů pro každou poruchu |
| `repodum/doma/gap.json` | mezera | prázdný prostor, definice Gapu |
| `repodum/doma/multimedialni_bloky_priklady_z_uhly_v1.json` | příklady | multimediální bloky (výstupy) |

```

## Instrukce

- `doma/angles/v1.json` – jsou jen příklady.
- `doma/angles/topology.json` – číslo 12 není dogma, je to jen příklad použití. Jde o kruh a vztahy. Protilehlé jsou opačné, sousední podobné.
- `doma/gap.json` – Gap je mezera, odlišující jeden význam od jiného. Není to nic, co nic nedělá. Je to prostor, ve kterém se děje význam. Můžeš ho použít jako vlastní prostor pro tvorbu i přemýšlení, pro přenos mezi médii, nebo pro vlastní volné místo jako takové. Nefunguje samo o sobě ve vakuu. Musíš tam pracovat s tím, co v kontextu máš. Nemusíš ho použít vždy povinně. Musíš ale uvést, když ho použiješ. A na doptání bys měl být schopný popsat, jak jsi ho právě použil.
- Mezera pro trénink je v ilustraci mezi obrazem, na kterém je vždy dívka představující jazyk a řeč, a zvířetem, které je její poruchou. A mezi ručně kresleným textem, který je autonomní složka jako obraz – texty se nepopisují, tvoří celek i s tou mezerou. Ta mezera je třetí autonomní složka a jako fyzický objekt existuje jako `gap.json`.
- `doma/poruchy.json` – poruchy nejsou chyby k opravě. Jsou to vlastní entity v podání zvířete. Jazyk není popis, ale materiál.
```
