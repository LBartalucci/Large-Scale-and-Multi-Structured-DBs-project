# Large-Scale-and-Multi-Structured-DBs-project

## Resoconto Post-Chiamata
### DUBBI:
 - Chi fa cosa? Distinguere cosa fanno graphdb e docdb
 - Modifiche a UML finale: 
    - Via Unregistered User, 
    - Valutare arco *Admin->User* 
 - Attenzione alla similarita' tra utenti

### DROPPED:
- The system must recommend games similar to those played by the user -> Via la similarita' statica tra giochi
- Rankings (troppo simile alla ricerca)
### AGGIUNTE
- GRAPH:  Social Network Influence Factor (Indice di Coesione della Playerbase)
- DOC: Average Playtime(easy) e Tasso di Drop-off(piu' complesso)
- GRAPH + DOC: 
    -  Se le recensioni rimangono come sono: *Social Virality Velocity*
    -  Se le recensioni diventano granulari: *Polarization & Echo Chamber Index*
