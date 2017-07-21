# Behoefte Drechtsteden

De behoefte van Gemeenschappelijk Regeling Drechtsteden is om per 1 januari 2018
alle koppelvlakken gerealiseerd te hebben. Het realiseren van koppelvlakken
betekent voor Drechtsteden dat alle applicaties gegevens uitwisselen met elkaar
via de centrale servicebus van Vicrea. De centrale voorziening waar de
servicebus onderdeel van uitmaakt wordt binnen Drechtsteden aangeduid met de
term "CDV". Met de snelheid waarmee gemiddeld genomen huidige
StUF-koppelvlakken gerealiseerd worden binnen Drechtsteden wordt de datum 1
januari 2018 zeker niet gehaald. Dit vraagt om een andere aanpak.

# Aanpak

De aanpak die Drechtsteden kiest is in lijn met het advies dat Solventa in
opdracht van KING begin 2017 heeft uitgebracht over het opstellen van
Eindproductstandaarden ter vervanging van StUF-BG en StUF-ZKN (zie http://www.gemmaonline.nl/images/gemmaonline/0/08/Eindproductstandaarden_-_vervanging_StUF-BG_en_StUF-ZKN.pdf).
Hieronder een opsomming van de voordelen van Eindproductstandaarden die in dit
advies benoemd worden:

- Eindproductstandaarden kunnen in hoger tempo worden opgesteld door KING.
- Aanbieders van applicaties kunnen eenvoudiger/goedkoper aan. eindproductstandaarden
voldoen aangezien deze minder complex zijn.
- Eindproductstandaarden zijn toegesneden op ketens en/of afgebakend op een domein en daarmee
specifieker.
- De eindproductstandaarden reduceren de ruimte voor interpretatieverschillen tot
nihil.
- KING kan de conformiteit aan eindproductstandaarden eenvoudiger toetsen.
- Door de inzet van eindproductstandaarden is de rolverdeling tussen applicaties
scherp gedefinieerd. 

Het advies is omarmd door de StUF Regiegroep en wordt als 
leidraad gehanteerd voor de opzet van de 'nieuwe StUF'. De nieuwe StUF is niet
radicaal anders, het borduurt zo veel mogelijk voort op de goede aspecten van
StUF en andere vastgestelde specificaties zoals LO GBA, RSGB en RGBZ.

# Nieuwe StUF

Met het omarmen van het advies gaat KING koersen richting een nieuwe StUF. Veel is
er onduidelijk over hoe dit traject er uit gaat zien. Een feit is dat
Drechtsteden graag de nek uitsteekt en leveranciers bij elkaar brengt om
conform eerder genoemd advies koppelvlakken te realiseren. Vicrea en Green
Valley zijn inmiddels druk bezig de eerste koppelvlakken te realiseren op basis van YAML/JSON. Met
deze resultaten gaat Drechtsteden bij KING aantonen dat er inderdaad vele
voordelen te behalen zijn met de inzet van Eindproductstandaarden en de technische mogelijkheden van YAML/JSON. Dit soort
praktijkvoorbeelden heeft KING nodig om de route naar een nieuwe StUF te
concretiseren.

Drechtsteden zelf is er daarnaast van overtuigd dat op deze wijze de koppelvlakken wel op 1
januari 2018 gerealiseerd kunnen zijn.

# YAML-specificatie en toepassing
YAML is ontwikkeld vanuit oogpunt van menselijke leesbaarheid en uitbreidbaarheid. YAML is dan ook goed voor mensen leesbaar, mede door de verplichte witruimtes in regels om structuur aan te geven. YAML ondersteund default object referenties en relationele structuren. Dit maakt het mogelijk om in YAML net als in XML eenvoudig cyclische datastructuren met diepe hiërarchie vast te leggen. YAML is geen XML, maar kent door de efficiëntere structuur wel een aantal grote voordelen boven XML. 
Met een YAML specificatie is het mogelijk om JSON webservices te genereren. Deze moeten dan nog wel in de software worden geplaatst. Dit kost zeker ook nog wel ontwikkeltijd, maar het is veel efficiënter en laat minder ruimte voor misinterpretatie dan de wijze waarop momenteel StUF wordt ingepast in de software. Precies op dit punt kan de inzet van YAML dus meerwaarde opleveren. Het is dus niet het idee dat JSON services dan alsnog handmatig worden gerealiseerd.
