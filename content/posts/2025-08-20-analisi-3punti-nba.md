+++
title = "La rivoluzione del tiro da tre"
date = "2025-08-20T17:00:00+02:00"
draft = false
tags = ["basket", "pandas", "jupyter"]
categories = ["blog"]
+++
{{< notice note >}}
Questo post nasce dalla mia passione per il basket NBA e dal desiderio di utilizzarla come spunto per esplorare la libreria [Pandas](https://pandas.pydata.org) in ambiente [Jupyter Notebook](https://jupyter.org).
{{< /notice >}}

### Una rivoluzione partita nel 1979
La stagione **1979/80** ha segnato una svolta storica nella NBA con l’introduzione della linea da tre punti. All’inizio, questo tiro era poco più di una curiosità: un’arma sporadica e rischiosa, lontana dal ruolo centrale che ha oggi, dove rappresenta il fulcro dell’attacco. Forse, a volte, anche un po’ troppo...

![Tiri da 3 punti per partita](/2025-08-20/tiri_3punti_per_partita.png)

Come mostra il *primo grafico*, questa percezione, condivisa da chi segue la NBA, trova un riscontro chiaro e inequivocabile nei numeri.

### Da meno di 3 tentativi a oltre 37
Analizzando i dati dal 1979/80 a oggi emerge che il numero **totale di tiri** tentati mediamente da una squadra a partita è rimasto relativamente stabile, oscillando quasi sempre tra **80** e **90**.  

Ciò che è cambiato radicalmente è il numero di conclusioni da tre punti, passate da **2,8** tentativi per partita nel 1979/80 a **37,6** nella stagione 2024/25, il massimo storico registrato.

![Tiri totali e da 3 punti per partita](/2025-08-20/tiri_totali_e_3punti_per_partita.png)

Osservando il *secondo grafico* si possono fare un paio di considerazioni:

- L’andamento dei **tiri totali** nel tempo risulta complessivamente stabile e le variazioni, di entità limitata, lo rendono assimilabile a una retta orizzontale. Questo indica una sostanziale costanza nel volume complessivo di conclusioni tentate.  
- L’andamento dei **tiri da tre punti** mostra invece una crescita pressoché lineare ed evidenzia un incremento costante e prolungato nel tempo.

Questo evidenzia che il vero cambiamento non riguarda tanto il **volume complessivo di tiri** presi mediamente da una squadra a partita, quanto la **distribuzione delle conclusioni**, con un progressivo aumento dei **tiri da tre punti** rispetto ai tiri da due punti.

### L’incidenza sul totale
![Incidenza del tiro da 3 punti sul totale](/2025-08-20/incidenza_tiro_3punti_sul_totale.png)

Il terzo e ultimo grafico mette in evidenza che, mediamente in una partita, circa il **42%** dei tiri di una squadra NBA proviene da oltre l’arco. Se questa tendenza dovesse mantenersi, senza modifiche regolamentari o fattori di saturazione, è realistico ipotizzare che entro pochi anni si possa raggiungere la soglia psicologica del 50%.

### Non chiamatela evoluzione del gioco
Il basket NBA è profondamente _cambiato_.
Regolamenti, interpretazioni arbitrali e molteplici fattori extra-gioco hanno plasmato ~uno sport~ un prodotto totalmente nuovo.

Nell’ultima stagione, l’**11 aprile 2025**, gli Utah Jazz hanno tentato **63** tiri da tre punti contro gli Oklahoma City Thunder. I Jazz chiuderanno la stagione all’ultimo posto, mentre i Thunder vinceranno il titolo NBA; quei **63 tentativi da tre punti** rappresentano al momento un record per una partita NBA senza tempi supplementari.

Il **3 giugno 1998**, a Salt Lake City, gli Utah Jazz vinsero gara 1 delle NBA Finals contro i Chicago Bulls di Michael Jordan... in tutta la partita non segnarono nemmeno un canestro da tre punti.

### One more thing
Nel primo grafico emerge una curiosa anomalia a metà anni ’90: nelle stagioni **1994/95**, **1995/96** e **1996/97**, la NBA accorciò di circa mezzo metro la linea da tre punti, con l’intento di favorire gli attacchi. Il risultato fu un repentino aumento dei tiri da tre punti, che creò un picco temporaneo, normalizzatosi solo quando la lega riportò la linea alla distanza originale. Ironia della sorte, nonostante l’obiettivo fosse favorire l’attacco, l’avvicinamento della linea ridusse gli spazi offensivi, finendo per agevolare in realtà la difesa.

---

### Materiali allegati

- [Notebook Jupyter usato per l’analisi](https://github.com/giuluk/giuluk.github.io/tree/77b39dac2aac6b498414dd3d636a585d1b8963af/static/2025-08-20/analisi.ipynb)  
- [File CSV con i dati](https://github.com/giuluk/giuluk.github.io/tree/77b39dac2aac6b498414dd3d636a585d1b8963af/static/2025-08-20/nba.csv)  [^1]

[^1]: I dati utilizzati provengono da [Basketball Reference](https://www.basketball-reference.com/).

