# Le Misure  

La fisica si occupa dello studio dei **fenomeni** che accadono in natura, attraverso quelle che che vengono chiamate **grandezze fisiche**. I fenomeni fisici vengono analizzati utilizzando il **metodo sperimentale**, introdotto per la prima volta da Galilei.    

```mermaid
flowchart LR
    F[osservazione fenomeno]-->ipotesi
    ipotesi-->V{verificata ?}--si-->legge
    V--no-->ipotesi
    legge-->applicazione
    applicazione-->F
```

Questo metodo ci permette di descrivere i fenomeni in modo quantitativo, giungendo a conclusioni oggettive utili ad esempio per poter fare previsioni o progetti.  

Per poter effettuare calcoli c'e' allora bisogno di associare un numero a queste grandezze fisiche. Questo numero si ottiene facendo appunto una **misura**, ovvero un **confronto** tra la grandezza in esame ed una grandezza di riferimento, ovvero l'**unita' di misura**.  

Par fare in modo di poter scambiare informazioni sulle grandezze e' necessario scegliere, anche se in modo arbitrario un **campione di riferimento**, detto appunto unita' di misura. E' importante rendersi conto che senza unita' di misura il valore numerico di una grandezza e' privo di significato.  


## Errore di sensibilita'  

Effettuando ad esempio una misura utilizzando il metro da sarto, notiamo che l'oggetto misura poco piu' di $2.5\ cm$.  

![errore_di_sensibilita](https://github.com/dennyb87/phoenomena/assets/7195133/35473062-11da-4477-91a6-3dafc1c505e8)  

Allora scopriamo che non e' possibile dire con certezza quale sia la misura dell'oggetto in esame, ma bisogna tenere conto dell'errore di sensibilita' dello strumento, ovvero la piu' piccola variazione della grandezza che e' in grado di rilevare, in questo caso $1\ mm$.  

Allora con 25 divisioni si ha che il **valore della grandezza**, ovvero la quantita' numerica che leggiamo sullo strumento e':  

$25 \cdot 0.1 = 2.5\ cm$  

Ma dovendo tenere conto dell'errore di sensibilita' scriviamo allora che la lunghezza $\ell$ dell'oggetto in esame e':  

$\ell = 2.5\pm0.1\ cm$  

Dove $2.5$ e' il valore della grandezza, mentre $\pm0.1$ e' l'**incertezza** della misura, il quale ci permette di individuare l'**intervallo di indeterminazione**, ovvero l'intervallo di possibili valori all'interno del quale rientra il valore della grandezza misurata, in questo caso $2.4\ cm \le \ell \le 2.6\ cm$.  

E' importante rendersi conto che l'incertezza di una misura puo' essere causata da diversi tipi di errore, come vedremo in seguito.  

## Misure e grandezze  

Quando la grandezza da misurare viene confrontata direttamente con il campione scelto come unita' di misura si parla di **misura diretta**. Se invece la misura viene eseguita attraverso calcoli ottenuti conoscendo misure di altre grandezze si parla allora di **misura indiretta**. Le grandezze misurate indirettamente si dicono **grandezze derivate**. Nel termometro per esempio si osserva la posizione del mercurio, quindi una lunghezza, a cui e' stata associata una temperatura.  

## Errore relativo  

Consideriamo le seguenti misure:  

$\ell_1 = 2\pm 0.5\ cm$  
$\ell_2 = 14\pm 0.5\ cm$  

L'incertezza e' identica, ma si intuisce immediatamente che la stessa incertezza ha un peso diverso a seconda del valore della grandezza misurata. Per tenere conto di questo si utilizza l'**errore relativo** $\varepsilon_r$ ovvero il rapporto tra l'incertezza $\Delta x$ ed il valore della grandezza misurata $x_m$. Questo rapporto esprime quindi la precisione di una misura, in questo caso si ha che:  

$\varepsilon_r = \dfrac{\Delta x}{x_m}$  

$\varepsilon_{r1} = \dfrac{0.5}{2} = 0.25$  

$\varepsilon_{r2} = \dfrac{0.5}{14} = 0.0357$  

La misura piu' precisa e' allora quella con l'errore relativo minore.  

## Sistema internazionale di unita' di misura  

Il sistema internazionale di unita' di misura **SI** nasce per facilitare la comunicazione ed il commercio, e definisce appunto le unita' di misura delle grandezze fondamentali, con le quali e' possibile derivare tutte le altre, si mettono in evidenza di seguito alcune di queste.  

| grandezza | unita' di misura   | simbolo |
| --------- | ------------------ | ------- |
| massa     | **k**ilo**g**rammo | kg      |
| lunghezza | **m**etro          | m       |
| tempo     | **s**econdo        | s       |

Si noti che le definizioni di queste unita' di misura si evolvono nel tempo, ad esempio il kilogrammo era inizialmente definito come $1\ dm^3$ di acqua distillata alla temperatura di $4^\circ C$, mentre piu' avanti e' stato sostituito con un campione cilindrico equilatero di platino-iridio.  

Ogni unita' di misura ha dei **multipli** e **sottomultipli**  basati sulle potenze di 10.  

$1\ mm = 1 \cdot 10^{-3}\ m$  

Ovvero $1$ millimetro equivale a $0.001$ metri.  

 | Potenza di 10 | prefisso | Simbolo |
 | ------------- | -------- | ------- |
 | $10^6$        | mega     | M       |
 | $10^3$        | kilo     | k       |
 | $10^2$        | hecto    | h       |
 | $10^1$        | deca     | da      |
 | $1$           | _        | _       |
 | $10^{-1}$     | deci     | d       |
 | $10^{-2}$     | centi    | c       |
 | $10^{-3}$     | milli    | m       |
 | $10^{-6}$     | micro    | μ       |
