# Scelte implementative:

#### Lato client:
I posti possono essere prenotati solo in riga verso destra, a partire da un posto designato
    
#### Lato server:
Lo storage deve essere nella cartella storage e deve essere allo stesso livello della cartella in cui è contenuto il codice compilato

### File sala:
    6 -> File
    12 -> Posti
    xxxxxoxxxxxx -> Sala
    ooooxooooooo -> Sala
    oooxxooooooo -> Sala
    ooooooxxxooo -> Sala
    oooooooooooo -> Sala
    oooooooooooo -> Sala
    xxxx=a1-3
    xxxx=e5-1
    xxxx=e10-1
    xxxx=c4-2
    xxxx=d7-3

#### Struttura codice prenotazioni:
- `aaaammddhhmmccxxxx` -> codice univoco
- `aaaa/mm/dd` -> data
- `hh:mm` -> orario spettacolo
- `xxxx` -> codice univoco
