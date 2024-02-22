# SiccardiTableDialogCespiti
Definire una JFrame per caricare una jTable Cespiti (String codice; int quantita; LocalDate dataAcquisto;)
Caricare i dati da una JDialog, da cui caricare la tabella sottostante.
Alla chiusura della JDialog, aggiornare sia l'elenco cespiti, che la JTable.

Occuparsi di gestire le modifiche di eventuali dati direttamente nella JTable, attraverso il metodo JTableChanged, di cui sono riportati qui dei link di esempio per l'implementazione. Cioè quando avvengono modifiche nella tabella questi vanno aggiornati nell'elenco di cespiti.

Da un menù in alto nella pagina, esportare i dati in un file csv o file json, o da 2 pulsanti a lato della tabella.

Il formato JSON json.org, richiede la libreria gson per essere salvata, un esempio di uso è nel link qui sotto. La libreria gson.jar qui allegata, va posta in una cartella lib/gson.java e selezionata come library dal menù File/Project structure.
