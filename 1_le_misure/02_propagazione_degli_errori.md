# Tipi di errore  

La misura puo' essere influenzata da diversi tipi di errore, quando questi non sono prevedibili si dicono **casuali** o **accidentali**, i quali data loro natura influenzano la misura sia per eccesso che per difetto e.g.

* intervento dell'operatore (lettura errata e.g. errore di parallasse)
* condizioni ambientali (temperatura, pressione...)
* condizioni di funzionamento dello strumento

Esistono poi errori che influenzano la misura soltanto in uno dei due sensi, sempre per eccesso o sempre per difetto, questi si dicono **errori sistematici** e.g. una bilancia scarica che segna $20\ g$ dara' valori maggiori ad ogni lettura. Questi sono spesso causati da:  

* utilizzo in condizioni non previste
* interferenza dello strumento con la grandezza da misurare
* difetti di costruzione

# Serie di misure  

Si ha una **serie di misure** in due casi:  

* la misurazione viene fatta su tanti oggetti o fenomeni ripetuti, teoricamente uguali, ottenendo quindi diversi valori riguardanti la stessa grandezza, ad esempio se volessimo misurare la lunghezza di tutte le auto in un parcheggio
* la misurazione viene ripetuta ma sempre su un unico oggetto, ad esempio se chiedessimo a $n$ persone di misurare la nostra auto

Per esprimere il risultato delle misurazioni occorre allora trovare un numero che ci permetta di tenere conto dei contributi di ogni misurazione, si va allora a calcolare il **valore medio** ovvero quel valore che ripetuto per ogni misurazione, ci darebbe, sommando tutti i valori, lo stesso risultato ottenuto con la serie effettiva.  

$valore\ medio = \dfrac{somma\ dei\ valori\ delle\ misure}{numero\ di\ misure} = \dfrac{x_1+x_2+...+x_n}{n}$  

Adesso non ci resta che trovare un'incertezza ragionevole. In realta' esistono molti modi per determinare l'incertezza di una serie, il procedimento piu' semplice e' quello del calcolo dell'**errore massimo** definito come segue:  

$\Delta x = \dfrac{x_{max}-x_{min}}{2}$  

# Le misure indirette  

La **misura indiretta** e' ottenuta effettuando calcoli utilizzando misure di cui siamo gia' a conoscenza, ad esempio calcolare la superficie di un pavimento a partire dai suoi lati $A = b \cdot h$  

In questo caso si parla di **grandezza derivata** in quanto l'area e' stata misurata indirettamente.  

Se volessimo davvero fare questa misura, dovremmo prima misurare i lati del pavimento $b$ ed $h$, ma se la loro lunghezza e' maggiore del nostro metro a nastro da $200\ cm$ di sensibilita' $0.5\ cm$ si pone allora il problema di determinare l'incertezza della nostra misura.  

Misuriamo allora $h = h_1 + h_2$ e scopriamo che...  

$h_1 = 200\pm 0.5\ cm$  
$h_2 = 152\pm 0.5\ cm$  

E' evidente allora che l'incertezza totale e' data dalla somma delle incertezze di ogni misura in quanto contengono lo stesso tipo di errore. Si ha allora che...  

$\Delta x(h) = \Delta x(h_1) + \Delta x(h_2) = 0.5 + 0.5 = 1\ cm$  

$h = 352\pm 1\ cm$  

Piu' in generale possiamo dire che l'incertezza di una grandezza ottenuta come somma (o differenza) di altre grandezze e' data dalla somma delle incertezze di tali grandezze.  

