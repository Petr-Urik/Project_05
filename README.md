# Project_05: Hypertenze v Evropě a ČR
Pátý projekt v rámci Engeto: Datová akademie s Pythonem

## Popis projektu
Obsahem práce je Power BI prezentace analýz z oblasti výskytu vysokého krevního tlaku (hypertenze) v evropských zemích a odděleně potom i v Česku. Výskyt hypertenze je porovnáván mezi evropskými státy,
mezi pohlavími a mezi různými věkovými skupinami. Poslední strana je pak věnována srovnání léků na vysoký tlak nejčastěji předepisovaných versus těchto léků nejčastěji v lékárnách vydávaných.
## Hlavní datové zdroje
 Hlavním zdrojem k těmto analýzám byly jednak data z portálu Eurostat (pro Evropu), Národního zdravotnického informačního portálu (pro ČR) a otevřená data Ústavu pro kontrolu léčiv (pro ČR). 
 Příslušné odkazy jsou součástí úvodní strany prezentace.  
 Nejaktuálnější výsledky pro Evropu pocházejí ze sběru dat v roce 2019, proto jsem využil právě tyto. Na místě je i upozornění, že ne všechny evropské
 země se tohoto sběru účastnily, a proto ve vizualizacích chybí. Česká data pak pocházejí z let 2011-2024 (hypertenze) a 2019-2024 (léky).
 ## Ukázka práce - úvodní dashboard  

 <img width="1321" height="746" alt="image" src="https://github.com/user-attachments/assets/571adab3-7906-4122-bf09-d0c3e75f1e8c" />  

 ## Využití
 - možnost porovnat evropské země nebo kraje ČR z hlediska procentuálního zastoupení pacientů s vysokým tlakem v příslušné populaci
 - porovnat státy i dle příslušnosti k bývalému Západnímu nebo Východnímu bloku z dob studené války
 - zjistit rozdíly ve výskytu vysokého tlaku mezi muži a ženami
 - pozorovat souvislost výskytu hypertenze s rostoucím věkem obyvatel
 - uvědomit si výrazný rozdíl mezi tím, jaké léky na tlak jsou lékaři předepisovány a jaké jsou pak vydávány v lékárnách

## Instrukce pro nastavení cesty k datům
Tento report využívá dynamický parametr pro načítání dat. Před prvním spuštěním (nebo při přesunu složky s daty) je nutné upravit cestu ke zdrojům:
- V Power BI: Na kartě *Domů* klikněte na šipku u *Transformovat data* a zvolte *Upravit parametry*.
- Upravte parametr *Cesta_k_souboru* tak, že do pole Aktuální hodnota vložíte cestu ke složce, kde máte uložená stažená zdrojová data. Vložená cesta musí končit zpětným lomítkem.
- Potvrďte a dejte *Refresh All*.
