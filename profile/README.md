# MonData

**Monitoring a automatizácia technických dát — jedným systémom.**

MonData je platforma, ktorá zbiera, ukladá a v reálnom čase zobrazuje dáta z technických a priemyselných zariadení — bez ohľadu na to, kde fyzicky stoja a akým protokolom komunikujú. Cieľom je jeden univerzálny systém, ktorý vie obslúžiť monitoring a automatizáciu ľubovoľného typu prevádzky: od technológie budovy, cez výrobnú linku, až po energetiku.

## Čo riešime

Technické zariadenia (meracie prístroje, PLC, senzory, riadiace jednotky) bežne komunikujú lokálne, každé svojím vlastným protokolom, a dáta z nich sú roztrieštené naprieč rôznymi izolovanými systémami. MonData tento problém rieši tým, že dáta z rôznych zariadení a protokolov zjednocuje do jednej dátovej štruktúry a sprístupňuje ich cez jedno webové rozhranie — nech je zariadenie akékoľvek.

## Ako to funguje

1. **Zber dát na mieste** — naše edge zariadenie sa pripája priamo k technológii na danej lokalite a číta (prípadne aj zapisuje) dáta lokálne, v reálnom čase.
2. **Bezpečný prenos do cloudu** — nazbierané dáta sa priebežne odosielajú a zálohujú do cloudu.
3. **Zobrazenie a monitoring** — webová aplikácia dáta zobrazuje prehľadne, v štruktúre "od lokality po konkrétny meraný bod", vrátane stavu a histórie.

Táto architektúra je navrhnutá univerzálne — jedna lokalita ("site") môže byť obchodné centrum, elektráreň, výrobná hala alebo čokoľvek iné, čo treba monitorovať alebo automatizovať.

## Podporované protokoly a zariadenia

Systém je od základu stavaný ako protokolovo nezávislý. Aktuálne podporujeme komunikáciu cez **Modbus** (TCP/RTU) a architektúra je pripravená na postupné pridávanie ďalších priemyselných a komunikačných protokolov podľa potreby konkrétnej integrácie. Cieľom nie je viazať sa na jedného výrobcu alebo jeden typ zariadenia, ale vedieť pripojiť čo najširšie spektrum technológií pod jeden monitoring.

## Vlastný hardvér

Popri softvérovej platforme vyvíjame aj vlastné edge hardvérové zariadenia, ktoré slúžia ako brána medzi lokálnou technológiou a naším systémom. Tieto zariadenia je možné nasadiť priamo na konkrétnu prevádzku a napojiť na existujúce meracie a riadiace prvky bez potreby zásahu do samotnej technológie.

## Stav projektu

MonData je aktívne vo vývoji. Časti systému (repozitáre) sú momentálne súkromné — v prípade záujmu o spoluprácu alebo viac informácií nás neváhajte kontaktovať.

