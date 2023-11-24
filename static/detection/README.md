# Exercise 2 - Diffing pour la detection de malware

Vous avez deux samples de la meme famille de malware. Cependant, les deux samples ne sont pas pareils et vous devez detecter les deux samples.

## Outils

* Ghidra
* BinExport
* BinDiff
* [YARA](https://virustotal.github.io/yara/)

## Instructions

1. Installer Ghidra, BinExport et BinDiff
2. Creer un compte [MalwareBazaar](https://bazaar.abuse.ch/) et chercher les samples
3. Importer le binaire dans Ghidra
4. Exporter le binaire sour la forme BinExport
5. Repeter les etapes 2-3 pour le deuxieme binaire
6. Importer les deux fichiers .BinExport dans BinDiff
7. Regarder les similarites entre les samples, plutot que les differences
8. Creer une signature YARA basee sur les similarites

## Samples

| SHA256                                                           |
|------------------------------------------------------------------|
| 108e8f5a4051763f052d008fb1dc3a9fbc56d149b3bf442fc06a4a35178efe03 |
| 7dbf54a7d28bc41c266a9277238b7ca8089e0df97b0c917f3424a443185f99c5 |
| ad4f00ab519845f4c1a3a4044e9d7992dc37c5887c08260282f9731f21c5da99 |
| e2a33fede9a1d897e504541f61bf7ded193e801dda952657d615f34d6b94cdd3 |
