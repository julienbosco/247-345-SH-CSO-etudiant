# Semaine 4

## Exercice de multiplication:

À partir du code en C suivant, produire le code en assembleur ou en *opcode* permettant d'exécuter ce code sur le processeur vu en classe:

```
a = 4;   // multiplicande
b = 2;   // multiplicateur
res = 0; // Resultat

// Cas special du multiplicateur a 0
if (b == 0) {
  halt();
}

// Cas special du multiplicateur a 1
res = a; 
if (b == 1) { 
  halt();
}

while (b != 0) {
  b--;
  if(b == 0)
    break;
  res += a;
}
halt();
```

Les opcodes disponibles sont:

| Opération | Code | Mmémonique |
|--|--|--|
|Load|10h|LOD|
|Store|11h|STO|
|Add|20h|ADD|
|Subtract|21h|SUB|
|Add with carry|22h|ADC|
|Subtract with borrow|23|SBB|
|Jump|30h|JMP|
|Jump If Zero|31h|JZ|
|Jump If Carry|32h|JC|
|Jump If Not Zero|33h|JNZ|
|Jump If Not Carry|34h|JNC|
|Halt|FFh|HLT|

## Modification du bloc de RAM

Fournir le schéma bloc d'un bloc de RAM 16x1. Les blocs pouvant être utilisés sont:

* Flip-Flop
* Selector
* Decoder

Toutes les entrées et sorties doivent être annotées. Voir page 187 (PDF) comme point de départ.
