# DiskMap

Rýchly analyzátor obsadenia diskov pre Windows: strom, treemapa, štatistiky, duplikáty a porovnanie v čase.

Pre Windows 10 (2004+) a Windows 11, x64.

## Stiahnuť

[Stiahnuť DiskMap.exe](https://github.com/enthilza/DiskMap/releases/latest/download/DiskMap.exe) · [Všetky vydania](https://github.com/enthilza/DiskMap/releases)

Samostatné EXE obsahuje .NET runtime, nič sa neinštaluje. Ulož ho do priečinka, kde máš právo zapisovať, a spusti.

## Aktualizácie

Aplikácia pri štarte overí, či existuje novšie vydanie, a tlačidlom aktualizácie to môžeš skontrolovať aj ručne. Inštaluje sa až po tvojom potvrdení.

Každé vydanie obsahuje `DiskMap.exe`, `update.json` a `update.sig`. Aplikácia overí digitálny podpis popisu vydania (RSA/SHA-256) zabudovaným verejným kľúčom a potom veľkosť, kontrolný súčet SHA-256 a verziu stiahnutého EXE. Až potom EXE vymení, nová verzia musí úspešne naštartovať, inak sa vráti pôvodná.

Nejde o Windows Authenticode podpis, preto môže Windows SmartScreen pri prvom spustení zobraziť upozornenie.

## Súkromie

Kontrola aktualizácií kontaktuje iba GitHub. Nastavenia sú v `%LOCALAPPDATA%\DiskMap`.

Tento repozitár obsahuje iba distribučné súbory a informácie o vydaniach.