# PAUSE — Importazione del progetto e preview funzionante

App mobile di micro-letture divulgative in italiano: capitoli brevi pensati per stare in una sola
schermata, organizzati per categorie, con copertine, salvataggi e un'esperienza di lettura calma.
Questo lavoro prende il progetto dal tuo repository GitHub e lo rimette in piedi qui, pronto da aprire e provare.

## Per chi è
Chi vuole imparare qualcosa di nuovo in pochi minuti, un capitolo alla volta, senza distrazioni —
nei momenti di pausa durante la giornata.

## Cosa include (contenuto già presente nel repo)
- **Onboarding**: ingresso come ospite e scelta di alcune categorie di interesse.
- **Home e categorie**: scienza, storia, spazio, natura, psicologia, tecnologia, arte, economia,
  geografia, sport, cultura, curiosità, corpo umano, animali.
- **Lettore a schermate**: ogni capitolo occupa una schermata, si avanza con un gesto; il testo si
  adatta automaticamente per entrare nello schermo.
- **Copertine e immagini** dei contenuti già incluse nel progetto.
- **Salvati**: raccolta dei capitoli messi da parte.
- **Profilo** con statistiche di lettura.
- **Premium e limite di pausa**: le schermate dedicate così come sono nel repo.
- **Tipografia** Plus Jakarta Sans su tutta l'app.

## Come si presenta
Si tratta di un'app pensata per il telefono. La preview viene mostrata nel browser in formato web:
l'aspetto e i flussi sono quelli dell'app, visualizzati in una finestra verticale da telefono.
Tono visivo calmo e curato, molto spazio, lettura al centro dell'esperienza.

## Flusso d'uso
1. Si apre l'app → onboarding → "Continua come ospite".
2. Si scelgono alcune categorie di interesse.
3. Dalla home si sceglie un argomento e si apre un capitolo.
4. Si legge avanzando schermata per schermata; si possono salvare i capitoli.
5. Dal profilo si vedono le proprie statistiche.

## Cosa viene fatto ora (Fase 1 — questa consegna)
- Importazione del codice dal repository e messa in funzione di backend e app.
- Caricamento dei contenuti già inclusi nel progetto (nessun contenuto nuovo generato).
- **Completamento rinomina "Mini lezioni" → "Impara"**: la modifica era già fatta quasi ovunque
  (etichette modalità, badge "IMPARA", onboarding, Premium). Resta da sistemare l'ultima stringa
  rimasta indietro, `read_lesson`, che oggi dice ancora "Leggi la mini-lezione":
  nuovo testo **"Leggi e Impara"** (IT) e **"Read & Learn"** (EN). Nessun credito necessario.
- Verifica che l'app si apra: onboarding, scelta categorie, home, apertura e lettura di un capitolo,
  salvataggi, profilo.
- Consegna della preview pronta da aprire.

## Fasi successive (non ora)
- **Fase 2 — Audio/voce**: attivare la narrazione vocale dei capitoli (quando ricarichi il credito).
- **Fase 2 — Capitoli più corti**: compattare i capitoli lunghi perché entrino meglio in una
  schermata (quando ricarichi il credito).
- **Fase 3 — Pubblicazione**: eventuali ritocchi e messa online dell'app.

## Scelte già prese (assunzioni)
- Preview **solo lettura**: nessuna narrazione vocale attiva ora, nessun consumo di credito.
- Contenuti **lasciati come sono**: i capitoli lunghi si adattano riducendo il testo; la
  compattazione si farà più avanti.
- L'app viene riportata **com'è nel repo**, senza aggiungere o togliere funzioni.
- Ingresso **come ospite** (nessun login da configurare in questa fase).
- Lingua dell'app: **italiano**, come nel progetto originale.
- La preview è mostrata **nel browser** in formato telefono (l'app è nata per mobile).
