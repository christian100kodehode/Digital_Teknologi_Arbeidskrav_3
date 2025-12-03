
![alt text](Header.jpg)
___
Student: Christian Westbye 
___
[Github Repo.](https://github.com/christian100kodehode/Digital_Teknologi_Arbeidskrav_3)


# Oppgave 1

Musikk industrien.

Den digitale revolusjon har totalt forandret hvordan musikk benyttes, distribueres og handles. Dette har skjedd hurtig i de siste tjue åra med fokus på fysisk til digitale format.

Man gikk fra vinyl, kasett og til CD`en på av 90tallet, med en stabil høy pris og en stor andel samlere/kjøpere. Musikk butikker fantes overalt, i både små og store byer. Musikk industrien solge godt og brukte mye ressurser på sine artister og produksjoner for å posisjonere seg i markedet. Distribusjons avtaler var viktig og dette avgjorde ofte hva du kunne finne i din lokale musikk butikk (både kjeder og selvstendige var vanlig.)

I slutten av 90 tallet, med internett som verktøy ble verden koblet sammen på en ny måte. Nå trengte man ikke kjøpe musikkblader fra utlandet for å få med seg nye artister og mulighetene for å finne nye artister utenfor de stor distribusjons nettverkene oppsto.

Med ny kraftig komprimering av musikk filer (mp3) kunne man plutselig laste ned musikk som før var for tungt (full audio cd 74minutt, 700MB) og tidkrevende for modem og isdn linjer (14.4kilobits per sekund eller ISDN med 64kilobits per sekund). Med en mp3 med 6kbs komprimering kunne et 45minutt album komme ned på 20MB.

Dette bidro også til cd brenning og kopiering av mange album/sanger på en cd. Dedikerte MP3 spillere som (feks. iPod) fortsatte trenden ved å la brukerene ha med seg hele samlinger med musikk i et lite lomme-format.

Diverse rettsaker pågikk rundt 2000tallet for å stoppe mye av fildelingen av musikk, mange tejenster ble lagt ned men kopieringen fortsatte med nye tjenester eller bare fra venner til venner lokalt.

Internett hastigheten ble raskere og raskere og mange firma begynte å eksperimentere med strømming av lyd og video direkte uten nedlastning.

I 2006 ble Spotify grunnlagt av to svensker, med et ønske om å tilby musikk på en lovlig måte, som både plateselskapene og lytterene ville være fornøyde med. Løsningen deres ble en abbonent løsning der en månedspris ga tilgang til all musikk tilgjengelig.

Denne modellen for å tilby alt for en månedspris ble brukt av mange etterhvert som kanskje mest kjent for film/tv Netflix.

Artister på slike løsninger som Spotify får betalt i en per avspiller basis (og per lokasjon, en lytter kan være mere verdt i noen deler av verden), men en stor kontrovers over små utbetalinger til mindre artister og store utbetalinger til dem med millioner av avspillinger på alle deres låter.



# Oppgave 2
## (a)

    Forklaring:
    bit - Minste verdi for en datamaskin, kan kun være 0 eller 1.
    byte - Verdi satt sammen av 8 bit (0 - 7). Med en byte kan vi sette et tegn eller nummer fra ASCII tabellen.


## (b)

    Binærverditabell, totallsystem (Grunntall = 2):

    Binær diagtabell som viser posisjon og verdi i hver bit i et 16-bit binært tall, fra høyre til venstre:

    | Bit Posisjon  | 15    | 14    | 13   | 12   | 11   | 10   | 9    | 8    | 7    | 6    | 5    | 4    | 3    | 2     | 1     | 0    |
    | ------------  | ----  | ----  | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----  | ----  | ---- |
    | Decimal Verdi | 32768 | 16384 | 8192 | 4096 | 2048 | 1024 | 512 | 256   | 128  | 64   | 32   | 16   | 8    | 4     | 2     | 1    |




## Utregning fra desimal til binær

    (A) 12

    Deling på 2 nedover: uten rest = 0, rest = 1.
    Utregning:
    | 12 / 2 = 0 (ingen rest = 6) |
    |  6 / 2 = 0 (ingen rest = 3) |
    |  3 / 2 = 1 (rest = 1)       |
    |  1 / 2 = 1 (rest = 1)       |


    12 desimal = 1100 binær
    -------------------------

    | Posisjon      | 3   | 2   | 1   | 0   |
    |---------------|-----|-----|-----|-----|
    | Desimalverdi  | 8   | 4   | 2   | 1   |
    | Binærtall     | 1   | 1   | 0   | 0   |

    Desimalverdi (8 * 1) + (4 * 1) + (2 * 0) + (1 * 0)= 12




    (B) 27

    Deling på 2 nedover: uten rest = 0, rest = 1.
    | 27 / 2 = 1 (rest = 13)      |
    | 13 / 2 = 1 (rest =  6)      |
    |  6 / 2 = 0 (ingen rest = 3) |
    |  3 / 2 = 1 (rest = 1 = 1)   |
    |  1 / 2 = 1 (rest = 1 = 1)   |

    27 desimal = 11011 binær

    | Posisjon     | 4   | 3   | 2   | 1   | 0   |
    |--------------|-----|-----|-----|-----|-----|
    | Desimalverdi |  16 | 8   | 4   | 2   | 1   |
    | Binærtall    |   1 | 1   | 0   | 1   | 1   |

    Desimalverdi (16 * 1) + (8 * 1) + (4 * 0) + (2 * 1) + (1 * 1) = 27





## (c) Konverter fra binær til desimal
        binær = 101110
    
        | Posisjon      | 5   |  4  | 3  | 2  | 1   | 0  |
        |---------------|-----|-----|----|----|-----|----|
        | Desimalverdi  | 32  |  16 | 8  | 4  | 2   | 1  |
        | Binærtall     |  1  |   0 | 1  | 1  | 1   | 0  |


        Desimalverdi (32 * 1) + (16 * 0) + (8 * 1) + (4 * 1) + (2 * 1) + (1 * 0) = 46


        Dobbel hver verdi fra venstre posisjon og nedover, legg sammen til slutt på høyre side for desimaltall


        Begynn fra venster:                 1
        Dobbel 1 = 2 legg til neste verdi , 0 = 2
        Dobbel 2 = 4 legg til neste verdi , 1 = 5
        Dobbel 5 = 10  legg til neste verdi , 1 = 11
        Dobbel 11 = 22 legg til neste verdi , 1 = 23
        dobbel 23 = 46 legg til neste verdi , 0 = 46
                binær 10111 = 46 desimal

        _________________________________
        Andre utregning eksempler:

                    Andre eksempler: 1010

                    Begynnn fra venstre:  1 
                        1 * 2   2 + 0 = 2
                        2 * 2   4 + 1 = 5
                        5 * 2  10 + 0 = 10


                        Binær 0111 = 10 desimal

                        Begynn fra venstre:  0
                        0*2 + neste verdi 1 = 1
                        1*2 + neste verdi 1 = 3
                        3*2 + neste verdi 1 = 7

                        Binær  0111 = 7 desimal



## (d) Konverter teksten "DATA" fra ASCII til binær:


    01000100 01000001 01010100 01000001

    ______

    Kalkulering:

    Ascii verdien for D er 68.

    68 / 2 = 34 ingen rest = 0
    34 / 2 = 17 ingen rest = 0
    17 / 2 = 8, rest =       1
    8/2 = 4 ingen rest =     0
    4/2 = 2ingen rest =      0
    2/2 = 1 ingen rest =     0
    1/2 = 0 rest =           1
    0/2 = 0 ingen rest =     0

    01000100 = D 

    ______

    Ascii verdien for A er 65.

    65 / 2 = 32 + rest     = 1
    32 / 2 = 16 ingen rest = 0
    16 / 2 = 8 ingen reset = 0
    8 / 2 = 4 ingen rest =   0
    4 / 2 = 2 ingen rest =   0
    2 / 2 = 1 ingen rest =   0
    1 / 2 = 0 + rest =       1
    0 / 2 = 0 ingen rest =   0

    01000001 = A

    _____

    Ascii verdien for T er 84.

    84 / 2 = 42 ingen rest = 0
    42 / 2 = 21 ingen rest = 0
    21 / 2 = 10 rest      =  1
    10 / 2 = 5 ingen rest =  0
    5 / 2 = 2 rest        =  1
    2 / 2 = 1 rest        =  0
    1 / 2 = 0 rest        =  1
    0 / 2 = 0 rest        =  0

    01010100 = T

    ______

    Ascii verdien for A er 65.

    65 / 2 = 32 + rest     = 1
    32 / 2 = 16 ingen rest = 0
    16 / 2 = 8 ingen reset = 0
    8 / 2 = 4 ingen rest =   0
    4 / 2 = 2 ingen rest =   0
    2 / 2 = 1 ingen rest =   0
    1 / 2 = 0 + rest =       1
    0 / 2 = 0 ingen rest =   0

    01000001 = A



# Oppgave 3

## (a) Hva er OSI Modellen:

    OSI-modellen (Open Systems Interconnection model) er et standardisert (teoretisk) rammeverk som forteller hvordan data-kommunikasjon fungerer i et nettverk. Består av 7 lag, der hver del har sin oppgave og kommuniserer kun med det laget som er over og under seg for å sørge for korrekt data flyt.



## (b) Beskriv Lag 2 - Datalinklaget og Lag 3 - Nettverkslaget.

    Lag 3: Nettverkslaget (Network Layer)  IP-adresser, ruting  

    Dette er laget der IP-adresser kommer inn i bildet.  
    Ansvarlig for at datapakker blir levert til riktig destinasjon på tvers av nettverk.

    Lag 2: Datalinklaget (Data Link Layer)  MAC-adresser, rammer (frames)  
    Fokuserer på hvordan data pakkes inn i rammer og sendes over en enkelt fysisk forbindelse (f.eks. innenfor samme lokale nettverk).





##  (c) Forklar hvordan OSI modellen kan hjelpe teknikere å feilsøke nettverksproblem

     OSI modellen deler kommunikasjonen inn i 7 lag, hver med definerte oppgaver. Hvert lag kommuniserer kun med laget rett over og under seg som igjen gjør det enklere å forstå og feilsøke nettverks problemer og se hvor feilen har oppstått. Ved å jobbe seg oppover/nedover lagene og teste underveis, kan man lettere finne årsåkan og finne hvor problemet ligger.




# Oppgav 4

## (a) Forklar RAM og ytelse, hva skjer når minnet er fullt.

    Ram (Random Access Memory) er datamaskinens minne som brukes etter behov/setup fra operativsystem og applikasjoner. Det er ett høyhastigighets område for lagring av data som maskinen aktivt bruker. Rask tilgang, flytting og prossesering av store mengder data blir da mulig.

    Ram kjører på mye høyere lese/skrive hastighet mot en harddisk/sdd, jo mere ram du har jo mer data kan kjøres direkte fra minnet og mindre deler hentes opp fra harddisk/ssd.

    Er minnet fullt blir deler av harddisk/ssd brukt som minne (virtual memory). Harddisk/ssd er ikke like rask som minnet og applikasjoner/operativsystem vil da ikke ha samme ytelse og hastighet som om man hadde nok fysisk minne ledig. Denne prosessen blir kallet swapping eller paging.

    Har man ingen diskplass og ram igjen så kan man oppleve at systemet står/fryser og/eller applikasjon kan avslutte eller krasje for å så å frigjøre minne (henger applikasjonen kan man måtte avslutte manuelt for å frigi minnet).

## (b) Oppgradere ram men eldre CPU, hvilke flaskehalser kan oppstå.

    Man kan oppleve at man ikke får utnyttet hastigheten på ram brikker viss minne kontrolleren i denne eldre cpu ikke støtter denne hyøere hastighet, man må også passe på å kjøpe en rett ram type til sitt hovedkort. Har man opplevd at minnet ble fullt ofte før oppgradering av minnet vil man oppleve at maskinen er raskere siden man vil slippe å bruke for mye virtuellt minne og harddisk/ssd som må flytte på data. 
    
    Selve regneoperasjoner vil ikke få høyere hastighet i seg selv med en slik oppgradering (ny cpu trengs da).



