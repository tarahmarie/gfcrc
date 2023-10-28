# Come riconoscere un ricercatore di cybersicurezza informatica in buona fede da un criminale informatico

## Un ricercatore di sicurezza è una persona che:

1. Rinviene una vulnerabilità nel corso di altre attività di ricerca e sviluppo non relative alla sicurezza, come ad esempio un programmatore che trova un bug nel codice open-source; questa potrebbe essere la sola vulnerabilità che abbia mai trovato.

2. Conduce ricerche generali sulla sicurezza informatica, come le minacce emergenti e l'attività degli hacker, ma il cui compito principale non è trovare vulnerabilità.

3. Va a caccia di vulnerabilità come obiettivo principale o primario del proprio lavoro.

## Il comportamento in buona fede comprende:

1. Riferire le proprie scoperte al proprietario della vulnerabilità o al pubblico.

1. Va oltre la semplice scoperta, fornendo anche informazioni per riprodurre e mitigare la vulnerabilità.

1. Non danneggia intenzionalmente la proprietà nel tentativo di scoprire o convalidare le vulnerabilità (visualizzare, copiare o diffondere i dati non è un danno).

   a. La divulgazione pubblica di dati che hanno una ragionevole probabilità di danneggiare l'interesse pubblico e che erano destinati a essere protetti prima della scoperta della vulnerabilità non è considerata un comportamento in buona fede (anche se vengono seguiti tutti gli altri princìpi del presente documento).

1. Progetta e realizza la ricerca delle vulnerabilità con modalità atte a scongiurare, nel miglior modo possibile, qualsiasi danno intenzionale ad individui o al pubblico.

1. Segue le leggi locali al meglio delle proprie capacità e conoscenze, comprese la dichiarazione e il pagamento delle tasse sul reddito alle agenzie fiscali competenti.

1. Se il proprietario di una vulnerabilità non risponde, segue le best practice di attendere perlomeno:

   a. 30 giorni prima di divulgare pubblicamente una vulnerabilità che potrebbe danneggiare la salute umana o la vita nelle infrastrutture critiche.

   b. 60 giorni prima di divulgare pubblicamente una vulnerabilità del software o del firmware.

   c. 180 giorni prima di divulgare pubblicamente una vulnerabilità fisica (ad esempio, una vulnerabilità rinvenuta in una serratura fisica o nel firmware/hardware di un sistema di controllo elettronico degli accessi).

1. In caso di mancata risposta da parte del proprietario della vulnerabilità durante il periodo di attesa, il ricercatore di vulnerabilità in buona fede:

   a. dovrebbe divulgare immediatamente ad un escrow partner se la vulnerabilità è relativa ad un'infrastruttura critica, e la divulgazione dovrebbe avvenire il più vicino possibile alla notifica del proprietario della vulnerabilità.

   b. può rivelare una vulnerabilità IT/OT o fisica ad un escrow partner prima della divulgazione pubblica, come parte della pratica di ricerca sulla sicurezza in buona fede.

1. In caso di risposta che stabilisca una linea di comunicazione per una vulnerabilità, il ricercatore di vulnerabilità in buona fede:

     a. Non divulga la vulnerabilità segnalata prima della scadenza concordata stabilita nelle comunicazioni avvenute con il proprietario della vulnerabilità, finché quest'ultimo continua a interagire con il ricercatore.

1. (Quando si presenta la situazione) Dà priorità alla sicurezza e alla salute degli altri piuttosto che al guadagno finanziario e segnala immediatamente ad un escrow partner se viene rilevata una vulnerabilità ICS/SCADA che sta danneggiando o potrebbe danneggiare attivamente le persone fisicamente.

1. Non nasconde i dettagli di una vulnerabilità per chiedere un pagamento al proprietario della vulnerabilità. Se il proprietario di una vulnerabilità si rifiuta di pagare o non vuole che gli venga rivelata, effettua una delle tre scelte:

   a. divulgare pubblicamente la vulnerabilità senza scopo di lucro,

   b. divulgare la vulnerabilità ad un escrow partner adeguato per ottenere assistenza nella divulgazione senza scopo di lucro,

   c. o divulgare pubblicamente la vulnerabilità senza scopo di lucro, come accettato pubblicamente o privatamente dall'escrow partner.

### Casi in cui la divulgazione della ricerca sulle vulnerabilità in buona fede ha favorito la sicurezza pubblica:

   a. "Il vostro aereo di linea verrà hackerato? Incontrate le persone che stanno facendo in modo che non succeda". Fonte (in lingua inglese): https://www.smithsonianmag.com/air-space-magazine/will-your-airliner-get-hacked-180976752/

   b. "La vulnerabilità BadAlloc colpisce il sistema operativo in tempo reale BlackBerry QNX" Fonte (in lingua inglese): https://www.securitymagazine.com/articles/95888-badalloc-vulnerability-affects-blackberry-qnx-real-time-operating-system

   c. "La piattaforma CISA aiuta le agenzie a scoprire più di 1.000 vulnerabilità informatiche" Fonte (in lingua inglese): https://federalnewsnetwork.com/cybersecurity/2023/08/cisa-platform-helps-agencies-uncover-more-than-1000-cyber-vulnerabilities/ 

### Definizioni e presupposti

* Infrastruttura critica: ha un impatto sull'infrastruttura fisica e digitale su cui la società fa affidamento, ad esempio: acqua e acque reflue, elettricità, petrolio e gas, telecomunicazioni, finanza, sanità, governo, settori che si basano su sistemi di controllo industriale (ICS) e sistemi SCADA, software e applicazioni di terze parti di uso comune o comunque facenti parte della filiera.

* Buona fede: "avere intenzioni oneste o sincere" di rispettare le comunicazioni stabilite con i proprietari delle vulnerabilità e comprendere l'impatto delle proprie azioni sul pubblico cercando di prevenire i danni.

* Escrow partner: un'organizzazione governativa o privata che può mediare tra un ricercatore e un proprietario di vulnerabilità, con la capacità di proteggere l'identità del ricercatore e di bilanciare la necessità di una risposta pubblica alle vulnerabilità delle infrastrutture critiche e ad altre vulnerabilità.

* Proprietario della vulnerabilità: chi possiede il sistema in cui è stata trovata la vulnerabilità. Può essere un ente governativo, un'azienda privata o un'altra organizzazione o persona.

* Giorni prima della divulgazione: il numero di giorni da attendere prima della divulgazione si basa su due elementi: in primo luogo, una media dei tempi pubblicati da organizzazioni come Project Zero di Google, CISA degli Stati Uniti ed i meccanismi di segnalazione delle vulnerabilità di aziende come Splunk, Symantec, Master Lock e altre ancora; in secondo luogo, quello che sarebbe comunemente considerato un tempo di attesa ragionevole tra i ricercatori di cybersicurezza informatica ed i proprietari delle vulnerabilità (perlomeno secondo la loro documentazione).
