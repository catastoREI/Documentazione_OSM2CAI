# Stato di percorribilità

Vista l'esigenza di informare sulla percorribilità di un percorso, è stato introdotto il concetto di stato di percoribilità.

I valori di questo campo possono essere quattro:

| STATO                     | DESCRIZIONE                                                                        |
| ------------------------- | ---------------------------------------------------------------------------------- |
| PERCORRIBILE              | Il percorso è ritenuto percorribile a seguito di un rilievo sul campo              |
| PARZIALMENTE PERCORRIBILE | Il percorso è ritenuto parzialmente percorribile a seguito di un rilievo sul campo |
| NON PERCORRIBILE          | Il percorso è ritenuto non percorribile a seguito di un rilievo sul campo          |
| NON RILEVATO              | Il percorso non è stato rilevato                                                   |

Contestualmente allo stato vengono salvate nel database anche la data di modifica dello stato e una eventuale descrizione, che risulta obbligatoria nel caso di percorso parzialmente percorribile o non percorribile
