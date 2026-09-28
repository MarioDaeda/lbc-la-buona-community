# Bibbia del mondo — "Le Emozioni Arrivano Prima di Noi"

Fonti ufficiali: `CONTEXT.md`, `docs/adr/0001`, `docs/adr/0002`, `docs/adr/0003`, `ANALISI_CRITICA_STATO_ARTE_E_MANUALI.md`. I fatti di questo file prevalgono sull'improvvisazione. Aggiornare dopo ogni capitolo riscritto (vedi verifica finale in SKILL.md).

## Canone a 5 atti (invariante)

Ogni capitolo segue la Struttura Tripartita Invariante in 5 atti:

1. **Innesco narrativo situato** — la frattura esplode in un luogo e un orario concreti.
2. **Terzo neutrale** — disciplina della telecamera: solo comportamento osservabile, zero interiorità dichiarata.
3. **Decodifica scientifica** — voce narrante, mai in bocca ai personaggi. Framework ammesso: Lazarus (appraisal/coping), Damasio (marcatori somatici), Barrett, Kahneman, Porges (neurocezione, stati vagali). Vietate tassonomie popolari (MBTI, Enneagramma).
4. **Ritorno nella stanza** — azione di de-escalation operativa: l'accordo si chiude su numeri, ore, procedure.
5. **Apparati pratici** — Esercizio in 7 punti e Registro di continuità; sobri e procedurali per progetto.

## Architettura corale (ADR 0001)

I protagonisti cambiano di capitolo in capitolo ma vivono nella stessa filiera industriale di distretto (rapporti cliente-fornitore, partner, commesse condivise). Ogni capitolo ha un POV focale diverso; i personaggi secondari di un capitolo possono essere protagonisti di un altro.

## Fratture organizzative (ADR 0002 — Modello B)

Ogni capitolo è trainato da una frattura materiale e relazionale viva, non da un'emozione a catalogo. Catalogo fratture: Commerciale vs Officina · Accentratore vs Delega · Acquisti vs Magazzino · Riconoscenza negata · Gelo tra soci fondatori · Cinismo di reparto.

## Telemetria emotiva (logica diagnostica)

L'emozione osservabile è telemetria di un flusso interrotto, mai problema psicologico individuale: rabbia → monte che scarica difettoso a valle; ansia → decisioni senza dati affidabili; apatia → incentivi che hanno punito l'iniziativa. Nella perizia, l'Hidden Want di ogni personaggio deve agganciarsi a questa logica (paura della vergogna, rivalsa, controllo, panico finanziario).

## Ancoraggio materico — palette di distretto

Girare sempre su oggetti fisici reali: lega 7075-T6, olio emulsionabile andato a male, cuscinetto idrostatico che stride, schermo Excel aperto sulle scadenze Ri.Ba., tazza di caffè freddo, carrelli porta-pezzi, distinte base stampate, cellulare personale del commerciale storico. Domestico: cucina alle 21:30, compiti dei figli, lavatrice, luci spente a metà stanza.

## Coordinate vocali per ruolo

- **Tecnico / Capofficina:** frasi brevi, sintassi secca, gergo di banco (mandrino, tolleranze, banco, pezzo dritto/rottame), bestemmia strozzata o silenzio sordo. Non spiega: constata.
- **Venditore / Direttore Commerciale:** ipotetiche fluide ("se poi il cliente…"), minimizzazione dei vincoli tecnici, slancio verbale di copertura, promesse col tempo già compromesso.
- **Titolare / Imprenditore:** mischia cifre e paure; non usa la parola "emozione", chiede "chi me lo garantisce".
- **Partner domestico (Elena/Giulia/Roberto):** nessun gergo da psicologo. Ironia stanca, affetto ruvido, preoccupazione per salute e figli, orario concreto (21:30 in cucina).

## Registro personaggi (da popolare dal manoscritto)

> Template: aggiungere una riga per personaggio a ogni capitolo riscritto. I nomi sotto sono provvisori, ricavati dai prompt di missione — confermare o correggere dal testo reale.

| Personaggio | Ruolo nella filiera | Capitolo POV | Oggetti-totem | Tic verbali | Note |
|---|---|---|---|---|---|
| Andrea | Fondatore (45 anni) società di consulenza per imprese; da 4 a 32 dipendenti; commessa da 400k€, banca "Popolare" | Cap. 1 (bozza) | masseteri a tenaglia, palmi sul piano di rovere, schermo Excel, corridoio di linoleum | frasi che si chiudono ("La verifica l'ho fatta"), tono affilato non urlato | frattura: Accentratore vs Delega |
| Luca | Responsabile operativo, "preciso fino a risultare irritante" | — | cursore mosso senza clic, appunti, fogli | formula procedurale: «una seconda firma … è prudenza, non è sfiducia»; tono da verbale; si ritira prendendo appunti | mette "a verbale" la sfiducia; la squadra paga l'operatività |
| Elena | Partner domestico (cucina, sera) | — | coltello e tagliere di faggio, mani di farina, bicchieri che tintinnano, canovaccio sul pane | domande-cronaca («Com'era arrivata la discussione?»), ironia ruvida («telecamera del cazzo») | operatore del terzo neutrale; chiude le scene con gesti (pane coperto, coltello conficcato) |
| Responsabile commerciale (non nominata) | Cliente finale Guidotti | — | fogli raccolti lentamente, occhi sulle note | — | schieramento silenzioso |
| Consulente finanziario (non nominato) | Verifica interna | — | cursore Excel | distinzioni (controllo tecnico vs responsabilità decisionale) | esterno, non sbilancia |
| Paolo Zantedeschi | Auditore esterno (Atto IV) | — | — | — | audit mirato sulle 2 voci (ven→lun 18:00), tetto 4.200€ con doppia firma elettronica |
| Guidotti | Cliente, ordine da firmare | — | — | — | scadenza martedì prossimo |

## Esiti red-teaming (registro di continuità)

| Capitolo | Frattura | Accordo dell'Atto IV | Verdetto | Vincolo che tiene |
|---|---|---|---|---|
| 1 | Accentratore vs Delega | Contratto di Salvaguardia di Processo (riscritto 2026-09-28): audit mirato Zantedeschi sulle 2 voci (ven→lun 18:00), cap 4.200€ con doppia firma elettronica (matrice >3k€), esito predefinito −15% avviamento, regola permanente seconda firma >100k€, penali Guidotti 2‰/giorno, ordine valido al 15 | YES-BUT (Fase 4) | firme elettroniche datate + scadenza con esito predefinito + penali che rendono lo stallo più caro dell'audit |
