# Essential-Keyboard

![License](https://img.shields.io/badge/license-GNU-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)

Essential-Keyboard nasce come dimostrazione di come funzione una periferica di input, Essential-Keyboard è stato frutto di un interssante discussione su driver e periferiche di input in classe.

## Sommario

- [Introduzione](#introduzione)
- [Caratteristiche](#caratteristiche)
- [Funzionamento](#funzionamento)
- [BOM (Bill Of Materials)](#bom)
- [Licenza](#licenza)
- [Contatti](#contatti)

## Introduzione

Essential-Keyboard è una tastiera realizzata con arduino composta da 12 tasti di cui:
I primi 9 tasti contengono 3 lettere dell'alfabeto + un numero. Ad eccezione dell'ultimo tasto che prevede 2 lettere dell'alfabeto + 2 numeri. I successivi 3 tasti servono per Cancellare, Inviare e dare lo spazio.
Sul circuito sono presenti due interruttori, questi due interruttori servono corrispettivamente a cambiare da maiuscolo a minuscolo e viceversa, ad entrare in modalità INS.



## Funzionamento:
Il funzionamento di Essential-Keyboard è lo stesso dei vecchi telecomandi, ossia la pressione i-esima di un tasto visualizzerò l'i-esimo carattere associato a quel tasto. Supponiamo di avere un tasto del genere T -> ABC0, se lo clicco una volta ottengo A, se lo clicco due volte ottengo AB ecc. Per accedere ad un singolo carattere associato ad un tasto bisogna entrare in modalità INS, alzando l'interruttore per poi abbassarlo una volta ottenuto il carattere scelto.




## BOM
- Arduino micro con ATMega 32U4
- Pulsanti x 12
- Zoccolo per schede
- Resistori di resistenze 10Kohm x 12
- Interruttori slide x 2
- Cavi
- Millefori


## Licenza
Essential-Keyboard ha una licenza GNU General Public License v3.0.

## Contatti
Puoi contattarmi presso questo indirizzo email: ignazioandsperandeo@gmail.com

