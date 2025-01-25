# Report dei casi di Covid

Questo elaborato analizza i dati della pandemia di COVID-19 forniti da [Our World in Data](https://github.com/owid/covid-19-data). 

L'obiettivo del progetto è di rispondere a determinate richieste da parte del committente, il progetto si sviluppa in questo modo:
1. Una prima e generica esplorazione del dataset nella sua forma e nei tipi di dato che contiente
   - Si sviluppa più nello specifico sull'analisi dei dati nulli e sulle discrepanze tra i valori delle colonne total_cases e new_cases
2. Si risponde in maniera breve e concisa alla richiesta di verificare le dimensioni del dataset e i relativi metadati
3. Si analizzano i dati dei casi totali suddivisi per continente e dlle relative percentuali sui casi totali globali
   - Si procede con un approccio misto: con output testuali, grafici ed interattivi
   - E' stato scelto questo approccio per tentare di soddisfare un qualsiasi utente finale
4. Analisi dei casi in Italia rispetto al 2022
   - Anche in questo caso è stata fornita una prima visualizzazione testuale dei dati
   - Sussegue una analisi grafica dell'evoluzione del casi totali dall'inizio alla fine dell'anno
   - L'analisi termina con una visualizzazione grafica del numero di nuovi casi rispetto alla data
5. Analisi del numero di pazienti in terapia intensiva (Intensive Care Unit, ICU) da maggio 2022 (incluso) ad aprile 2023 (incluso) in Italia, Germania e Francia
   - Visualizzazione grafica in boxplot
   - Commento finale
6. Analisi del numero totale di pazienti ospedalizzati nel 2023 in Italia, Germania, Francia e Spagna
   - Prima visualizzazione testuale dei dati
   - Visualizzazione grafica con grafico a barre
   - Commento sui dati nulli presenti

## Informazioni utili:
Il dataset (in formato .csv) è acessibile attraverso un link a GoogleDrive, ho implementato la lettura del file da parte di pandas con il link
In questo modo l'elaborato è accessibile da qualsiasi utente.

Non ho implementato chiavi di accesso perché si tratta di un dataset pubblico.

Ho riavviato tutti i kernel per un eventuale controllo della bontà del codice, ma ho lasciato in vista gli output in modo da averli a primo impatto.
