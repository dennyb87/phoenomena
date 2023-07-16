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

Supponendo di aver misurato $b = 390\pm 1\ cm$ possiamo trovare la superficie $A_m = b_m \cdot h_m = 390 \cdot 352 = 137\,280\ cm^2$ che pero' puo' variare tra un valore minimo e massimo ottenuto come segue:  

$A_{min} = b_{min} \cdot h_{min} = (390 - 1) \cdot (352-1)= 136\,539\ cm^2$  

$A_{max} = b_{max} \cdot h_{max} = (390 + 1) \cdot (352+1) = 138\,023\ cm^2$  

Allora per trovare l'incertezza si procede prima sommando gli errori relativi, quindi trovando l'errore relativo dell'area.  

$\varepsilon_r (b) = \dfrac{1}{390} = 0.00256$  

$\varepsilon_r (h) = \dfrac{1}{352} = 0.00284$  

$\varepsilon_r (A) = \varepsilon_r (b) + \varepsilon_r (h) = 0.00256 + 0.00284 = 0.0054$  

Poi si moltiplica l'errore per il valore della grandezza dell'area trovando la sua incertezza.  

$\Delta x(A) = \varepsilon_r (A) \cdot A_m = 0.0054 \cdot 137\,280\ = 741.312\ cm^2$  

Si noti che e' possibile dimostrare che:  

$\Delta x(A) = \varepsilon_r (A) \cdot A_m = \dfrac{A_{max}-A_{min}}{2}$  

Possiamo allora dire che l'**errore relativo** di una grandezza derivata da un prodotto o da un quoziente e' dato dalla somma degli errori relativi di tali grandezze.  

| operazione                | legge di propagazione                                    |
| ------------------------- | -------------------------------------------------------- |
| somma: $S = A + B$        | $\Delta x(S) = \Delta x(A) + \Delta x(B)$                |
| differenza: $D = A - B$   | $\Delta x(D) = \Delta x(A) + \Delta x(B)$                |
| prodotto: $P = A \cdot B$ | $\varepsilon_r(P) = \varepsilon_r(A) + \varepsilon_r(B)$ |
| quoziente: $Q = A/B$      | $\varepsilon_r(Q) = \varepsilon_r(A) + \varepsilon_r(B)$ |

## Criteri di arrotondamento  

Dei diversi criteri di arrotondamento scegliamo i seguenti:  

* l'incertezza si arrotonda sempre per **eccesso** alla prima cifra significativa diversa da zero da sinistra verso destra
*  il valore della grandezza si arrotonda per eccesso o per difetto in corrispondenza della posizione della cifra significativa dell'incertezza

Nel nostro caso si ha che:  

$\Delta x(A) = \textbf{7}41.312\ cm^2 \implies \textbf{8}00\ cm^2$  

$A_m = 137\, \textbf{2}80\ cm^2 \implies 137\, \textbf{3}00\ cm^2$  

Possiamo infine scrivere...  

$A = 137\,300\pm 800\ cm^2 \implies 13.73\pm 0.08\ m^2$  

E' importante notare di fronte ad una misura, il valore della grandezza e l'incertezza possono avere origini diverse, riassumiamo quindi le differenti situazioni che possono portare alla scrittura di una misura.  

| misura           | =   | valore della grandezza | $\pm$ | incertezza             |
| ---------------- | --- | ---------------------- | ----- | ---------------------- |
| misura diretta   | =   | valore misurato        | $\pm$ | errore di sensibilita' |
| serie di misure  | =   | valore medio           | $\pm$ | errore massimo         |
| misura indiretta | =   | valore calcolato       | $\pm$ | errore di propagazione |

## Gli strumenti  

Gli strumenti sono principalmente caratterizzati da:  

* sensibilita'
* portata (o fondo scala)
* precisione

La **sensibilita**' ovvero la piu' piccola variazione apprezzabile determina anche l'errore di sensibilita' che coincide quindi con il valore di una divisione sulla scala dello strumento.  

La **portata** (o valore di fondo scala) e' il valore massimo che lo strumento puo' misurare, in certi casi oltrepassarlo puo' comprometterne il funzionamento.  

La **precisione** (qui una definizione puramente qualitativa) descrive l'affidabilita' dello strumento e non va confusa con la sensibilita' e.g. strumenti molto sensibili possono essere imprecisi. In particolare misurando piu volte la stessa grandezza si deve ottenere sempre lo stesso risultato, ed i valori forniti devono essere in accordo con quelli di un altro strumento noto come affidabile.  

## Taratura  

Per rendere uno strumento idoneo all'effettuazione di una misura occorre appunto una taratura, ovvero una serie di operazioni che permettono collocare una scala graduata sullo strumento e.g. confrontando il valore di una grandezza misurata con lo strumento e il valore ottenuto con lo strumento campione.