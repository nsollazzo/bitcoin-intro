# Intro

I principi che segue questa guida sono:
- Iniziare semplicemente e poi migliorare è meglio che non iniziare affatto
- È più coinvolgente utilizzare gli strumenti prima di leggere una spiegazione dettagliata
- Mantenete sempre il pieno controllo dei vostri bitcoin (usate strumenti non-custodial)
- Rimaneti concentrato ed evita le truffe 

-----

| Step     | Descrizione                                    | Progressi |
| -------- | ---------------------------------------------- |  -------- |
| **LV. 0**| **Studioso**                                   |           |
| 0.1      | Che cos'è bitcoin?                             |           |
| 0.2      | Perché usare bitcoin?                          |           |
| **LV. 1**| **Apprendista**                                |           |
| 1.1      | Ottenere un Wallet                             |           |
| 1.2      | Comprare dei bitcoin                           |           |
| **LV. 2**| **Mago**                                       |           |
| 2.1      | Un migliore Backup                             |           |
| 2.2      | Comprare in modo privato                       |           |
| 2.3      | Bitcoin Privacy                                |           |
| **LV. 3**| **Stregone [ITA-ENG]**                                   |           |
| 3.1      | Come funziona bitcoin?                         |           |
| 3.2      | Nodo bitcoin                                   |           |
| 3.3      | MicroPagamenti Bitcoin: Lightning Network      |           |
| 3.4      | Eventi ed incontri                             |           |
| **LV. 4**| **Saggio [ENG]**                                     |           |
| 4.1      | Ulteriori approfondimenti                      |           |

-----

# LV. 0 - Studioso
> Conosco poco o niente di Bitcoin e vorrei saperne di più

## 0.1 - Che cos'è bitcoin?
> fonte: <a href="https://sollazzo.one/2019-01-07-alla-scoperta-di-bitcoin/">Alla scoperta di Bitcoin con Ferdinando Ametrano</a>

**bitcoin** è una **moneta digitale e decentralizzata** – cioè senza nessun governo o organizzazione alle sue spalle – non si basa su una terza parte fiduciaria, permette transazioni tra due parti (**peer-to-peer**) in maniera istantanea e crittograficamente sicura.

Bitcoin rappresenta potenzialmente una **efficiente banca low-cost per tutti ovunque essi siano**, a patto di possedere un dispositivo elettronico connesso alla rete internet, garantendo allo stesso tempo un alto livello di privacy.

## 0.2 - Perché usare bitcoin?
> *Obbiettivo: Imparare perché bitcoin è utile*

Se avete appena iniziato a lavorare con Bitcoin, potreste chiedervi quali sono i benefici. Ecco le ragioni più popolari per cui la gente sceglie di usare i bitcoin:

