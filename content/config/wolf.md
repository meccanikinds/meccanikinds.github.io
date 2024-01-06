---
title: "Wolf:ET"
date: 2018-01-28T21:48:10+01:00
anchor: "wolf"
weight: 20
---

### Download e installazione

Usate Windows e non rompete le scatole.
Il gioco si scarica da [qui](http://wolffiles.de/filebase/ET/Full%20Version/WolfET_2_60b_custom.zip).

Se usate MacOSX o Linux-antani, non perdete le speranze e provate con [questi](https://www.etlegacy.com).\
Non va? scrivete una mail al Papa.

Tutti i pacchetti e le mappe custom si scaricano automagicamente da sole. Pazientate un attimo.

### HunkMegs

Controllare se c'è un file di nome `autoexec.cfg` in `etmain` all'interno della cartella di installazione del gioco, se non c'è va creato. Raccomandiamo di controllare che il file creato sia effettivamente un file di solo testo, e sia stato nominato `autoexec.cfg` modificando l’estensione (per esempio se il file alla fine è `autoexec.cfg.txt` va malissimo).

Inserire questa riga: 

        set com_hunkmegs "128"

salvare il file. Profit.


---


{{< block warn >}}
La configurazione di seguito ha circa un decennio, è qui per motivi storiografici e perché l'ho scritta io: praticamente tutte le informazioni sono sbagliate o incomplete.\
**NON FATE GLI SCEMI E NON PROVATE A FARE NULLA DI QUELLO CHE C'È SCRITTO QUI**
{{< /block >}}

### Download e installazione

>*Da "Non va una sega" a "Funziona tutto"*\
>-*Zurgo*-


Non serve molto oltre al gioco base (Wolfenstein: Enemy Territory, o duri!), il mod con cui giochiamo (ETpub) e il consigliatissimo programma di comunicazione tattico/militare(!?) (TeamSpeak).

Per installare Enemy Territory:
+ Se usi Windows ti serve avere installata la versione `2.60b.` Puoi scaricare direttamente la versione patchata 2.60b dai cugini crucchi. Se poi proprio ti vuoi rompere le palle, scaricati le versioni precedenti e aggiornale con le patch fino alla `2.60b`.
+ Se usi Linux ti serve avere installata la versione `2.60b`. Puoi scaricare direttamente il gioco da PlayDeb.
+ Se usi MacOSX ti serve avere installata la versione `2.60d` che trovi comodamente dagli altri cugini crucchi.


ETpub client versione 20100628, Il mod che usiamo attualmente, viene automaticamente scaricato dal gioco quando ti connetti al nostro server. Nel caso avessi problemi nel download innanzitutto controlla (ii) 3. ammodino. Se poi insisti proprio nel voler fare alla vecchia maniera, ETPub si scarica da qui.

TeamSpeak versione 3 si scarica da [qui](https://www.teamspeak.com). Ti consigliamo però di installarlo solo dopo che l'installazione e la configurazione di Enemy Territory sono state completate, e ti sei assicurato che tutto funzioni bene.

<a name="rem"></a>

 ### Configurazione 

Cerca un file di nome autoexec.cfg all'interno della cartella etmain, e se non lo vedi crealo. Raccomando agli utenti Windows di controllare se il file creato è effettivamente un file di solo testo, e sia stato nominato autoexec.cfg modificando l’estensione (per esempio se il file alla fine è “autoexec.cfg.txt” non va molto bene). 
Poi scrivici questa riga (in un posto qualunque): 

        set com_hunkmegs "128"

salva il file e riavvia wolfet. Questo file ti consente di non dover mai avere a che fare con alcuni noiosi problemi di gestione della memoria, che potrebbero causare il crash di alcune mappe.
N.B. non è opzionale: fallo subito!

(nota doverosa: completando questi passaggi, hai appena creato il tuo primo script di configurazione per ET (in questo caso del rendering); è importante sapere che di tutto si può fare con gli script, per esempio configurarsi tasti di funzione, azioni programmate, etc. (chiedete a Miller...).
            
Per far funzionare le XPsave (e consentirti l’accesso al server) devi assicurarti di avere un file di nome etkey dentro la tua cartella /etmain. Se non trovi nessun file che si chiama etkey dentro /etmain, scarica una nuova etkey da qui e metticela.


Perché il redirect per scaricare mappe e affini funzioni (e vada irragionevolmente veloce), bisogna controllare due cose in "options>game":

        Get missing files from server: Yes
        Allow HTTP/FTP Downloads: Yes

A questo punto assicurati che Enemy Territory funzioni bene (rendering, suono) prima di iniziare a installare e configurare TeamSpeak.
In caso affermativo, installa Teamspeak, lancialo, vai su "settings>options>playback" e premi "play test sound" per regolare il volume in ricezione. Poi spostati su "settings>options>capture" e premi "test voice" per regolare il volume del microfono.
Se usi altoparlanti e microfono, ti consigliamo di abilitare il "Push-to-Talk" per evitare spiacevoli feedback (e conseguenti insulti dei tuoi compagni di canale). Se invece usi cuffie e microfono, ablilita pure il "Voice Activation Detection" (e a quel punto regola la soglia in modo che si sentano i sussurri della thailandese che ti fa i massaggi mentre giochi).

Il server teamspeak usato di solito in partita è tsviewer.com porta 9987, puoi salvarlo nei bookmarks di teamspeak. Controlla comunque nella tabella della giornata eventuali modifiche e informazioni sui canali.


### Materiale Utile

Questo materiale non è necessario per il corretto funzionamento del gioco, ma serve per non fare sempre la fine del tordo sulla Futa. Abbiamo, fra le varie cose:

Un ottimo manuale di gioco, da consultare a perdita di tempo (ma in realtà utilissimo).
Un sito di Strategie e tattiche, da leggere per i più ambiziosi.
Mappe, skin, aggeggi ed intrallazzi.
Mod a caterva: ETpub, ETpro, Jaymod, NoQuarter. per i malati, i codici sorgente di ET.

Tutti i files necessari e aggiuntivi per giocare sui nostri server sono disponibili tramite redirect HTTP al momento della connessione (vedi (ii) 2.) 
Nella sezione Equipaggiamento della mailinglist, il vecchio archivio non più aggiornato e in eliminazione


### Le Istruzioni Mancanti 3.0

sono girate per mail: un po' tecniche forse, ma le riportiamo. se avete problemi non banali, provate a leggerle. 

Le parti in corsivo sono istruzioni per le vecchie impostazioni: contengono comunque informazioni utili, per esempio come risolvere alcuni problemi più sottili, i server in uso, i file .pk3 in uso... 
Come istruzioni generali però, sono state rese obsolete da aggiornamenti. Le parti in grassetto sono appunto questi aggiornamenti.

---

1.  1. per giocare serve `WolfET 2.60b` per windows, o `2.60d` per macosx e linux, una cosa del genere, l'unica è provare (il server gira con la versione 2.60b, i giocatori macosx usano tranquillamente la versione `2.60d` apparte JollyKiller che non gli riesce).

    2. Per risolvere subito il messaggio di errore che appare sempre al benedetto fueldump: aprite la console (vedi 4.) e date come comando:
                
                set com_hunkMegs 128
       
       riavviare, riconnettersi.
{{< block info >}} 
leggere [qui](#rem)!
{{< /block >}}




2.  1. Suoni del vecchio wolfenstein: per averli, mettete nella cartella `etmain`, dentro la cartella di installazione di WolfensteiET, il pacchetto `zzz_suoni.pk3` lo potete scaricare al seguente indirizzo: http://poisson.phc.unipi.it/~gentili/WolfensteinET/
    2. se volete, ci sono le divise carine per fare i fighetti, e le bandiere delle divisioni giuste e altre segate. alcuni combattenti hanno lamentato problemi a distinguere i nemici (anzi gli amici, visto che nel dubbio si spara). provate, o fregatevene. solita destinazione, solito indirizzo per scaricare, il file questa volta si chiama `zzz_skins2.pk3`.
    3. nel caso che le divise nuove diano noia, le modifiche sono solo provvisorie e possono essere annullate in qualsiasi momento: basta togliere il file `zzz_skins2.pk3` dalla cartella `etmain`, dentro la cartella di installazione di WolfensteiET, riavviare e riconnettersi. se danno fastidio i suoni, la faccenda è identica.
{{< block info>}} 
Adesso c'è un redirect automatico che fa scaricare i pacchetti mancanti a velocità ragguardevole. In caso di problemi, o per quanto riguarda 2.3, basta andare nel menu principale del gioco, e poi `options>game>"Get missing file from servers: no"`. in questo modo ignora i download e passa avanti.
Questo metodo funziona ovviamente solo con i `.pk3` non indispensabili al gioco.
{{< /block >}}


---

**(29/10/2010) i file presenti e utilizzati dal server sono i seguenti:**


|nome:|funzione:|
|:----------|:----------:|
|zzz_suoni.pk3|*suoni delle armi di RTCW™*|
|zzz_skins2.pk3|*skins delle divisioni UK/NAZI in Africa*|
|Spring.pk3|*textures “primaverili” per fueldump*|
|z_SfsSoundPack37.pk3|*suoni fastidiosi tipo “Amerika!”*|
|etpubc-20100628.pk3|*client etpub ultima versione (consigliato)*|
|obgf_camp.pk3|*file della della nostra campagna*|


i file veramente indispensabili sono invece le mappe non-standard, ma solo quando le giochiamo. in quel caso è più semplice accendere il redirect (leggere [qui](#2em)!) e scaricarle automaticamente.

+ ~~con skype facciamo il teamspeak, quindi se ve lo procurate all'inizio ci facciamo le chiamate giuste per insultarci e domandarsi: "Dove [...] è finito quel maledetto ingegnere che non sono riuscito a inchiodare?".~~
usiamo www.teamspeak.com. Di volta in volta nella pagina di iscrizione potrete controllare l'indirizzo del server teamspeak usato per la serata e la password del canale.

+ il server, quando è acceso è `131.114.10.38` (fourier.phc.unipi.it). se non riuscite a connettervi dalla console di et, `~` o il tasto sotto `esc` oppure `>` per aprirla da dentro il gioco -non è semplice trovarlo, vi ricorda qualcosa?-, poi come comando:

        /connect 131.114.10.38

   Non va? Controllate la vostra rete: se va mandate una mail a Zurgo.
   Per problemi di risorse, manutenzione e materiale umano, l'indirizzo dei server cambia a caso. Controllate la pagina della partita della settimana, oppure mandate una mail a Zurgo se il server è giù o non lo trovate. I server più probabili sono: `131.114.10.38` (fourier), `131.114.10.33` (daphne)

+ il server ha le xpsave a 7 giorni (leggere (ii) 2.), oltre ad un paio di modifiche che sono state comunicate, compresa la possibilità di fingersi morti, e altre bazzecole sulle armi e cavolate... grazie a etpub. a chiunque la meni per la hud, consiglio di dare un'occhiata a `mod>load>etpub` poi `etpub>options`.\
C'è la trasparenza per i fireteam, e di tutto... addirittura il config Drag&Drop!

---

© miller/zurgo 2007-2010
