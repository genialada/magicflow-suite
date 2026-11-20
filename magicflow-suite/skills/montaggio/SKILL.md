---
name: montaggio
description: "MagicFlow · monta il girato grezzo del cliente e lo rende un video pulito, a zero crediti: trascrive il parlato, toglie tosse, pause, «ehm», parole ripetute e frasi sbagliate, unisce i pezzi buoni, mette la musica sotto la voce e fa i formati 9:16 e 1:1 con i sottotitoli e il 16:9 composto (video a destra, logo, frase e sottotitoli a sinistra). USA SEMPRE questa skill quando il cliente porta i suoi video da sistemare: \"monta questi video\", \"pulisci il video\", \"togli le pause / gli errori\", \"unisci i pezzi\", \"metti la musica sotto\", \"fammi i formati\", \"fammi il quadrato / l'orizzontale\". Non serve per i video fatti con video-animati, che escono già finiti. Istruzioni e programmi arrivano dal connettore MagicFlow."
---

# Montaggio · MagicFlow

Il metodo e i programmi **non sono scritti qui**: li consegna, sempre aggiornati, il connettore **MagicFlow** di Adà.

## Prima di lavorare
1. Chiama lo strumento `istruzioni` del connettore MagicFlow con `modulo: "montaggio"` (pezzo `inizio`) e seguilo alla lettera.
2. Al Passo 0 chiama lo strumento `programmi` con `modulo: "montaggio"` ed esegui in Bash il comando che ti dà, così com'è: scarica i programmi in `~/magicflow/montaggio/`.
3. Colori, logo, caratteri e contatto vengono dalla scheda cliente; la frase gancio dalla skill `testi-social`.

## Se il connettore MagicFlow non risponde
Non scrivere i programmi né il metodo a memoria. Spiega al cliente, con parole semplici:
- se il connettore non è collegato: apri **Impostazioni › Plugin › MagicFlow suite › Connettori**, clicca **Collega** su MagicFlow e scrivi il codice di licenza che hai ricevuto con l'acquisto (email dell'ordine o *Il mio account* su genialada.com);
  (oppure la skill **attivazione** di MagicFlow suite, che lo guida passo per passo: «attiva MagicFlow»);
- se i programmi non si scaricano: aggiungi `magicflow.genialada.workers.dev` in **Impostazioni › Funzionalità › Domini aggiuntivi consentiti**, poi apri una chat nuova;
- se la licenza non è attiva o il modulo non è incluso: riporta la frase che ti ha dato il connettore, con gentilezza, e il link che contiene.

Per qualsiasi problema: info@genialada.com.
