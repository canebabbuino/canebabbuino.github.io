---
layout: post
title: "Pensando a un blog"
category: babbuino
author: Matteo Del Prete
---

Vorrei partire da quella sensazione di smarrimento e di disarmo che mi blocca tutte le volte che affronto l'inizio di un lungo progetto. Cado facilmente nella tentazione di guardarmi intorno e paragonarmi tacitamente a ciò che vedo, selezionando soprattutto le realtà che mi più mi corrispondono e a cui più mi piacerebbe somigliare. Ci sono innumerevoli belle immagini nel mondo e mi è facile considerarle un deterrente e una riprova della difficoltà, piuttosto che delle fonti di ispirazione ad impegnarmi di più nel presente.

Ad esempio un bel blog, semplice e pulito e pieno di cose interessanti da leggere, come [questo](http://bactra.org/); oppure canali YouTube come [questo](https://www.youtube.com/c/3blue1brown) e [questo](https://www.youtube.com/c/kurzgesagt), dove oltre ogni altra cosa si coltivano la cura e la passione nel far capire le cose. Mi è forse impossibile immaginare di essere al punto di partenza di una storia simile. Che faccio, come inizio? Ho dubbi e innumerevoli scelte da compiere, le mani e gli occhi si fanno pesanti, scrivo e poi cancello. Che fatica!

## Pensando a un blog
Mi piace scrivere, quando mi riesce. A volte mi dicono che sono bravo, io mi stringo un po' nelle spalle. Il fatto è che quando ho qualcosa da dire e la scrivo, sento che poi funzionerà, in qualche modo. Da questo punto di vista, la scelta di creare un blog è forse la più facile da compiere. Non è un'esperienza del tutto nuova, per me: questa è forse la quarta o quinta volta che ci provo. Alcune provando a costruire tutto da zero, una modesta riga di linguaggio HTML alla volta; altre provando a far mie delle strutture già confezionate, come Blogger, Tumblr e Wordpress. Con un po' di impegno potrei riuscire a raccontarvi il perché di tanti tentativi e fallimenti, ma mi sento più onesto e meno lagnoso a venire direttamente al presente. Ora sono qui, dopotutto - anche se non c'è garanzia sulla durata di questo tentativo!

Nel presente c'è [Jekyll](https://jekyllrb.com). È un ottimo strumento se si ha una minima conoscenza di programmazione, ma non si parlano bene i vari linguaggi e non si ha la pazienza che serve per gestire centinaia di nomi di variabili e parentesi graffe. Nella costruzione di un sito, generalmente, si utilizza l'HTML per comunicare al browser cosa va visualizzato. Ad esempio, scrivendo nel file:  

{% highlight html %}
<p>Questa riga
    non va mica a capo,</p>
{% endhighlight %}
{% highlight html %}
<p>questa</br>
    invece sì!</p>
{% endhighlight %}

si ottiene nel browser:
> Questa riga non va mica a capo,  

>questa  
invece sì!

Tutto quello che vediamo in una pagina internet ha un codice dietro, anche banalmente le parole e le immagini devono essere inserite tramite un codice che spieghi al browser cosa visualizzare. Addirittura andare a capo richiede un `</br>`! Naturalmente c'è molto altro: una delle cose più delicate e potenzialmente fastidiose da gestire è la disposizione dei vari elementi, la geometria della pagina. Se mal gestito, anche solo uno spostamento di qualche centimetro di un piccolo logo genera uno sconvolgimento di tutta la struttura, rovinando il lavoro di giorni. E torna in gioco la già citata pazienza del programmatore, una dote che non riesco neanche ad immaginare di avere, e che ammiro.

Ma torniamo a Jekyll: con lui, i problemi sono (quasi) praticamente risolti. Infatti Jekyll è un costruttore di siti e già di suo propone all'utente di procedere con ordine, in base a delle cartelle ben strutturate. C'è la cartella con i post del blog, la cartella con i colori da utilizzare, la cartella con le immagini da includere, eccetera. Se non si vuole partire da zero, viene fornito un modello di blog semplice e pulito come questo, e riempirlo di contenuti è facilissimo sin da subito: basta inserire dei nuovi file di testo nella cartella dei post, e Jekyll automaticamente capisce che deve prendere quel testo lì, tradurlo in linguaggio HTML e infilarlo al posto giusto del sito! Voglio andare a capo? Premo Invio! Il mio sito non lo capirebbe, ma Jekyll lo traduce in `</br>`, ed ecco fatto.

La tentazione di dire che questa "è la volta buona" c'è, ma in verità la motivazione non è tecnica. Non è la comodità nel costruire il blog a renderlo concreto.  
È il pensiero.

### Fare didattica
Si sarà già capito che mi piace spiegare le cose. Qualche settimana fa, parlando con [Etienne Jacob](https://twitter.com/etiennejcb), ho concluso che:
> Per me, i piaceri più belli dell'insegnamento sono sempre stati quei brevi momenti di realizzazione, quegli "hey, adesso ho capito!", che spesso capitano in entrambe le direzioni tra insegnante e studente. Non so dire bene cosa ci sia sotto, ma è come se due menti si incontrassero, è una cosa che mi fa sentire connesso.  
A volte non sembra neanche portare a qualcosa di più, a degli ottenimenti pratici e duraturi, ma questa è un'altra storia, in quanto lì entrano in gioco fattori esterni che spesso sono fuori dal nostro controllo diretto: la voglia di studiare, le priorità nella vita, eccetera. Poi se tutte queste cose convergono e rendono possibile una realizzazione di lunga durata, si arriva a una sorta di obiettivo ideale per ciascun insegnante.

Sono consapevole che nella pratica dell'insegnamento ci sia molto altro. Ad esempio la progettualità necessaria per arrivare a determinati obiettivi futuri. Se però è vero che il passaggio fondamentale per poter trasmettere qualcosa è quello di stringere un rapporto, allora va anche detto che quel rapporto si sviluppa gradualmente, un passo alla volta, realizzazione dopo realizzazione. Quindi l'immediatezza del momento "wow" non è affatto secondaria, nemmeno quando si parla di programmare una serie di lezioni, di assegnare esercizi per casa o elaborare un libro di testo che supporterà lo studente per mesi e mesi.

Se questo discorso fila, allora penso di aver trovato il pensiero vincente, ed è quello di fidarsi di questo tipo di rapporto, nei panni dell'insegnate-studente. Una creatura che compie un lungo cammino e che si spaventa al pensiero di doverlo percorrere tutto; ma accompagnata passo passo può godersi ogni singolo momento di successo, ogni volta che si cambia prospettiva, si scollina dopo una faticosa salita e si ammira un nuovo paesaggio di fronte o dietro di sé. Pensandola in questo modo, iniziare questa nuova avventura forse non incute più alcun timore.

### Il mio amico Davide
Qualche settimana fa ho avuto il piacere di collaborare con il mio amico Davide Guerra alla scrittura di un podcast per il progetto [Maturadio](https://www.raiplayradio.it/programmi/maturadio/). Una bella sfida, quella di elaborare un testo scritto, poi letto e registrato da un attore per niente esperto di fisica, di un podcast che spieghi l'evoluzione delle idee scientifiche sulla luce nel corso della storia. Abbiamo scelto insieme questo argomento, anche se è più corretto dire che si è fatto strada nelle nostre menti mentre cercavamo il tassello finale nel puzzle dei 50 argomenti di matematica e fisica del progetto. Attualmente il podcast non si può ancora ascoltare, noi abbiamo fatto la nostra parte di scrittura ma non è stato ancora registrato. L'abbiamo definito la nostra bambina, che per noi è nata ma ancora non ha effettivamente visto la luce.

Scrivere insieme è stato bello e un salto in lungo oltre l'ostacolo del "come fare". Avevo già scritto due testi per lo stesso progetto: da solo, ho combattuto con l'ispirazione, aspettandola; ho ricercato una giusta struttura e delle giuste parole, provando a rispondere alle molte domande che mi si paravano davanti. Chi poi ascolterà, vedrà ciò che io vedo adesso? Posso trasmettere un'immagine tanto personale tramite la voce di qualcun'altro? Si sentirà il mio respiro a questo ritmo calmo e profondo, in riva al mare della conoscenza?
Lavorare da solo e provare a rispondere a queste domande mi ha dato il tempo di cercare un senso della divulgazione. È sempre far capire qualcosa, ma con un rapporto del tutto diverso da quello insegnante-studente di sopra. Richiede di far proprie certe idee e certe osservazioni, in qualche modo inspirarle per poi riportarle fuori con altre parole e altre immagini. A volte ci vuole tanto coraggio, qualcuno potrebbe dire sconsideratezza, per entrare ed uscire correndo dal rigoroso palazzo della scienza, portando dentro e fuori le notizie di ciò che gli esseri umani hanno scoperto sulla realtà.

Scrivere insieme è stato completamente diverso, perché si viaggiava rapidamente e come in barca, tagliando le onde spinti dal vento. Tramite [Google Docs](https://www.google.com/docs/about/) abbiamo lavorato a quattro mani sullo stesso foglio. Ciascuno si occupava di quello che c'era da fare: proporre una scaletta, inventare una metafora, ripulire la sintassi e l'ortografia e via dicendo. I nostri cursori colorati si inseguivano nella pagina e non ci lasciavano il tempo necessario a quelle domande pesate di cui sopra: così è nata una leggerezza che penso potrete sentire nel prodotto finale. E anche se, per qualsiasi motivo, questo non potrà succedere, per me la bambina è nata: con il blog getto ora questo seme dell'albero le cui foglie ci daranno ombra e fresco per incontrarci e scrivere di nuovo insieme.  
Ciao ciccio, buon viaggio!
