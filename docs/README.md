# Dokumentacija MSc projekta

## Tema

**Integrated Detect-and-Avoid for Indoor UAVs:
Real-Time Trajectory Optimization and Robust Nonlinear Control
with Motion-Capture-Based Validation**

## Glavni cilj

Cilj projekta je razvoj integrisanog detect-and-avoid sistema za autonomne
letjelice u zatvorenom prostoru.

Sistem treba povezati:

1. real-time planiranje vremenski parametrizovanih trajektorija;
2. izbjegavanje statičkih i pokretnih prepreka;
3. multi-agent rješavanje konflikata i održavanje minimalne separacije;
4. robustan nelinearni regulator za praćenje generisanih trajektorija;
5. integraciju planera, regulatora, ROS 2, PX4 i MoCap sistema;
6. simulacijsku i eksperimentalnu validaciju.

## Kontrolni podsistem

Geometrijsko upravljanje i INDI predstavljaju odabrani pravac razvoja
kontrolnog podsistema.

Planirano je detaljno istražiti:

- geometrijski model kvadrotora na SO(3) i SE(3);
- geometrijsko praćenje položaja i orijentacije;
- INDI za brzu unutrašnju kontrolnu petlju;
- odbacivanje smetnji;
- uticaj modelskih neizvjesnosti, šuma, kašnjenja i saturacija;
- vezu između greške praćenja i sigurnosnih ograničenja planera.

Ova kontrolna arhitektura nije svrha kompletnog MSc rada, nego jedan od
ključnih podsistema integrisanog detect-and-avoid okvira.

## Glavne cjeline dokumentacije

- zahtjevi i obim teme;
- modeliranje kvadrotora;
- geometrijsko upravljanje;
- INDI;
- generisanje i optimizacija trajektorija;
- detect-and-avoid;
- multi-agent koordinacija;
- integracija planiranja i upravljanja;
- ROS 2, PX4 i MoCap arhitektura;
- eksperimentalni protokol;
- metrike, rezultati i benchmarking.
