# Teori

### Hva er forskjellen mellom en Hub og en Switch.

**Hub:**  
- Hub opererer på Level 1 av OSI-Modellen på den fysiske layern.
- Som en switch mottar en hub innkommende trafikk, men i motsetning til en switch sender den trafikken videre til alle porter, uavhengig av hvilken enhet dataene er ment for.
- Hub kom først, og switch kom senere.

**Switch:**  
- En switch opererer på Level 2 av OSI-Modellen, på Data-Link layern.
- Leser MAC-adresser og sender trafikken videre til riktig port basert på hvilken enhet som skal motta dataene.
- En switch håndterer nettverkstrafikk mer effektivt enn en hub fordi den vet hvor dataene skal sendes.


**Hvorfor brukte man hub-er?**
- **Enkle nettverk:** Hub-er var enkle å sette opp og krevde ingen konfigurering.
- **Lav pris:** De var billigere å produsere enn switch-er.
- **Små nettverk:** De kunne brukes til å koble sammen noen få enheter i mindre nettverk.
- **Tidlig nettverksteknologi:** Hub-er var vanlige i eldre Ethernet-nettverk.
   
**Hvorfor bruker man switch-er i dag?**
- Bedre utnyttelse av nettverkskapasiteten.
- Mindre unødvendig nettverkstrafikk.
- Hver port får sin egen collision domain.
- Mer effektiv kommunikasjon mellom enheter.
- Støtte for funksjoner som VLAN.
