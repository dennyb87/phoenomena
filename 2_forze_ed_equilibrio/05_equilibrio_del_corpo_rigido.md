# Corpo rigido esteso  

Il **corpo rigido**, per brevita', e' il modello che si utilizza quando non e' possibile semplificare il corpo da esaminare ad un punto materiale. **Rigido** in quanto non subisce deformazioni apprezzabili sotto l'azione di forze. **Esteso** in quanto le forze possono essere applicate in punti diversi del corpo.  


## Somma di forze su corpi rigidi  

Nel caso di un corpo rigido, valgono le stesse leggi del punto materiale quando le forze giaciono sulla stezza retta d'azione, o quando le rette d'azione di intersecano. E' importante notare che i punti di applicazione non devono necessariamente coincidere.  

![forces_rigid_body_01](https://github.com/dennyb87/phoenomena/assets/7195133/a4fec870-6877-474f-9caa-44e9dd3bd90c)  

Quando le forze giaciono su rette d'azione parallele concordi o discordi si ricorre alle formule qui sotto. In questi casi potrebbe manifestarsi una rotazione del corpo che vedremo in dettaglio piu' avanti. E' importante notare che il punto di applicazione $P$ e' tale che:  

$\dfrac{F_2}{F_1} = \dfrac{d_1}{d_2}$  

![forces_rigid_body_02](https://github.com/dennyb87/phoenomena/assets/7195133/b2bfd181-cf6a-4f04-ba0e-4b094636e284)  

# Momento di una forza  

![braccio_forza_porta](https://github.com/dennyb87/phoenomena/assets/7195133/71c581af-97c8-48dd-adf5-3175b4904a8b)  

Nel tentativo di aprire una porta, ci si rende conto che per ottenere la stessa rotazione serve una forza maggiore quanto piu' il punto di applicazione si avvicina allo stipite. Concludiamo che la rotazione dipende non solo dalla forza ma anche dalla distanza dallo stipite. Per tenere conto di questo si introduce una nuova grandezza vettoriale chiamata **momento**, e il suo modulo e' definito come:  

$M = F \cdot b$  

Dove $b$ e' chiamato **braccio** della forza, ovvero la lunghezza della perpendicolare alla retta d'azione dal centro di rotazione. La sua unita' di misura e' quindi newton metri $Nm$  

![momento_01](https://github.com/dennyb87/phoenomena/assets/7195133/ec3724d8-688b-4c71-852f-770e863e4eed)  

Il verso di $\vec{M}$ ci da indicazioni sul senso di rotazione, seguendo la regola della mano destra.  

![momento_02](https://github.com/dennyb87/phoenomena/assets/7195133/fb7a681d-7552-4294-aef5-8d425b124606)  

## Momento di una coppia di forze  

Si dice coppia di forze quando le forze giaciono su rette d'azione parallele, hanno la stessa intensita', ma verso opposto. E' importante notare che questo da luogo ad una rotazione.  

![momento_coppia_01](https://github.com/dennyb87/phoenomena/assets/7195133/21f77713-9c54-4f3f-8079-565b3938d59c)  

Una coppia di forze da vita a due momenti:  

$M_1 = F_1 \cdot b_1$  

$M_2 = F_2 \cdot b_2$  

Il momento risultante della coppia $M_c$ sara' quindi...  

$M_c = M_1 + M_2 = (F_1 \cdot b_1) + (F_2 \cdot b_2)$  

Ma $F = F_1 = F_2$ allora..  

$M_c = F \cdot (b_1 + b_2)$  

Il **momento di una coppia** individua la rotazione di un corpo dovuta ad una coppia di forze. Il suo modulo e' definito come:  

$M_c = F \cdot d$  

Dove $d$ e' la lunghezza della perpendicolare tra le rette d'azione.  

## Equilibrio del corpo rigido  

Da una coppia di forze si otterrebbe un modulo risultante nullo, portandoci a pensare che il corpo sia fermo, eppure sappiamo per esperienza che una coppia di forze causa la rotazione del corpo. Concludiamo che nel caso del corpo rigido le condizioni di equilibrio sono:  

* forze risultante nulla $F_{tot} = 0$
* momento risultante nullo $M_{tot} = 0$

Ovvero la somma vettoriale di tutte le forze cosi' come quella di tutti i momenti deve essere nulla.  

## Corpo rigido appoggiato  

I corpi rigidi si comportano come se la forza peso agisse in un solo punto detto centro di gravita' o baricentro. Un corpo rigido appoggiato pertanto, e' in equilibrio fin tanto che la perpendicolare dal baricentro cade all'interno della base di appoggio.  

![baricentro_01](https://github.com/dennyb87/phoenomena/assets/7195133/f1162770-507e-4522-ade8-2ba3fbe73e26)  

## Corpo rigido appeso  

Un corpo rigido appeso tende a posizionarsi, se i vincoli lo permettono, in modo che il baricentro assuma la posizione piu' bassa. In particolare esistono tre tipi di equilibrio: **stabile**, **instabile**, **indifferente**.  

![equilibrio_corpo_appeso_01](https://github.com/dennyb87/phoenomena/assets/7195133/4a6fe23d-138b-4e0f-820e-aa3d62174985)  

# Leve  

Quando parliamo di **macchina**, si parla di qualunque dispositivo che permetta di agire su una forza utilizzando un'altra forza. In particolare si dice **macchina semplice** quando permette di equilibrare una forza (**resistenza**) con un altra forza (**motrice**). La leva e' una macchina semplice composta da un **asse** rigido e fisso, libero di ruotare attorno ad un punto fisso chiamato **fulcro**. Il tipo di leva dipende dalla configurazione di fulcro, resistenza, e forza motrice.  

![tipi_leve](https://github.com/dennyb87/phoenomena/assets/7195133/2c7d2a66-8887-4495-ab90-bb9f53972783)  

Quando il momento della forza motrice e il momento della resistenza sono uguali si verifica la **condizione di equilibrio**.  

![altalena_leva](https://github.com/dennyb87/phoenomena/assets/7195133/7b3c23fe-c101-4398-bec5-4de07ffb586b)  

L'altalena, essendo una leva di **primo genere**, sara' in equilibrio quando $M_{tot} = 0$ ovvero quando:  

$R \cdot b_R = F \cdot b_F$  

Se il bambino fosse piu' pesante $R > F$ allora dovrebbe avvicinarsi al fulcro per equilibrare la situazione $b_R < b_F$. In questo caso particolare dove $F = R$ e $b_R = b_F$ si dice che la leva e' **indifferente**.  

![leva_vantaggiosa_01](https://github.com/dennyb87/phoenomena/assets/7195133/8d3eed88-4759-4aac-b549-c4f0b2587024)  

Nello schiaccianoci si ha una leva di **secondo genere** in quanto il braccio della resistenza e' minore di quello della forza $b_R < b_F$ per cui sara' sufficiente una forza minore della resistenza $F < R$ per raggiungere l'equilibrio, siamo quindi di fronte ad una **leva vantaggiosa**.  

![leva_svantaggiosa_01](https://github.com/dennyb87/phoenomena/assets/7195133/631d27a3-403f-4ce1-ac2a-69079213d320)  

Il contrario vale per le pinzette, una leva di **terzo genere**, dove il braccio della forza e' minore di quello della resistenza $b_R > b_F$ per cui l'equilibrio si ha con $F > R$ siamo quindi di fronte ad una **leva svantaggiosa**.  