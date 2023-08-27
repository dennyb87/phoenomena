# Moto circolare uniforme  

Si vuole ora studiare il moto curvilineo piu' semplice, ovvero il **moto circolare uniforme**, dove la traiettoria e' una circonferenza, ed il modulo della velocita' e' costante. Sappiamo che la velocita' e' individuata dallo spazio percorso nell'intervallo di tempo, ed in questo caso come spazio viene presa in considerazione la lunghezza della circonferenza, mentre l'intervallo di tempo $T$ detto **periodo**, sara' quello necessario a percorrerla. Il modulo della velocita', detta **tangenziale**, la cui unita' di misura e' sempre *metri al secondo* $\small\frac{m}{s}$ e' allora...  

$v = \dfrac{2\pi r}{T}$  

Al contrario del modulo che resta costante, la direzione del vettore velocita' cambia continuamente. Concludiamo allora che essendo presente una variazione di velocita' seppur solo in direzione, siamo comunque di fronte ad un'accelerazione $a_c$ che prende il nome di **accelerazione centripeta**.  

$a_c = \dfrac{v^2}{r}$  

![centripetal_acceleration](https://github.com/dennyb87/phoenomena/assets/7195133/a1c6e7e0-ee5e-4624-ae89-4cda02fd4e72)  

La formula deriva dal fatto che quando l'intervallo di tempo $\Delta t$ tende a zero, l'angolo $\theta$ formato da $v_1$ e $v_2$ diminuisce, e l'arco di circonferenza tra le due velocita' e' uguale alla corda $s = v \Delta t$. Dato che le due velocita' formano un angolo $\theta$ uguale a quello formato dai raggi $r$ si hanno quindi due triangoli simili. Percio' ricordando che $v = v_1 = v_2$ ...  

$\dfrac{\Delta v}{v} = \dfrac{s}{r} \implies \dfrac{\Delta v}{v}= \dfrac{v \Delta t}{r}$  

$a_c = \dfrac{\Delta v}{\Delta t} = \dfrac{v^2}{r}$  

![centripetal_acceleration_derivation](https://github.com/dennyb87/phoenomena/assets/7195133/115ece3d-9eb4-4124-b3f9-1e484d45987d)  

# Frequenza  

Si vuole introdurre ora il concetto di frequenza, il quale descrive il numero di giri compiuti da un oggetto che si muove di moto circolare uniforme in un intervallo di tempo unitario. I dischi vinile ad esempio esistono da 33 o 45 giri al minuto.  

$f = \dfrac{45}{60} = 0.75\ Hz$  

La sua unita' di misura si chiama **hertz** ed e' dimostrabile che la frequenza e' l'inverso del periodo se consideriamo $n$ il numero di giri e $T$ il tempo necessario a compiere un giro.  

$f = \dfrac{\cancel{n}}{\cancel{n} \cdot T} = \dfrac{1}{T} \implies \dfrac{1}{s} = s^{-1}= 1\ Hz$  

![grafico_freq_periodo](https://github.com/dennyb87/phoenomena/assets/7195133/41ccce3a-f24e-413f-a6f0-58a48790756a)  

Tracciando il grafico frequenza-periodo si nota che all'aumentare del periodo la frequenza diminuisce, si dice allora che esiste **proporzionalita' inversa** tra le due grandezze, o in generale quando il loro prodotto e' una costante.  

$x \cdot y = k \implies y = \dfrac{k}{x}$  

# Moto armonico  

Si dice armonico il moto di un corpo che oscilla attorno ad un punto fisso con un movimento simile in fase di andata e ritorno, come ad esempio un pendolo. Per studiare questo tipo di moto si ricorre ad un modello che consiste nella proiezione sul diametro di un punto materiale che si muove lungo una circonferenza.  

![moto_armonico](https://github.com/dennyb87/phoenomena/assets/7195133/ad3528c1-71e8-4818-b295-cd45d2e412b0)  

Osservando una delle due proiezioni, ad esempio il punto materiale rosso, si puo' notare che la **velocita**' nel moto armonico e' massima al centro e nulla agli estremi. L'**accelerazione** al contrario sara' nulla al centro in quanto non c'e' nessuna variazione di velocita', mentre sara massima agli estremi in quanto il punto materiale e' costretto a fermarsi per poi ripartire nel verso opposto.  

# Pendolo semplice  

![simple_pendulum](https://github.com/dennyb87/phoenomena/assets/7195133/af241c5b-ba70-4a08-9dd0-a28e306cb85d)  

Si vuole ora presentare la formula per il calcolo del periodo del pendolo semplice, ovvero il tempo necessario alla massa $m$ per completare un'oscillazione completa e.g. il punto $B$ e' sia il punto di partenza che quello di arrivo.  

$T = 2\pi \cdot \sqrt{\dfrac{L}{g}}$  

Questa formula e' valida per le piccole oscillazioni, e ci mostra che il periodo:  

* dipende dalla lunghezza $L$
* dipende dall'accelerazione di gravita' $g$
* non dipende dalla massa $m$
* non dipende dall'ampiezza dell'oscillazione (un angolo maggiore produrra' una velocita' maggiore per cui il tempo di oscillazione resta lo stesso)

