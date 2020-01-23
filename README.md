# Transportbånd

![Transportbånd](Oversiktsbilde av transportbånd.jpg)

- ##  Introduksjon
I dette prosjektet er målet å få transportbåndet (på lageret mellom 1ELR og 2ELR) i gang. Prosjektet innvolverer en blanding av pneumatikk, og elektronikk. Målet er at båndet skal være automatisk og selvstyrt, vi har sensorer og de fleste andre deler som er nødvendige for at båndet skal fungere. 
- ## Fremgangsplan
  - Få transportbåndet i gang ✔️
  - Få luft i sylinderne ✔️
  - Få koblet opp sensorene
  - Få koblet ferdig skap 2
  - Lage PLS program
  - Teste anlegget 

- ##  Oversikt
Transportbåndet fungerer fint med manuell styring. Når man først åpner ventilene tar det 1-2 minutter før man kan dytte klossene ved hjelp av pneumatikken, fordi ventilene tar litt tid for til å fylles med luft. Startposisjon for ventilene er når de røde bryterne står vertikalt. Da er luften stengt. På sylinderne står det hvilken rekkefølge man skal vri på bryterne (steg 1, 2, 3,...). 

Nå skal transportbåndet styres ved hjelp av PLS og kontaktorer. Last ned TwinCat 3 Engineering (XAE): https://www.beckhoff.com/twincat3/
og se tutorial på youtube. Vi har satt opp en testrigg til I/O modul sånn at vi kan koble den til pcen. I tillegg til dette må vi finne ut hvilke sensorer det er vi har på transportbåndet, slik at vi kan begynne å finne ut hva som må gjøres for å få de i gang.



- ##  Intro til PLS program
PLS progammet heter TwinCat 3, og er vanskeligere å bruke enn logosoft. Derfor må man investere en del tid for å lære seg å bruke programmet. Det er problemer med tilkoblinger mellom PC-en og modulen. 


