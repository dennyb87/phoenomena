# Principi della dinamica  

La dinamica si occupa dello studio del moto dei corpi a partire dalle loro cause, le forze.  Il primo principio della dinamica si basa su un esperimento ideale, ed e' proprio per questo che prende il nome di principio, in quanto non puo' essere dimostrato, ne' l'esperimento realizzato concretamente.  

## Primo principio  

Consideriamo il caso di un'automobile in strada il cui motore viene spento mentre e' in movimento, questa rallentera' fino a fermarsi completamente.  

![newton_first_law](https://github.com/dennyb87/phoenomena/assets/7195133/4c503a39-69a4-4bc1-9dae-42d8f94835bf)  

Se invece dell'asfalto l'auto fosse sopra una superficie ghiacciata, dopo aver spento il motore, l'auto continuerebbe a muoversi per un tempo maggiore, percorrendo quindi anche una distanza maggiore. Si intuisce allora che la forza del motore serve a vincere le forze di attrito, ed immaginando quindi di poter eliminare queste tutte queste forze, concludiamo che l'auto continuerebbe a muoversi all'infinito.  

> In assenza di forze, un corpo fermo continua a rimanere fermo, se invece si muove di moto rettilineo uniforme, prosegue secondo tale moto

Chiamato anche **principio d'inerzia** perche' esprime l'inerzia dei corpi, ovvero la tendenza, quando le forze sono nulle, a restare nello stato in cui si trovano. Una sorta di **resistenza** ad adeguarsi ai cambiamenti della situazione in cui si trovano.  

## Secondo principio  

Il primo principio ha messo in evidenza che la forza non e' la causa della velocita', bensi' la causa di una variazione di velocita', ovvero un'accelerazione. Ad esempio, una volta avviato il moto di una bicicletta, pedalare serve soltanto a vincere le forze d'attrito mantenendo la velocita' costante. Uno sforzo maggiore nella pedalata aumentera' la velocita', percio' concludiamo che esiste una relazione tra forza e variazione di velocita'.  

> L'accelerazione di un corpo e' direttamente proporzionale alla forza che ne e' la causa  

Se ad esempio spingo un corpo con una forza $F$ ottengo un'accelerazione $a$, ma se qualcuno mi aiuta allora con la forza $2F$ si avrebbe $2a$. Si ha allora che $\dfrac{F}{a}$ e' una costante, e questa costante prende il nome di **massa inerziale**, o piu' semplicemente, **massa**.  

$\dfrac{F}{a} = m \implies F = m \cdot a$  

![newton_second_law_graph](https://github.com/dennyb87/phoenomena/assets/7195133/1d70a5cc-61b4-4873-b907-af861859b56d)  

Si nota immediatamente che a parita' di forza, il corpo con massa maggiore subisce un'accelerazione minore, e viceversa. Ricavando invece $a = \dfrac{F}{m}$ notiamo come $a$ ed $m$ siano inversamente proporzionali.  

![newton_2nd_law_acceleration_mass_graph](https://github.com/dennyb87/phoenomena/assets/7195133/3b30a194-5f5a-412e-bada-460323684f1f)  

## Terzo principio  

> Ad ogni azione corrisponde una reazione uguale in modulo e direzione ma di verso opposto  

![newton_third_law](https://github.com/dennyb87/phoenomena/assets/7195133/fe33f976-f316-4a55-8e5a-39b7865619d8)  

$F_2 = - F_1$  

Detto anche principio di azione e reazione, e' valido sia per le forze di contatto, sia per le forze a distanza come quelle gravitazionali. Ma perche' allora se la stessa forza esercitata dalla terra sulla pallina, viene esercitata dalla pallina sulla terra, la terra non si sposta ?  

![third_law_earth](https://github.com/dennyb87/phoenomena/assets/7195133/3342168b-d2cb-4350-aaca-d60ee243febe)  

Come abbiamo visto, a parita' di forze l'accelerazione dipende dalle masse. Per cui la forza esercitata dalla pallina non e' sufficiente a far muovere la terra in modo apprezzabile ad occhio nudo.  

$m_{terra} = 5.98 \cdot 10^{24}\ kg$  
$F_{mela} = 2.5\ N$  

$a_{terra} = \dfrac{F_{mela}}{m_{terra}} = \dfrac{2.5}{5.98 \cdot 10^{24}} \simeq 4.18 \cdot 10^{-25}\ \small\frac{m}{s^2}$  

# Sistemi di riferimento  

![frame_of_reference_01](https://github.com/dennyb87/phoenomena/assets/7195133/7837842a-9064-4fc2-9ed0-7e7282e7b266)  

Quando l'autobus accelera ci sentiamo spinti nella direzione opposta, ed il primo principio della dinamica sembra apparentemente violato. Dal punto di vista dei passanti invece l'accelerazione dell'autobus rivela giustamente una forza come ci si aspetta dal primo principio. Concludiamo allora che il primo principio e' valido soltanto nei sistemi di riferimento chiamati **inerziali**, ovvero un sistema di riferimento in cui non ci sono accelerazioni di nessun tipo.  

Non e' facile determinare quali siano o se esistano effettivi sistemi inerziali, tuttavia con buona approsimazione possiamo ritenere la terra, e tutti i sistemi di riferimento di moto rettilineo uniforme rispetto ad essa dei **sistemi di riferimento inerziali** soddisfacenti.  

## Trasformazioni di Galileo  

![galilean_transformation](https://github.com/dennyb87/phoenomena/assets/7195133/1e024177-62e2-494d-ab81-7db5cb884dec)  

Il principio di relativita' galileiano ci dice che le leggi fisiche sono le stesse nei sistemi di riferimento inerziali, per cui dati due sistemi di riferimento $O$ e $O^\prime$ dove inizialmente $O \equiv O^\prime$. Se $O^\prime$ si muove di moto rettilineo uniforme con velocita' $v$ avremo che dopo un tempo $t$ sara' possibile individuare il punto $P$ per entrambe i sistemi con:  

$$
P_{kevin}\ \begin{cases}
  \begin{aligned}
    y &= y^\prime \\
    x &= x^\prime + vt \\
  \end{aligned}
\end{cases}
$$  

$$
P_{jennie}\ \begin{cases}
  \begin{aligned}
    y^\prime &= y \\
    x^\prime &= x - vt \\
  \end{aligned}
\end{cases}
$$

E' importante notare che in entrambe i sistemi di riferimento i tempi coincidono $t = t^\prime$ mentre la posizione di $P$ risulta diversa, le equazioni percio' dipendono dal sistema di riferimento scelto.  

## Composizione della velocita'  

![relativita_galileiana](https://github.com/dennyb87/phoenomena/assets/7195133/08b59406-7500-4abd-8209-40065a726485)   

Sempre grazie al principio di relativita' galieliano se Matteo si muove di moto rettilineo uniforme in un sistema di riferimento anch'esso di moto rettilineo uniforme a velocita' a differenti, per un sistema di riferimento stazionario possiamo scrivere...  

$V_{matteo} = v^\prime + v_s$  
