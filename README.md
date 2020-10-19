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

### Week 4 


het hilarische  tijdelijke aansluitingsschema 

#### Op DIN
Pwer->EnergyMeter->Server-> Tree Extention -> Dimmmer Extension->AirExtention

#### Aangesloten met Tree cable 
Touch - > Motion 

#### Gekoppeld aan Air Base

Ir , tubular motor , watersensor, smoke detector, window/door , air remote?


 

## Materiaallijst 

100001	 Miniserver Gen 1	https://www.loxone.com/enen/kb/miniserver-technical-info/

200001	Power Supply 24V 1.3A	https://www.loxone.com/enen/kb/power-supplies/

200002	Power Supply 24V 4.2A 	https://www.loxone.com/enen/kb/power-supplies/

100114	Air Base Extension	https://www.loxone.com/enen/kb/air-base/

100218	 Tree Extension	https://www.loxone.com/enen/kb/tree/

100029	Dimmer Extension	https://www.loxone.com/enen/kb/dimmer-setup/

100239	RGBW 24V Dimmer Tree	https://www.loxone.com/enen/kb/rgbw-24v-dimmer-tree/

100394	Loxone Tree Cable (200m/656ft) -- +- 1 meter	https://www.loxone.com/enen/kb/loxone-tree-cable/

100142	Smoke Detector Air	https://www.loxone.com/enen/kb/smoke-detector-air/

100210	Door& Window Contact Air-White	https://www.loxone.com/enen/kb/door-window-contact-air/

100222	Touch Tree - Anthracite	https://www.loxone.com/enen/kb/touch-tree/

200098	RGBW LED Strip 5m IP20	https://www.loxone.com/enen/kb/led-strip-new-build/

100327	LED Spot WW - White	https://www.loxone.com/enen/kb/led-spot-ww-tree/

100141	IR Control Air	https://www.loxone.com/enen/kb/ir-control-air/

100140	Remote Air    - ben niet zeker of we deze hebben – dit toestel heb ik nog niet gezien 

200049	 Coupling Relay	https://shop.loxone.com/enuk/coupling-relay.html

100182	Tubular Motor SOLIDline Air 10	https://www.loxone.com/wp-content/uploads/datasheets/GEIGER_E_BAL_SOLIDline-Flex-AIR_100W1580-000_EN.pdf

200157	3-Phase Modbus Energy Meter	https://www.loxone.com/enen/kb/modbus-energy-meter/

100211	Water Sensor Air -- hier zijn er 5 van maar ik herinner me niet dat we er eentje hadden	https://www.loxone.com/enen/kb/water-sensor-air/

100223	Motion Sensor Tree - White    --- hebben we dit wel ? er zijn er 5 maar ik herinner me niet dat we er eentje hadden	https://www.loxone.com/enen/kb/motion-sensor-tree/


