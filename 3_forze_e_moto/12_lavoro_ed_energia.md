# Lavoro  

![force_displacement](https://github.com/dennyb87/phoenomena/assets/7195133/b2911bbe-6b17-4c26-a71f-64213463887d)  

In fisica si parla di lavoro quando all'applicazione di una forza ne consegue uno spostamento del corpo interessato. Formalmente viene definito come:  

> Il prodotto tra la componente della forza in direzione dello spostamento, e lo spostamento stesso.  

$L = \vec{F}_s \cdot \vec{s}$  

La sua unita' di misura e' il **joule** $J$  

$1\ J = 1\ N \cdot m$  

![work_and_angles](https://github.com/dennyb87/phoenomena/assets/7195133/3683d6f6-ebd7-4bef-a66b-6f618475fff2)  

Si parla di **lavoro positivo** (o motore) per $\theta \lt 90^\circ$ mentre si dice **negativo** (o resistente) quando $\theta \gt 90^\circ$. Con un angolo retto il lavoro e' invece nullo in quanto la forza applicata non contribuisce in alcun modo allo spostamento.  

![positive_negative_work](https://github.com/dennyb87/phoenomena/assets/7195133/0c9c1d9d-d326-4c15-b88b-12faa67a6a3f)  

Sollevando un corpo da terra stiamo compiendo lavoro positivo, mentre la forza peso essendo contraria alla direzione dello spostamento, compie lavoro negativo.  

# Potenza  

Una volta introdotto il lavoro diventa utile poter capire quanto lavoro viene svolto in un intervallo di tempo, nasce cosi' una nuova grandezza detta **potenza**, formalmente:  

> Il rapporto tra il lavoro compiuto e l'intervallo di tempo impiegato  

$P = \dfrac{L}{\Delta t}$  

La sua unita' di misura e' il *watt* $W$  

$1\ W = 1\dfrac{J}{s}$  

Essendo $1\ W$ una potenza molto piccola si ricorre solitamente ai suoi multipli e.g. $1\ kW = 1000\ W$  

# Energia  

Il nostro corpo possiede la capacita' di sollevare un libro da terra indipendentemente dal fatto che questa azione venga compiuta o meno. La possibilita' che venga compiuto del lavoro viene appunto detta **energia**.  

> La capacita' di compiere lavoro  

L'energia esiste in molte forme e.g. cinetica, gravitazionale, elettrica etc.. dalle quali possiamo attingere per ottenere del lavoro. Dato che quello che prima era energia puo' essere trasformato in lavoro, ne segue che hanno la stessa unita' di misura, il **joule**. L'energia puo' essere espressa anche in **kilowattora** dove $1\ kWh$ e' la quantita' di energia uguale ad una potenza di $1\ kW$ erogata per un ora.  

$1\ kWh = 1\ kW \cdot 1\ h = 1000\ W \cdot 3600\ s = 3.6 \cdot 10^6\ J$  

## Energia cinetica  

Si puo' intuire che un corpo in movimento possa causare lo spostamento di altri corpi per esempio grazie ad un urto. L'energia che un corpo possiede per il solo fatto di essere in movimento prende il nome di **energia cinetica**. E' dimostrabile che questa energia equivale al lavoro necessario per portare un corpo di massa $m$ dallo stato di quiete $v_i = 0$ alla velocita' desiderata $v_f$.  

$L = \vec{F}_s \cdot \vec{s}$  

Ricaviamo quindi il tempo per poi trovare il modulo dello spostamento assumendo un moto rettilineo uniformemente accelerato con il corpo inizialmente fermo.  

$v_f = at \implies t = \dfrac{v_f}{a}$  

$s = \frac{1}{2}at^2 = \frac{1}{2}\cancel{a}\dfrac{v_f^2}{a^{\cancel{2}}} = \dfrac{v_f^2}{2a} =\frac{1}{2}mv_f^2$  

Sostituiamo nella formula del lavoro...  

$L = F_s \cdot s = m \cdot a \cdot s = m\cancel{a}\dfrac{v_f^2}{2\cancel{a}} \implies \frac{1}{2}mv_f^2$  

Si ha allora che l'**energia cinetica** $E_c$ del corpo e' uguale al lavoro necessario per accelerarlo alla velocita' che possiede.  

$L = E_c = \frac{1}{2}mv_f^2$  

E' importante notare che nel nostro esempio il corpo era inizialmente in stato di quiete, ma piu' in generale, con $v_i \ne 0$ e' possible dimostrare che il lavoro compiuto da una forza che sposta un corpo dalla posizione iniziale $i$ alla posizione finale $f$ e' uguale alla variazione di energia cinetica del corpo nel corso di tale spostamento.  

$L = \Delta E_c = E_{cf} - E_{ci} = \frac{1}{2}mv_f^2 - \frac{1}{2}mv_i^2$  

# Energia potenziale gravitazionale  

![gravitational_potential_energy](https://github.com/dennyb87/phoenomena/assets/7195133/36186fc3-c89b-45e3-b0fd-1377aff91b1e)  

Lasciando cadere una palla, questa grazie alla forza gravitazionale viene accelerata guadagnando quindi energia cinetica che puo' essere usata per fare lavoro. E' evidente che e' la sua posizione a permettergli di cadere, si dice allora **energia potenziale gravitazionale** quelle che un corpo possiede a causa della sua posizione nel campo gravitazionale rispetto ad un livello di riferimento scelto.  

$E_{Pg} = mgh$  

E' importante notare che il lavoro necessario per portare la palla all'altezza $h$ e' prioprio $Ph = mgh$ che una volta compiuto si trasforma in energia di posizione. Ne segue che questo tipo di energia e' riconducibile ad un lavoro che e' stato compiuto sul corpo che e' soggetto a forze.  

# Energia potenziale elastica  

Allungango o comprimendo una molla rispetto alla sua posizione di equilibrio e' possibile immagazzinarvi energia. In modo analogo all'energia potenziale gravitazionale, quella elastica e' pari al lavoro necessario per comprimere la molla, ovvero:  

$E_{Pel} = \frac{1}{2}K \cdot \Delta L^2$  

Dove $K$ e' la costante elastica e $\Delta L$ la variazione di lunghezza della molla.  
