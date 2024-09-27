# Capstone-Project-Robustelli-Michele-Data-Analyst-

1) All'interno del file word è presente il link al drive contenente tutti i file relativi al mio progetto;

2) L'API utilizzata per estrarre il dataset di partenza ed i valori presenti in tale dataset sono continuamente aggiornati da Gamalytic. Pertanto, rilanciando il codice Python contenuto nel file "EstrazioneDatiDaWeb.ipynb" potrebbe essere estratto un dataset contenente valori differenti, colonne differenti/aggiuntive o colonne con valori dotati di un  tipo di dato differente (es: list invece che str). Infatti, l'istruzione "df.duplicated().sum()", avente lo scopo di evidenziare la presenza di valori duplicati, funzionante al momento dell'estrazione iniziale ora non lo è più.
In ogni caso, è possibile verificare dal file Excel "DatasetPartenza.xlsx", contenente il dataset utilizzato frutto del primo utilizzo dell'API, l'assenza di righe duplicate.
