# Lavoro di Tesi: Voci dall'Inferno

**Codifica di una testimonianza orale di Goti Bauer**  
Università di Pisa – Corso di Laurea in Informatica Umanistica  
Lavoro realizzato per il tirocinio universitario e per la tesi triennale.

Il progetto riguarda la trascrizione e la codifica XML-TEI di una testimonianza orale di Goti Bauer, in particolare di un’intervista realizzata dalla professoressa Marina Riccucci, per preservare e rendere consultabili i contenuti in formato digitale. Durante lo sviluppo dell'applicazione web, sono state implementate funzionalità per la consultazione dei dati, utilizzando **XQuery** per estrarre e visualizzare informazioni rilevanti come una mappa dei luoghi citati e una mappa che illustra gli spostamenti fatti dal testimone.

L'ambiente di sviluppo per l'applicazione web è stato **existDB**, una piattaforma di gestione di database XML che consente l'elaborazione e la consultazione efficiente dei dati XML.

## Contenuto del repository

- `file.xml` – Codifica originale dell'intervista audio in formato XML.
- `file_definitivo.xml` – Codifica finale dell'intervista.
- `intervista.txt` – Trascrizione dell'intervista audio in formato testo.
- `dtd-tei.dtd` – DTD (Document Type Definition) standard per la codifica XML-TEI.
- `dtd-voci-inferno.dtd` – Versione personalizzata del DTD per il progetto *Voci dall'Inferno*.
- `tesi.pdf` – Documento PDF della tesi triennale, con la descrizione del progetto e dei metodi utilizzati.

## Tecnologie utilizzate

- **XML-TEI** per la codifica del testo.
- **XQuery** per l'estrazione dei dati dalla codifica e la generazione di contenuti dinamici per la web app.
- **existDB** come ambiente di sviluppo per la gestione e la consultazione dei dati XML.
- **Web app** per la visualizzazione della testimonianza e delle informazioni correlate.

