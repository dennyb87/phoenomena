# Vettori ed operazioni  

![vettore](https://github.com/dennyb87/phoenomena/assets/7195133/9a069f43-ce1b-49ab-b400-2dc12509fff0)  

Esistono **grandezze scalari**, che e' possibile individuare grazie ad un singolo numero e.g. la lunghezza, altre invece come la forza richiedono informazioni aggiuntive per essere individuate, queste si dicono **grandezze vettoriali**, o semplicemente **vettori**, i quali sono caratterizzati da:  

* modulo (o intensita')
* direzione (la retta su cui giace il vettore)
* verso

Dati due vettori applicati nello stesso punto e' possibile sommarli per trovare il vettore risultante.  

![parallel_vector_sum](https://github.com/dennyb87/phoenomena/assets/7195133/d4b8e1af-0bdd-44f7-a24c-234984679eda)  

Nel caso non siano paralleli si ricorre alla **regola del parallelogramma**, ovvero il vettore risultante ha modulo, direzione e verso, coincidenti con la diagonale del parallelogramma formato dai vettori.  

![regola_parallelogramma](https://github.com/dennyb87/phoenomena/assets/7195133/f8b04487-e582-4acc-af67-7f5aa4742df9)  

Talvolta e' noto solo il vettore risultante, ma attraverso la sua proiezione e' possibile ricavare i suoi componenti conoscendo le loro direzioni. Nel caso particolare in cui tra i vettori ci sia un angolo di $90^\circ$ si puo' calcolare il modulo del vettore risultante grazie al teorema di Pitagora:  

$\lvert\vec{c}\rvert = \sqrt{\lvert\vec{a}\rvert^2 + \lvert\vec{b}\rvert^2}$  

# Equilibrio del punto materiale  

 ![equilibrio_statico](https://github.com/dennyb87/phoenomena/assets/7195133/ee91684c-b996-4e7f-9390-244f1caf8268)  

 Spesso, per evitare di perderci in dettagli trascurabili, si semplificano situazioni reali prendendo in considerazione solo gli aspetti fondamentali del fenomeno in esame, ovvero si utilizza un **modello**. Considerato un libro fermo su un tavolo come in figura, possiamo pensare al libro come un **punto materiale**, ovvero la semplificazione di un corpo, in cui si immagina concentrata tutta la sua materia.  

 In questo scenario il tavolo viene chiamato **vincolo**, ovvero un impedimento che limita parzialmente o totalmente al corpo di muoversi, il quale si deforma anche se in modo non apprezzabile ai nostri occhi, ed esercita una forza sui corpi su esso appoggiati chiamata **reazione vincolare**.  

Un punto materiale si dice in equilibrio quando la somma vettoriale (o forza risultante) di tutte le forze applicate e' nulla.  

$\vec{F_{tot}} = 0$  

Nel nostro esempio si ha una condizione di equilibrio in quanto le forze sono uguali e contrarie $\vec{F_{tot}} = \vec{N} + \vec{G} = 0$  

## Equilibrio su piano inclinato  

![equilibrio_piano_inclinato](https://github.com/dennyb87/phoenomena/assets/7195133/03c99b65-2c53-4f05-83e7-8b29eb590d99)  

Posta una sfera su un piano inclinato, e considerata come punto materiale, si ha una forza peso $F_P$ verso il basso, ed una rezione vincolare $F_V$ che agisce perpendicolare al piano. Si ha qunidi che $F_\parallel$ e' la componente attiva della forza peso, e di conseguenza $\vec{F_E} = - \vec{F_\parallel}$ la forza equilibrante. Concludiamo quindi che la relazione tra forza peso e forza equilibrante e':  

$F_E = F_P \cdot \dfrac{h}{l}$  


# Attrito  

![friction_intuition](https://github.com/dennyb87/phoenomena/assets/7195133/cbfcd69c-4e13-4bb5-a2cf-d9b4d3a1a051)  

Ogni superficie anche se non e' apprezzabile ad occhio nudo, presenta delle irregolarita' che danno origine ad una forza che si oppone allo strisciamento, questa si chiama **forza d'attrito radente** e viene definita come:  

$F_a = K \cdot F$  

Dove $K$ e' il coefficiente d'attrito statico, e tiene conto del materiale delle superfici a contatto, mentre $F$ e' la **forza premente** perpendicolare al piano di appoggio, nel nostro caso coincide con la forza peso. Ne deriva quindi che:  

$K = \dfrac{F_a}{F}$  

E' importante notare che una volta che il corpo e' in movimento, lo sforzo per continuare a spostarlo e' minore di quello iniziale. Si parla allora di **attrito radente dinamico** dove il **coefficiente di attrito dinamico** e' solitamente minore di quello statico.  

Per diminuire lo sforzo necessario a spostare la cassa potremmo:  

* diminuirne il peso riducendo il numer di oggetti al suo interno
* cambiare le caratteristiche della superficie a contatto per renderla piu' scorrevole
* poggiare il baule su un supporto dotato di rotelle

La forza agente tra due corpi che rotolano l'uno sull'altro si dice **forza d'attrito volvente**, ed e' in genere molto piu' piccola di quella derivata dall'attrito radente.  
