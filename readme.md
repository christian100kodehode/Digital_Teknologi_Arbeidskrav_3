
![alt text](Header.jpg)
___
Student: Christian Westbye
___



- Oppgave 1


- Oppgave 2


(a)

    Forklaring:
    bit - Minste verdi for en datamaskin, kan kun være 0 eller 1.
    byte - Verdi satt sammen av 8 bit (0 - 7). Med en byte kan vi sette et tegn eller nummer fra ASCII tabellen.


(b)

    Binærverditabell, totallsystem (Grunntall = 2):

    Binær diagtabell som viser posisjon og verdi i hver bit i et 16-bit binært tall, fra høyre til venstre:

    | Bit Posisjon  | 15    | 14    | 13   | 12   | 11   | 10   | 9    | 8    | 7    | 6    | 5    | 4    | 3    | 2     | 1     | 0    |
    | ------------  | ----  | ----  | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----  | ----  | ---- |
    | Decimal Verdi | 32768 | 16384 | 8192 | 4096 | 2048 | 1024 | 512 | 256   | 128  | 64   | 32   | 16   | 8    | 4     | 2     | 1    |




Utregning fra desimal til binær

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





(c) Konverter fra binær til desimal
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



(d) Konverter teksten "DATA" fra ASCII til binær:

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



- Oppgave 3

(a) Hva er OSI Modellen:

    OSI-modellen (Open Systems Interconnection model) er et standardisert (teoretisk) rammeverk som forteller hvordan data-kommunikasjon fungerer i et nettverk. Består av 7 lag, der hver del har sin oppgave og kommuniserer kun med det laget som er over og under seg for å sørge for korrekt data flyt.



(b) Beskriv Lag 2 - Datalinklaget og Lag 3 - Nettverkslaget.

    Lag 3: Nettverkslaget (Network Layer)  IP-adresser, ruting  

    Dette er laget der IP-adresser kommer inn i bildet.  
    Ansvarlig for at datapakker blir levert til riktig destinasjon på tvers av nettverk.

    Lag 2: Datalinklaget (Data Link Layer)  MAC-adresser, rammer (frames)  
    Fokuserer på hvordan data pakkes inn i rammer og sendes over en enkelt fysisk forbindelse (f.eks. innenfor samme lokale nettverk).





(c) Forklar hvordan OSI modellen kan hjelpe teknikere å feilsøke nettverksproblem

     OSI modellen deler kommunikasjonen inn i 7 lag, hver med definerte oppgaver. Hvert lag kommuniserer kun med laget rett over og under seg som igjen gjør det enklere å forstå og feilsøke nettverks problemer og se hvor feilen har oppstått. Ved å jobbe seg oppover/nedover lagene og teste underveis, kan man lettere finne årsåkan og finne hvor problemet ligger.




- Oppgav 4

(a) Forklar RAM og ytelse, hva skjer når minnet er fullt.



(b) Oppgradere ram men eldre CPU, hvilke flaskehalser kan oppstå.




