---
name: email-clienti
description: "MagicFlow · le email ai clienti su MailerLite, dalla scheda cliente: collega MailerLite con un clic (connettore, senza chiavi), crea il gruppo, scrive la sequenza a risposta diretta (metodo Kennedy), monta l'automazione e la rende davvero inviabile, prepara la riattivazione della lista. USA SEMPRE questa skill per \"prepara le mail\", \"sequenza email\", \"collega / imposta MailerLite\", \"automazione email\", \"email di benvenuto / offerta / follow-up\", \"riattiva la lista\", \"Emails not designed\", o subito dopo l'intervista. Le istruzioni aggiornate arrivano dal connettore MagicFlow."
---

# Email ai clienti · MagicFlow

Il metodo di questa skill **non è scritto qui**: lo consegna, sempre aggiornato, il connettore **MagicFlow** di Adà.

## Prima di lavorare
1. Serve la scheda cliente (`scheda-cliente.json`). Se non c'è, parti dalla skill `intervista-cliente`.
2. Chiama lo strumento `istruzioni` del connettore MagicFlow con `modulo: "email-clienti"` (pezzo `inizio`) e seguilo alla lettera.
3. Gli altri pezzi (`sequenza` per i testi, `api` per rendere inviabili le email e attivare l'automazione) chiedili quando il pezzo `inizio` lo dice. I testi li scrivi col metodo della skill `testi-social`.
4. Il lavoro su MailerLite si fa col connettore MailerLite, collegato all'account **del cliente**. Prima di creare qualsiasi cosa, controlla con `get_auth_status` che sia l'account giusto.

## Se il connettore MagicFlow non risponde
Non scrivere il metodo a memoria. Spiega al cliente, con parole semplici:
- se il connettore non è collegato: apri **Impostazioni › Plugin › MagicFlow suite › Connettori**, clicca **Collega** su MagicFlow e scrivi il codice di licenza che hai ricevuto con l'acquisto (email dell'ordine o *Il mio account* su genialada.com);
  (oppure la skill **attivazione** di MagicFlow suite, che lo guida passo per passo: «attiva MagicFlow»);
- se la licenza non è attiva o il modulo non è incluso: riporta la frase che ti ha dato il connettore, con gentilezza, e il link che contiene.

Per qualsiasi problema: info@genialada.com.
