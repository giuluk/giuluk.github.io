---
layout: post
title:  "Congettura di Collatz"
date: '2021-02-15 20:20:00 +0200'
categories: [matematica]
tags: [collatz, python]
mathjax: true
published: true
---

La [Congettura di Collatz](https://it.wikipedia.org/wiki/Congettura_di_Collatz), enunciata nel 1937 dal matematico tedesco *Lothar Collatz*, è uno dei tanti problemi matematici ancora senza una soluzione.

Supponiamo di scegliere un intero positivo $n$ e procediamo seguendo i passi del seguente algoritmo:

1. se $n=1$ l’algoritmo termina;
2. se $n$ è un numero **pari** allora lo dividiamo per $2$;
3. se $n$ è un numero **dispari** allora lo moltiplichiamo per $3$ e addizioniamo $1$.

L’algoritmo va eseguito prendendo, come valore di input, l’output del risultato precedente e poi si procede fino a quando $n=1$.

La congettura sostiene che, dopo un numero finito di cicli, l'algoritmo sarà sempre destinato ad arrestarsi, indipendentemente dalla scelta di $n$.

**Esempio**

Scelto $n=13$ essendo dispari moltiplichiamo per $3$ e aggiungiamo $1$, così facendo otteniamo $40$ che, essendo pari, possiamo dividere per $2$. A questo punto il nuovo valore di $n$ è $20$ e si prosegue usando le regole dell’algoritmo fino a quando $n=1$.

La sequenza completa per il numero $13$ è:

$13 \rightarrow 40 \rightarrow 20 \rightarrow 10 \rightarrow 5 \rightarrow 16 \rightarrow 8 \rightarrow 4 \rightarrow 2 \rightarrow 1$

**Codice**

Quello che segue è il codice per generare una successione, come nell'esempio, usando l'algoritmo della congettura di Collatz. Non ho esperienza di programmazione in Python quindi è stato scritto avendo come riferimento la semplicità ma trascurando efficienza, eleganza e controllo delle eccezioni.

~~~ python
def collatz(n):
    print(n)
    while n > 1:
        if n%2 != 0:
            n = 3*n + 1
        else:
            n = n // 2
        print(n)
~~~

L’algoritmo è stato verificato per [valori enormi](http://www.ericr.nl/wondrous/) di $n$ ma la congettura, ad oggi, resta ancora senza una dimostrazione.
