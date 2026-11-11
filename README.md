# Large-Scale-and-Multi-Structured-DBs-project

## Resoconto Post-Chiamata
### DUBBI:
 - Modifiche a UML finale: 
    - Via Unregistered User
    - Valutare arco *Admin->User* 
 - Attenzione alla similarita' tra utenti
 - Pensare a nuovo sketch per grafo 

### DROPPED:
- The system must recommend games similar to those played by the user -> Via la similarita' statica tra giochi
- Rankings (troppo simile alla ricerca)
### AGGIUNTE
- Il voto associato ad una recensione adesso va da 1 a 5
- GRAPH: Indice di Coesione della Playerbase
- DOC: Average Playtime e Std.Dev. voti 
- GRAPH + DOC: Polarization & Echo Chamber Index

### Materiale per GrillMe
- Specifiche progetto
- Contesto (cosa fa il progetto)
- Progetti passati a tema videogiochi (se buono)
- Progetto passati non a tema videogiochi (libri, auto...)

#### Nota: Cercando un utente si possono vedere i videogiochi a cui ha giocato, anche se non si e' amici

### Chi fa cosa?
#### DOCDB
- login/registrazione
- ricerca videogiochi/utenti
- iniziare/terminare/abbandonare videogioco
- recensire un gioco
- media voti videogioco
- devstd voti videogioco
- media playtime videogioco
- vedere recensioni di un videogioco
- calcolo videogiochi trending
- aggiungere/bannare/eliminare utente
- aggiungere/eliminare gioco
- admin: vedere le recensioni pubblicate da un utente
- utente: elimiare una SUA recensione
- admin: elimiare una recensione

#### GRAPHDB
- fare amicizia con un utente
- indice di coesione della playerbase
- similarita' tra utenti
- raccomandazione giochi in base a utenti simili

#### GRAPHDB + DOCDB
- polarization e echo chamber

Videogiochi vanno nel graphDB -> vedere gli amici che hanno completato un gioco GRAPHDB
Vedere i giochi completati da un utente e' una query solo su graphDB   

