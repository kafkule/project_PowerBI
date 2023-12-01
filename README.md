### ENGETO Projekt Power BI
### Autor: Kateřina Kocianová (Discord: Kateřina Koci - kafkule)
-----



## Struktura projektu

- dokumentace
- vizualizace dat



## Zadání projektu

Vizualizace zvoleného datasetu podle zadaných kritérií:

- rozsah 2-3 stránky :ballot_box_with_check:
- použití minimálně 5 různých typů vizuálů :ballot_box_with_check:
- filtrování pomocí slicerů :ballot_box_with_check:
- využití bookmarks/page navigation :ballot_box_with_check:
- propojení více datových zdrojů (v Power Query nebo v Power BI) :ballot_box_with_check:
- použití datové hierarchie :ballot_box_with_check:
- vytvoření alespoň 1 measure (metrika/míra) a 1 kalkulovaného sloupce :ballot_box_with_check:
- grafická úprava použitých vizuálů a vizuálně přívětivý výsledný report :ballot_box_with_check:



## Dodatečné informace

Pro projekt z Power BI jsem si vybrala volně dostupný dataset [Nobel Prize Winners: 1901 to 2023](https://www.kaggle.com/datasets/sazidthe1/nobel-prize-data), který byl v době zpracování (11/2023) vizualizace aktualizovaný a vztažený k výsledkům Nobelovy ceny z roku 2023.



## Popis dat

[Number of prizes awarded](#Number of prizes awarded)
[Gender gap](#Gender gap)
[Age of laureates](#Age of laureates)
[Nobel Prize timeline](#Nobel Prize timeline)
[Shared Nobel Prizes](#Shared Nobel Prizes)
[Nobel Prize categories by continents](#Nobel Prize categories by continents)
[All Nobel Prize Winners](#All Nobel Prize Winners)
[Nobel Prize categories by continents](#Nobel Prize categories by continents)
[Laureates and organizations with >1 prizes](#Laureates and organizations with >1 prizes)

![Home](https://github.com/kafkule/project_PowerBI/blob/main/images/NP1.png)
![NP 1](https://github.com/kafkule/project_PowerBI/blob/main/images/NP2.png)
![NP 2](https://github.com/kafkule/project_PowerBI/blob/main/images/NP3.png)


### Number of prizes awarded

Tento vizuál ukazuje počet udělených cen (nikoliv oceněných laureátů) v jednotlivých kategoriích. 

Uprostřed vizuálu je umístěna jedna z cen - medaile s podobiznou Alfreda Nobela, kterou obdrží každý vítěz Nobelovy ceny. 

Více informací [A unique gold medal](https://www.nobelprize.org/prizes/about/the-nobel-medals-and-the-medal-for-the-prize-in-economic-sciences/).


### Gender gap 

V letech 1901 až 2023 bylo oceněno celkem 65 žen, vizuál ukazuje procentuální poměr mezi vítězi dle jednotlivých kategorií. Co se počtu žen týče, nikdy se nejednalo o více než pětinu oceněných. 

Ve vizuálu byla použita míra pro určení celkového počtu řádků, kdy je ve sloupci gender (pohlaví) uvedeno "female" (žena) nebo "male" (muž).

Více informací [Nobel Prize awarded women](https://www.nobelprize.org/prizes/lists/nobel-prize-awarded-women/).


### Age of laureates

#### Yougest medailist age 

Malale Yousafzai bylo v době obdržení ceny pouhých 17 let, cenu za mír obdržela v roce 2014 společně s Kailash Satyarthim za boj proti potlačování dětí a jejich právo na vzdělání. 

Více informací [The Nobel Peace Prize 2014](https://www.nobelprize.org/prizes/peace/2014/summary/).

#### Oldest medalist age

Nejstaršímu oceněnému bylo v době převzetí ceny úctyhodných 97 let, jednalo se o Johna B. Goodenougha, který spolu s M. Stanleym Whittinghamem a Akira Yoshinou převzal v roce 2019 cenu v kategorii Chemie (přestože byl fyzik) za vývoj lithium-iontových baterií (Li-Ion baterie), které se dnes už běžně užívají ve spotřební elektronice.

Více informací [The Nobel Prize in Chemistry 2019](https://www.nobelprize.org/prizes/chemistry/2019/summary/)

#### Average age at the time of the award

Ve vizuálu je pro zobrazení průměrného věku laureátů použita funkce pro vytvoření skupin, které mezi sebou dělí vždy 10 let.

Tento vizuál z pochopitelných důvodů nezahrnuje stáří oceněných organizací.

Více informací [Nobel Laureates by age](https://www.nobelprize.org/prizes/lists/nobel-laureates-by-age/)


### Nobel Prize timeline

Časová osa, vytvořená pomocí skládaného sloupcového grafu, ukazuje jednotlivé roky a ceny dle jednotlivých kategorií, které byly v daných letech uděleny.

V grafu chybí roky 1940 - 1942, kdy probíhala 2. světová válka. V roce 1939 nebyla udělena cena za mír. V letech 1940 až 1942 nebyla cena udělena v žádné kategorii, a to z důvodu okupace Norska Německem. V následujícím roce byly uděleny všechny ceny s výjimkou cen za literaturu a mír.

Vedle grafu vidíme počet oceněných, případně po kliknutí na některou z vizualizací počet dle dané kategorie.

Více informací [With fascism on the doorstep](https://nobelprize.org/prizes/themes/with-fascism-on-the-doorstep-the-nobel-institution-in-norway-1940-1945/)


### Shared Nobel Prizes

Koláčový graf zobrazuje poměr cen dle toho, zda byly uděleny jednotlivci nebo mezi více laureátů.


### Nobel Prize categories by continents

Speciální typ grafu zv. chord, který zobrazuje vztahy mezi daty v matici, ukazuje vztahy mezi cenami udělenými v jednotlivých kategoriích a kontinenty, odkud pocházejí laureáti.


### All Nobel Prize Winners

V prezentaci najdeme i tabulku se všemi oceněnými, jejich původem, zemí, kde působili, i zemí, kde případně zemřeli. Podle těchto údajů se dá také ve vizuálu filtrovat.

Ve vizuálu byla použita hierarchie.


### Nobel Prize categories by continents

Mapa ukazuje pohled na svět a rozdělení laureátů podle země (kontinentu) jejich původu.


### Laureates and organizations with >1 prizes

Tabulka zobrazuje laureáty a organizace, kteří v obdrželi více než jedno ocenění.