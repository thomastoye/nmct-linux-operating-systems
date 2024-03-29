# Situatieschets

* Ik heb net een bedrijfje gekocht met veel groeipotentieel dat momenteel een Windows server heeft staan met een AD infrastructuur.
* Er is een productiefiliaal in het buitenland dat momenteel met een enkele PC werkt onder Windows XP die enkel gebruikt wordt voor kantoortoepassingen en internettoegang.
* Ik heb goede ervaringen met Linux en wil automatiseren op basis van Linux en FLOSS software. Mijn budget is beperkt wegens de overnamekost.

# Vraag

* Ik huur een team in om op korte termijn een oplossing voor te stellen die maakt dat ik een veilige en op groei berekende infrastructuur ter beschikking heb van mijn bedrijf.
* Jullie hebben 2 weken de tijd om een bindend voorstel te doen en vervolgens 4 weken om de basisinfrastructuur uit te rollen en nog 4 weken om af te werken indien nodig.

# Hoe gaan jullie te werk hiervoor?

* Kies een soort bedrijf dat ik heb: aantal personeelsleden, markt, producten, services, … Bedenk hierbij enkele bestaande voorbeeldbedrijven.
* Teken hierbij onmiddellijk ook uit welk essentiële bedrijfsprocessen moeten worden geautomatiseerd, rekening houdend met een generieke kmo, maar ook met de specifieke aard van dit bedrijf

## Maak een offerte

* Beslis of je gaat voor een volledige vervanging van de bestaande infrastructuur of voor een aanvulling op de bestaande.
* Specificeer mogelijke software die zou kunnen handig zijn om de verschillende bedrijfsprocessen te automatiseren. Denk hierbij zowel aan client als server.
* Maak een kostprijsschatting gebaseerd op een tijdsplanning. Deze tijdsplanning (een WBS) zal worden gebruikt ter evaluatie van de uitvoering van de voorgestelde offerte.

## Presentatie

* Presenteer jullie voorstel (volgende week laatste 2 uur)
* Beargumenteer de keuzes die jullie voorstellen
* Stel jullie WBS en tijdsplanning voor
* Stel de offerte voor
* Maak een TCO calculatie
* Stel je team voor en schets het belang van certificaties voor je team (zie verder)

## LPIC en Linux foundation certification

Iedereen in jullie team wordt verondersteld Linux gecertificeerd te zijn. Om duidelijk te maken wat dit inhoud voor de klant presenteer je ook volgende zaken:
* Wat zijn de  LPI certificatie tracks en wat moet je daar precies voor kennen?
* Wat zijn de Linux foundation certificatie tracks op en wat wordt daar verwacht?
* Wat is het grote verschil tussen deze 2 soorten certificatie en waarom zou je voor het ene of het andere kiezen?

# Onze case

Industriele bakkerij.

* Aantal personeelsleden: 20 personen die regelmatig met een computer werken
* Producten: brood, patisserie
* Markt: voedingsindustrie
* Er is een helpdeskmedewerker in het bedrijf

## Windows Server met Active Directory

Houden, niet overschakelen naar een Linuxoplossing (e.g. OpenLDAP). De Active Directory is gemakkelijker te beheren, en Linuxoplossingen (zoals Samba) kunnen we integreren met Active Directory.

## Automatisatie

Met Wake-on-LAN worden computers van op afstand ingeschakeld.

## Workstations

Er is bestaande infrastructuur. We zullen een deploymentserver opzetten om de workstations te imagen.

We voorzien support voor Linux-images (voor het grootste deel van de workstations) en Windows (voor applicaties die niet anders kunnen (e.g. Microsoft Office).

Voor de homedirectory van users: we zijn er nog niet aan uit. Voorstel is om met Samba te werken. Het probleem is dan hoe we dynamisch homedirs gaan aanmaken in Samba.

## Nodige software

### ERP

Afwegen: de software moet werken op Linux en Windows.

### VPN

Het remote bedrijf moet "binnenkunnen" bij het moederbedrijf.

### Access points

Met Active Directory-integratie.

### IP cams

Mogelijkheid, maar niet main focus.

### Printers

Integreren met Active Directory. We werken niet met cups, omdat je dan automatisch je printers krijgt op Windows. Met CUPS is dat moeilijker.

### Administratie van machines

Met een ADAM-module of Raspberry Pi.

### Thin client server software

Een server om thin clients te bedienen.

## TCO

## Voordelen certificatie


