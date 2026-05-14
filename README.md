# Ročníková práce: Návrh a sestavení vlastního stolního počítače

**Autor:** Šmehlík Tadeáš
**Školní rok:** 2025/2026  

---

## Úvod

Tématem mé ročníkové práce je návrh, výběr komponentu a samotné fyzické sestavení stolního počítače. Cílem bylo vytvořit moderní a vyváženou PC sestavu, která bude sloužit pro hraní náročnějších her, a to vše s ohledem na rozpočet.



## 1. Cíle ročníkové práce

### 1.1 Hardwarová část
* Vybrat navzájem kompatibilní komponenty.
* Vejít se do stanoveného rozpočtu 20 000 Kč.
* Fyzicky sestavit počítač bez poškození citlivých součástek.


### 1.2 Softwarová část
* Aktualizovat systém BIOS na základní desce.
* Nainstalovat operační systém Windows 11.
* Správně nainstalovat ovladače pro grafickou kartu a procesor.

### 1.3 Testování a ladění
* Otestovat stabilitu systému pomocí zátěžových testů.
* Zkontrolovat teploty procesoru a grafické karty.

## 2. Komponenty

Před samotným nákupem jsem strávil několik týdnů sledováním recenzí a studiem toho, jakou platformu zvolit. 

### 2.1 Procesor (CPU) a platforma
Rozhodoval jsem se mezi Intelem a AMD. Nakonec jsem zvolil platformu **Intel** (konkrétně procesor Intel Core i5-8400).

### 2.2 Grafická karta (GPU)
Pro hraní v rozlišení 1080p a občasné 1440p jsem vybral kartu **Nvidia Geforce GTX 1050**.

### 2.3 Zdroj (PSU) a zbytek sestavy
Vybral jsem 650W zdroj s certifikací 80 Plus Gold od spolehlivého výrobce (Seasonic). Dále jsem osadil 64 GB DDR5 RAM.

## 3. Sestavení počítače v praxi

### 3.1 Příprava mimo skříň
Nejdřív jsem si připravil komponenty na stůl. Poté nářadí a nějaký návod

### 3.2 Montáž do skříně a zapojování
Následně jsem předpřipravenou desku vložil do počítačové skříně a zajistil šrouby. 
Největší výzvou celého projektu pro mě překvapivě nebylo zacházení s drahým procesorem, ale **zapojení kabelů**. ATX kabel od zdroje byl dost neohebný. Nejvíc trpělivosti ale vyžadovalo zapojení. 
Všechny kabely jsem se snažil vést zadní stranou skříně a uchytit je stahovacími páskami, aby v hlavní komoře nic nebránilo průtoku vzduchu od předních ventilátorů k procesoru a grafice.

## 4. Softwarová realizace a oživení

### 4.1 První spuštění
Po zapojení do sítě jsem počítač zapnul. K mé úlevě se roztočily ventilátory, rozsvítily se kontrolky a na monitoru naběhl BIOS. 

### 4.2 Nastavení a instalace
1. Jako první jsem na jiném počítači stáhl nejnovější verzi BIOSu a přes USB flash disk ji do desky nahrál. Tím jsem zajistil maximální kompatibilitu s mým procesorem.
2. V BIOSu jsem zapnul funkci **EXPO**. Kdybych to neudělal, paměti by běžely jen na základní pomalé frekvenci a já bych přicházel o část výkonu.
3. Pomocí nástroje Media Creation Tool jsem si vytvořil instalační flash disk a nainstaloval Windows 11.
4. Následovala instalace ovladačů grafické karty stažených přímo ze stránek Nvidie a aktualizace systému.

## 5. Testování

Abych si byl jistý, že je počítač stabilní a chlazení funguje správně, podrobil jsem ho několika testům.

* **Cinebench R23:** Procesor běžel na 100 % zátěže po dobu 10 minut. Teplota nepřesáhla 76 °C, což je pro tyto moderní čipy výborná a velmi bezpečná hodnota. Chladič Fera 5 se ukázal jako správná volba.
* **3DMark Time Spy a Furmark:** Grafická karta dosáhla maximální teploty 68 °C, ventilátory běžely zhruba na 45 %, takže karta byla velmi tichá.

## 6. Závěr

Moje ročníková práce byla úspěšná a všechny stanovené cíle se mi podařilo splnit. – konektory jsou navrženy tak, že většinou nejdou zapojit špatně.

Díky vlastní montáži jsem výrazně ušetřil oproti předraženým hotovým sestavám z velkých obchodů, a navíc vím přesně, jaké komponenty v počítači mám. Naučil jsem se pracovat s BIOSem a vyzkoušel si diagnostiku teplot. 

## 7. Použité nástroje a zdroje

Při výběru komponent a přípravě na sestavení jsem čerpal převážně z komunitních a odborných zdrojů:

* https://youtu.be/e-9FOctIF3c?si=l79XDl3I0LHMeJ4p - návod na sestavení
* https://youtu.be/3zo9_LxCVNQ?si=ZcqHcOlnciCBCBef - 2. návod na sestavení
* https://youtu.be/6rMtuOfPX4c?si=eVOVVmZnj2pR9Rbh - instalace windows
* https://youtu.be/0B4t2mRwuhU?si=MTo5pUlnywS59eIM - nejlepší komponenty
* https://www.alza.cz/?kampan=adwalz_alza_sea_gen_alza-brand_alza-brand-varianty_c_1003823_e__803331011505_~198549952281~&gad_source=1&gad_campaignid=20984453029&gbraid=0AAAAAD2xsm4QCPDgO9NrsISUXgEOmyreU&gclid=CjwKCAjw5ZXQBhBdEiwAI5XVWSheDMKT44UvAlqE7juuGeQ3Kkj2oh9ELZZwoJl1jfhiXnbcbkJ8TRoCvO4QAvD_BwE - na alze jsem vybíral
* Gemini
