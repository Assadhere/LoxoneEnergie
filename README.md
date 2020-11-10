# LoxoneEnergie
 Project: Loxone Energiebesparing Graduaat IOT 2
# Energiebesparing Loxone
Ons groepje heeft energiebesparing als doelstelling. Dit kunnen we door meerdere acties bereiken.

## Doelen
Aangezien we niet heel veel materiaal hebben moeten we een beetje creatief omspringen met hoe we energiebesparing interpreteren en hoe we dit verwezenlijken in ons project.

Mijn voorstel is:
- Verschillende lichtzones die tijdens daglicht maar een paar minuten aan gaan in bepaalde ruimtes.
- De zonwering/rolluiken worden creatief gebruikt om zoveel mogelijk licht binnen te laten maar ook zo weinig mogelijk hitte. Ik denk dat we het beste er van uitgaan dat ons "demo huis" 3-dubbel glas heeft.
- De zonnewering kan gebruikt worden als demo om lichten(Ledstrip en spot) te dimmen naarmate de zonnewering open gaat. 
- Mogelijk kunnen we licht meten met een PIR of andere sensor.
- Slimme klimatiseringssturing - Dit kunnen we niet IRL uitwerken maar al wel programmeren
- Slimme deur/raamsensoren - Een ruimte die open is moet bijvoorbeeld geen verwarming hebben aanstaan
- alerts voor openende deuren en ramen 
- Touch-zones gebruiken, verschillende sfeerzones zodat het grote licht niet moet branden.
- Verschil uitrekenen met het energieverbuik onder 'normale' omstandigheden zonder slimme sturing
- Double tap gebruiken met Loxone Touch om bij het verlaten van het huis alle lichten te doven en verwarming uit te zetten 


## Ideetjes met ESP

Sinds de kans erg klein is dat we materiaal van de school zullen ontvangen en de labotoegang er beperkt is lijkt het aangeraden om zelfvoorzienend te zijn.

We kunnen met enkele ESP32'jes vele elementen simuleren die aanwezig zouden zijn in onze smart home setup.

We kunnen met POST en GET requests over het lokale netwerk communiceren met de miniserver. Eventueel zouden we ook iets kunnen aansturen met een eigen MQTT server.
Op deze manier kan een ESP32 dienst doen als :
- een verwarming ( relay verbonden aan een waterkoker of een ander toestel waarmee we warmte kunnen genereren.
- een thermometer ( deze kan dan uitmeten hoe warm of koud de kamer is )
- een additionele lamp
- een luxmeter (om te bepalen of de automatische verlichting met PIR wel aan moet gaan )
- een ventilator = koelingsysteem


Met al deze elementen in ons achterhoofd kunnen we makkelijk het volgende scenario voorstellen:

Het is een warme ochtend 

## Wekelijkse verslagen 

Labo Verslagen


### Week 1 

Serge vult de hele les met relevante verhalen. In het laatste half uur mogen we al het materiaal van Loxone uitpakken en verdelen. 

Nadat alle rollen en het materiaal zijn ingedeeld in groepen duwt Serge alles zonder discriminatie weer door elkaar in de kasten.

### Week 2 

We nemen de tijd om de schade van de voorgaande week weer in te halen. 
Een definitieve rol- en groepenverdeling komt tot stand en al het materiaal wordt verdeelt in 5 groepen.

We maken een materiaallijst (zie materiaallijst) op van alles dat we hebben  en beginnen de Loxone documentatie te lezen. 

Sinds we beperkt materiaal beschikbaar hebben is er niet onmiddellijk om een project op te bouwen waarin Smart energiebesparing uitgebreid aan bod kan komen. 

We besluiten om alvast de pir sensor te gebruiken ( of een andere in de toekomst) om de sterkte van  het licht te meten en zo de lichten de laten dimmen naar gelang het natuurlijke licht op die moment om ze energie te besparen . ( te demonstreren met gordijnmotor?)

Met onze energiebesparingsmeter kunnen we dan ook uitmeten hoeveel energie en geld we dan kunnen besparen.

We sluiten de miniserver aan en maken een connectie met de Loxone config
We sluiten de energiemeter aan 
We koppelen de Air extention aan de miniserver en sturen hiermee de gordijnmotor aan  (nog niet helemaal zoals het zou moeten zijn maar er is al beweging :D )
We koppelen de Tree extention aan de miniserver 

[Eerste configuratie van miniserver video](https://www.youtube.com/watch?v=tU6_HpW234k)

[in en uitgangen Lox Config](https://www.youtube.com/watch?v=WtBnUZ039nw)

### Week 3 

Geen Labo , geen materiaal , geen probleem 

Er is een meeting met Maarten Hendrickx die duidelijk maakt dat er volgende week een werkende setup op tafel moet liggen.
We bespreken onderling onze ideeën voor de setup en zorgen ervoor dat we allemaal vertrouwt zijn met alle aspecten van de installatie die volgende week zal doorgaan . 

#### Videos van Loxone

[loxone energy management](https://www.youtube.com/watch?v=Qos-lW2XTx0)
[Efficiente Configuratie in Loxone Config](https://www.youtube.com/watch?v=niVk46c76ak)
[bouwstenen loxone config](https://www.youtube.com/watch?v=gm_AXAb1zTY)

[Slimme energiemeter Youless](https://www.youtube.com/watch?v=m-z0Rbo9ZSM&list=PLblG94XtXUvnhxSCKBbakdgilbL9Jq9Yf&index=29)




hulpvaardige links voor installatie volgende week: 
- [ledstrips + rgb tree](https://www.loxone.com/enen/kb/led-strips-new-build/)
- [loxone config docs](https://www.loxone.com/nlnl/kb-cat/loxone-config/)
- [configuratie lichtsturingsbouwstenen config](https://www.youtube.com/watch?v=lk0lifrXnsI)
- [vervolg](https://www.youtube.com/watch?v=wWAuZ1lk4Rk)
- [Tutorial: Automatische zonwering en ruimteklimaat](https://www.youtube.com/watch?v=Czq5HhtPKxs)
- [motor config](https://www.youtube.com/watch?v=lM85bBsKFDs)

https://www.loxone.com/enen/kb/auto-configuration/


### Week 4 


het hilarische  tijdelijke aansluitingsschema 

#### Op DIN
Pwer->EnergyMeter->Server-> Tree Extention -> Dimmmer Extension->AirExtention

#### Aangesloten met Tree cable 
Touch - > Motion 

#### Gekoppeld aan Air Base

Ir , tubular motor , watersensor, smoke detector, window/door , air remote?

### Week6

Mogelijkheden bekijken om data te sturen en ontvangen naar een esp om zo fictieve delen van onze setuo te emuleren (verwarmingsketel, lampen) 

https://blog.denninger.at/2018/iot-sending-temp-hum-esp8266-loxone-smart-home/