1. Read '<a href="https://medium.com/@wiz/why-bitcoin-359ada12629e" target="_blank">Why Bitcoin</a>' by [Wiz](https://twitter.com/wiz)
2. Read '<a href="https://medium.com/@vijayboyapati/the-bullish-case-for-bitcoin-6ecc8bdecc1" target="_blank">The Bullish Case for Bitcoin</a>' by [Vijay Boyapati](https://twitter.com/real_vijay)
3. Watch '<a href="https://youtu.be/q0XxsabgJEI?t=31" target="_blank">Why Bitcoin Matters</a>' by [Aleks Svetski](https://twitter.com/AleksSvetski)

-----

# LV. 1 - Apprendista
> Sono uno [studioso](#lv-0---studioso) del mondo di bitcoin ed ora vorrei iniziare ad usarlo

## 1.1 - Ottenere un Wallet
> **OBIETTIVO**: Ottenere un portafoglio dove tenere i Bitcoin ed imparare ad utilizzarlo.

> **ATTENZIONE**:
> La fonte dei contenuti e delle immagini di questa sezione è la <a href="https://docs.blockstream.com/green/getting-started/getting-started-index.html" target="_blank">documentazione ufficiale</a> di <a href="https://blockstream.com/green/" target="_blank">Blockstream Green wallet</a>

Il portafoglio che andremo ad utilizzare si chiama <a href="https://blockstream.com/green/" target="_blank">Blockstream Green wallet</a> ed è possibile scaricarlo sia per <a href="https://blockstream.green/android" target="_blank">Android</a> che per <a href="https://blockstream.green/ios" target="_blank">IOS</a>.

Dopo aver installato l'app, avrete la possibilità di effettuare il login con un mnemonico esistente, oppure di creare un nuovo portafoglio. Per iniziare, cliccate su `Crea nuovo portafoglio`.

<p align="center">
  <img src="https://docs.blockstream.com/_images/landing.png" width="250" />
</p>

A questo punto, l'app genererà un mnemonico di 24 parole per funzionare come metodo di login di backup per il vostro portafoglio.

<p align="center">
  <img src="https://docs.blockstream.com/_images/menmonic-warning.png" width="250" />
</p>

> **ATTENZIONE**:
> Il tuo mnemonico è l'informazione più importante associata al tuo portafoglio.
> Devi scriverlo in un posto sicuro e segreto - è il tuo backup.

Per garantire una registrazione sicura del vostro mnemonico, vi verrà richiesto di reinserire diverse parole nell'ordine corretto.

<p align="center">
  <img src="https://docs.blockstream.com/_images/mnemonic-quiz.png" width="250" />
</p>

Per ricevere Bitcoin, tutto quello che dovete fare è fornire un indirizzo di ricezione al mittente.

<p align="center">
  <img src="https://docs.blockstream.com/_images/receive.png" width="250" />
</p>

<details>
  <summary><i>Nota sugli indirizzi bitcoin</i></summary>
<br>
Un indirizzo di ricezione Bitcoin è una stringa di numeri e lettere. È possibile creare un indirizzo di ricezione selezionando "Receive" dalla schermata principale. Il vostro portafoglio genererà un nuovo indirizzo di ricezione ogni volta che lo richiederete. Anche se è possibile riutilizzare i vecchi indirizzi, è vivamente sconsigliato perché riduce la tua privacy.
  <br>
  <br>
Una volta che potrai vedere qual è il tuo nuovo indirizzo, dovrai comunicarlo al mittente. Se hai bisogno di comunicarlo a distanza, un messaggio di testo o un'e-mail è un modo efficace per farlo.
  <br>
  <br>
Se sei fisicamente accanto alla persona che ti invierà Bitcoin, un'altra opzione è quella di utilizzare il codice QR, che il mittente può scansionare per ottenere l'indirizzo di ricezione. Questo è davvero conveniente se il mittente utilizza un Wallet mobile.
  <br>
  <br>
Una volta che qualcuno ha inviato una transazione al tuo Blockstream Green wallet, dovrebbe apparire nella tua pagina della lista delle transazioni. All'inizio, sarà etichettato come "non confermato". A questo punto, non si dovrebbe considerare che i bitcoin siano stati ricevute, perché la transazione potrebbe comunque essere sovrascritta o annullata. La transazione accumulerà nel tempo "conferme" man mano che verranno estratti nuovi blocchi nella rete Bitcoin. Una volta che la transazione raggiunge le 6 conferme, il vostro portafoglio la elencherà come "confermata" e potrete considerare le monete ricevute.
  <br>
  <br>
</details> 

## 1.2 - Comprare dei bitcoin
> **OBIETTIVO**: Comprare una piccola quantità di bitcoin.

> **ATTENZIONE**:
> Per iniziare si consiglia di comprare solo una piccola quantità di bitcoin.
> Il metodo che tra poco verrà mostrato ti permetterà di comprare bitcoin velocemente ma ridurrà la tua privacy.
> Per comprare bitcoin in modo privato verranno inlustrati metodi alternativi nella [sezione 2.2](#22---comprare-in-modo-privato).

Il metodo migliore per comprare bitcoin nell'Unione Europea è tramite <a href="https://getbittr.com/" target="_blank">Bittr</a>: Bittr ha delle fee dello **1.5%** ed è possibile leggere delle recensioni del servizio offerto, in inglese, su <a href="https://www.trustpilot.com/review/getbittr.com" target="_blank">Trustpilot</a>.

Per comprare su Bittr:
1.	Vai su <a href="https://getbittr.com/save-bitcoin" target="_blank">Bittr</a>.
2.	Immetti la tua email ed il tuo numero di telefono.
3.	Incolla il tuo indirizzo bitcoin (ottenuto nella [sezione 1.1](#11---ottenere-un-wallet)).
4.  Copia la  reference ed invia minimo 25€ dal tuo conto corrente bancario al conto corrente mostrato.
5.	Aspetta che i tuoi bitcoin compaiano in Green Wallet (< 24 hrs). 

Confratulazioni, ora possiedi ufficialmente dei bitcoin!
Fintanto che terrai quelle 24 parole al sicuro, nessuno potrà rubarti i tuoi bitcoin dal Wallet che hai creato poiché senza quelle 24 parole nessuno potrà accedere ai tuoi bitcoin.

-----

# LV. 2 - Mago 
> Sono un [apprendista](#lv-1---apprendista) del mondo di bitcoin ed ora vorrei sapere come migliorare la mia privacy e salvaguardarmi meglio



## 2.1 - Un migliore Backup
> **OBIETTIVO**: Migliorare il tuo sistema di backup in modo da essere pronto quando il valore di bitcoin aumenterà o deciderai di comprarne di più.

1. Read the <a href="https://github.com/6102bitcoin/FAQ/blob/master/seed.md" target="_blank">Seed FAQ</a>
2. Pick a setup (e.g. Two full backups, one on paper one on stamped metal)
3. Implement your selected setup

## 2.2 - Comprare in modo privato
Anche se i metodi spiegati nella [sezione 1.2](#12---comprare-dei-bitcoin) sono semplici e facili per comprare i tuoi primi bitcoin, vale la pena considerare metodi che garantiscono una maggiore privacy per i futuri acquisti.

### Overview table

| Metodo di Pagamento | Privacy      | Interfaccia | Email/Telefono    | Nome/Indirizzo    | Esempi          |
| ---                 | ---          | ---         | ---               | ---               | ---             |
| Contanti            | Privato      | Di persona  | **Non richiesto** | **Non richiesto** | BISQ / Vouchers |
| Bonifico            | Semi-privato | Sito Web    | Richiesto         | **Non richiesto** | Bittr           |
| Carta di debito     | Non-privato  | Sito Web    | Richiesto         | Richiesto         | Coinbase        |

Per lo scopo di questa sezione ci concentreremo su due metodo: BISQ e Vouchers

#### BISQ
0. <a href="https://bisq.network/downloads/Download" target="_blank">Scarica</a> e installa BISQ
1. Imposta Euro
2. Cerca venditori vicino a te (seleziona `BUY BTC` in alto a sinistra)
3. Compra da venditori locali (selezione `CREATE A NEW OFFER TO BUY BTC WITH EUR`)
4. Ritira i tuoi bitcoin sul tuo indirizzo bitcoin ([sezione 1.1](#11---ottenere-un-wallet))

> **NOTA**: Come indicato al momento dell'installazione di BISQ, l'utente è responsabile dell'utilizzo del software in conformità alle leggi locali.

#### Vouchers
0. Controlla se ci sono commercianti vicino a te che vendono vouchers su <a href="https://azte.co/vendors.html" target="_blank">Azteco</a> o <a href="https://fastbitcoins.com/#locations" target="_blank">FastBitcoins</a>
1. Se ce ne sono, acquista il taglio minimo del buono e segui le istruzioni del buono per riscattare il bitcoin nel tuo portafoglio.
2. Ritira i tuoi bitcoin sul tuo indirizzo bitcoin ([sezione 1.1](#11---ottenere-un-wallet))


## 2.3 - Bitcoin privacy
> **OBIETTIVO**: Capire come e perché usare bitcoin in modo privato.

1. Read how to <a href="https://github.com/6102bitcoin/FAQ/blob/master/hodl-privacy.md" target="_blank">Hodl Privately</a>
2. Learn about <a href="https://github.com/6102bitcoin/CoinJoin-Research/blob/master/CoinJoin_Research/CoinJoin_FAQ.md" target="_blank">CoinJoin</a>

-----

# LV. 3 - Stregone [ITA-ENG]
> Sono un [mago](#lv-2---mago) del mondo bitcoin ed ora vorrei imparare tecnicismi, aiutare e partecipare nella community



## 3.1 - Come funziona bitcoin?
> **OBIETTIVO**: Capire meglio come funziona bitcoin e la sua terminologia.

1. Guarda <a href="https://www.youtube-nocookie.com/embed/bBC-nXj3Ng4" target="_blank">But How does bitcoin actually work</a>
2. Guarda <a href="https://www.youtube-nocookie.com/embed/Lx9zgZCMqXE" target="_blank">How Bitcoin Works Under the Hood</a>


# 3.2 - Nodo Bitcoin
> **OBIETTIVO**: Capire come e perché avere un proprio full-node bitcoin.

> **NOTA**: Avere un nodo bitcoin ti porta beneficio se lo usi per inviare e ricevere transazioni.
> Non usarlo aiuterà a salvare la blockchain su un device in più ma non ti porterà diretti benefici.

1. Guarda <a href="https://www.youtube-nocookie.com/embed/D11R0W2uxeM" target="_blank">Benefits of a Full Node</a>
2. Valutare le tabelle sottostanti per determinare quale opzione ti sembra il più adatto:


|                              | Opzione A | Opzione B  | Opzione C      | Opzione D     |  
| ---                          | ---       | ---        | ---            | ---           |
| Costo                        | Zero      | Zero       | Basso          | **Alto**      |
| Tempo richiesto              | Basso     | **Alto**   | **Medio/alto** | Basso         |
| Difficoltà di configurazione | Basso     | **Alto**   | Medio          | Basso         |
| Tempo di inattività          | **Alto**  | Basso      | Basso          | Basso         |


| Opzione | Utente Ideale             | Fattori positivi     | Fattori Negativi     | 
| ---     | ---                       | ---                  | ---                  |
| A       | Principiante non tecnico  | Gratuito, facile e veloce | Quando il tuo computer sarà spento il nodo non sarà in funzione, quindi, quando vorrete usarlo, dovrete aspettare che si sincronizzi.|
| B       | Appassionato tecnico      | Gratuito             | Richiede un tempo significativo per l'installazione ed è tecnologicamente difficile se non si è mai usato linux prima.|
| C       | Appassionato meno tecnico | Costo ragionevolmente basso e veloce | Richiede un po' di tempo per l'installazione, anche se in genere le guide specificano l'hardware rendendo l'installazione semplice come segue le istruzioni precise. |
| D      | Chiunque possa permettersi comodamente questa opzione | Veloce e facile | Costo elevato rispetto alle alternative |

### Opzione A: Bitcoin-Core sul tuo computer di tutti i giorni
- Download <a href="https://github.com/lightning-power-users/node-launcher/releases" target="_blank">NodeLauncher</a>, un semplice programma che ti aiuterà ad installare bitcoin core.

### Opzione B: Bitcoin-core su un computer sempre acceso
- Video Tutorial: <a href="https://www.youtube.com/watch?v=0Zq_JdExHkE&list=PLmoQ11MXEmagwLs0NtjadkyVwc-CFfr4h" target="_blank">Install Linux</a> e <a href="https://www.youtube.com/watch?v=q0Uen8p4feM&list=PLmoQ11MXEmag9I2ibHnubzJdjDqypujCk" target="_blank">Install Core</a>
- Tutorial Scritto <a href="https://medium.com/hackernoon/a-complete-beginners-guide-to-installing-a-bitcoin-full-node-on-linux-2018-edition-cb8e384479ea" target="_blank">Opzione 1 </a> / <a href="https://github.com/k3tan172/ubuntu-node-box/" target="_blank">Opzione 2</a>

### Opzione C: Costruire un nodo a sé stante
- Appassionati che vogliono controllare il proprio bitcoin full stack: <a href="http://mynodebtc.com/" target="_blank">MyNodeBTC</a>
- Utenti Samourai Wallet: <a href="https://bitcoin-on-raspberry-pi-4.gitbook.io/" target="_blank">DOJO</a>
- Altre Opzioni: <a href="https://stadicus.github.io/RaspiBolt/" target="_blank">RaspiBolt</a> / <a href="https://github.com/rootzoll/raspiblitz" target="_blank">RaspiBlitz</a>

### Opzione D: Comprare un nodo a sé stante già costruito
- Appassionati sensibili al prezzo che vogliono controllare il proprio bitcoin full stack: <a href="http://mynodebtc.com/products/one" target="_blank">MyNodeBTC</a> / <a href="https://raspiblitz.com/" target="_blank">Raspiblitz</a> (<a href="https://shop.fulmo.org/" target="_blank">EU</a> / <a href="https://lightninginabox.co/product/raspiblitz-raspberry-pi-lightning-node/" target="_blank">USA </a>)
- Appassionati che vogliono prestazioni elevate: <a href="https://www.nodl.it/" target="_blank">NODL</a> / <a href="https://shop.nodl.it/en/home/38-nodl-samourai-edition.html" target="_blank">NODL Samourai</a>


## 3.3 - MicroPagamenti Bitcoin: Lightning Network
> **OBIETTIVO**: Capire cos'è Lightning Network e come poterla usare.

1. Download a non-custodial bitcoin lightning wallet
2. Transfer some bitcoin to it (a small amount)
3. Send bitcoin over lightning
4. Watch <a href="https://www.youtube-nocookie.com/embed/3PcR4HWJnkY" target="_blank">The Importance of Layer Two</a>
5. Read <a href="https://github.com/6102bitcoin/bitcoin-intro/raw/master/QA%20bitcoin-159-165.pdf" target="_blank">LNP/BP</a> as compared to TCP/IP (extract from <a href="https://twitter.com/QAaboutBitcoin" target="_blank">Q/A About Bitcoin</a>).


## 3.4 - Community
> **OBIETTIVO**: Scoprire come partecipare alla community bitcoin.

Ecco un elenco di alcuni gruppi ed eventi organizzati dalla community italiana di bitcoin

### Gruppi
#### Telegram
* [Bitcoin Italia](https://t.me/bitcoinIta) [2.7k+ membri]
* [Bitcoin: Tax & Law Italia](http://t.me/joinchat/A887ID6t77v2RcjCuuFwfg) [2.7k+ membri]
* [Bitcoin Milano](https://t.me/BitcoinMilan) [200+ membri]
* [Bitcoin - Fiat & Alt Trading](https://t.me/cryptotradingitalia) [900+ membri]
* [Bitcoin e gambling (Poker / scommesse)](https://telegram.me/joinchat/AAR0rz3LDH4tIKNJ52ubjg) [100+ membri]
* [Bitcoin: IQ, Tech, Econ & Politics](https://t.me/Bitcoin_e_politica) [100+ membri]
* [Hardware & Software (no mining)](https://t.me/ItalyBitcoinHWandSW) [150+ membri]
* [BW Arbitrage & Cryptoexchange](http://t.me/ArbitrageCryptoExchangeITA) [770+ membri]
* [Bitcoin Gateways](https://t.me/bitcoinIta_Gateways) [570+ membri]
* [Bitcoin e Servizi di Pagamento (carte & conti)](https://t.me/Bitcoineservizidipagamento) [1.1k+ membri]
* [Bitcoin Dev Italia](https://t.me/bitcoindevitalia) [270+ membri]
* [Liquid Italia (Bitcoin sidechain)](https://t.me/liquid_ita) [30+ membri]

-----

# LV. 4 - Saggio [ENG]
Sono uno [stregone](#lv-3---stregone-ita-eng) del mondo bitcoin e vorrei sviluppare ulteriormente la mia conoscenza attingendo dalle migliori fonti del sapere

## 3.5 - Ulteriori approfondimenti
> **OBIETTIVO**: Sviluppare ulteriormente la tua conoscenza di bitcoin

### Listen
1. <a href="https://youtu.be/Zbm772vF-5M?t=308" target="_blank">The Bitcoin Standard</a>
2. <a href="https://youtu.be/OrMHQhDKhrU" target="_blank">Intro to Bitcoin Austrian thought</a>

### Read
1. '<a href="https://bitcoin-only.com/#bitcoin" target="_blank">What Is Bitcoin</a>' by [Greg Walker](https://twitter.com/in3rsha) 
2. <a href="https://www.amazon.com/dp/1641990503" target="_blank">The Little Bitcoin Book</a>
3. <a href="https://www.amazon.com/Bitcoin-Sovereignty-mathematics-Knut-Svanholm/dp/1090109911" target="_blank">Sovereignty through mathematics</a>
4. <a href="https://www.amazon.com/Bitcoin-Standard-Decentralized-Alternative-Central/dp/1119473861" target="_blank">The Bitcoin Standard</a> (<a href="https://www.podbean.com/eu/pb-48576-a563c0" target="_blank">Listen</a> to the prologue)

### Watch
1.'<a href="https://www.rt.com/shows/to-the-moon/457141-bitcoin-digital-currencies-revolution/video/5cbc2abbdda4c844198b4657/" target="_blank">Bitcoin - The Genesis</a>' by [RT](https://twitter.com/RT_com)

