# Exercise 3 - Patch Diffing

Vous avez 2 binaires, un vulnerable et un patched. Afin de trouver la patch et comprendre la vulnerabilite, faites un diff avec BinDiff!

## Outils

* Ghidra
* DynamoRIO
* DragonDance
* Cartographer

## Instructions

1. Installer les outils
2. Capturer la premiere trace avec:
```
./drrun -t drcov -- curl http://pasunsiteweb.com/
```
3. Capturer la deuxieme trace avec:
```
./drrun -t drcov -- curl https://google.com/
```
4. Importer curl dans Ghidra
5. Importer la premiere trace avec DragonDance ou Cartographer
6. Importer la deuxieme trace avec DragonDance ou Cartographer
3. Differencier les traces
6. Analyser les resultats 
