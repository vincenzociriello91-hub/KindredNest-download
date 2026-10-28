# Informativa sulla privacy di KindredNest

Ultimo aggiornamento: 28 ottobre 2026

KindredNest non ha account, pubblicità né statistiche di utilizzo. Lo sviluppatore riceve soltanto, e solo se lo permetti, i rapporti tecnici descritti qui sotto: mai foto, progetti o dati personali.

## Foto, planimetrie e progetti
- Restano salvati sul tuo telefono e si cancellano eliminando il progetto o l'app.
- Per creare le proposte vengono inviati ai servizi di intelligenza artificiale che usi: Puter (con i modelli di Google e OpenAI), la tua chiave Gemini se l'hai collegata, oppure il servizio di riserva su Hugging Face. Ciascun servizio applica la propria informativa.
- Con il **designer sul telefono** le analisi e la chat avvengono interamente sul telefono: le foto non escono dal dispositivo. Il modello si scarica una volta da Hugging Face.

## Posizione
Si usa solo quando chiedi i negozi vicini: viene inviata a OpenStreetMap (servizio Overpass) per la ricerca e non viene salvata.

## Chiave Gemini
Se la colleghi, è salvata solo sul telefono e cifrata con il Keystore di Android.

## Rapporti tecnici (facoltativi)
Al primo avvio l'app chiede se può inviare rapporti tecnici per correggere i problemi; la scelta si cambia in *Impostazioni › Rapporti per migliorare KindredNest*, dove si può anche leggere l'ultimo rapporto preparato.
- **Cosa contengono:** modello del telefono, versione di Android e dell'app, lingua, memoria, quali servizi di intelligenza artificiale hanno risposto e in quanto tempo, gli esiti di ogni proposta (riuscita o errore), i messaggi d'errore e la traccia del codice in caso di chiusura improvvisa, e un codice casuale dell'installazione (non è legato a te e cambia se cancelli i dati dell'app).
- **Cosa non contengono mai:** foto, planimetrie, immagini generate, nomi dei progetti e delle stanze, note, misure, liste dei mobili, messaggi al designer, chiavi, account, email, numeri di telefono o posizione. Questi dati vengono tolti anche dai messaggi d'errore.
- **Come viaggiano:** il rapporto si cifra sul telefono (AES-256 e RSA a 3072 bit) e solo lo sviluppatore ha la chiave per aprirlo. Passa da un servizio di inoltro su Cloudflare, che non lo può leggere e non salva il tuo indirizzo IP, e viene conservato in un archivio privato su GitHub.
- **Perché:** solo per trovare e correggere i problemi dell'app. Base giuridica: il tuo consenso, che puoi ritirare quando vuoi (i rapporti non ancora inviati vengono cancellati).

## Aggiornamenti
Per sapere se c'è una versione nuova l'app legge la pagina pubblica delle versioni su GitHub (al massimo ogni 12 ore) e, se lo confermi, scarica da lì il nuovo file. GitHub vede l'indirizzo IP della richiesta, come per qualsiasi pagina web.

## Suggerimenti
Si inviano su GitHub con il tuo account e sono pubblici.

## Contatti
Scrivi un [suggerimento](https://github.com/vincenzociriello91-hub/KindredNest-download/issues/new?template=suggerimento.yml).
