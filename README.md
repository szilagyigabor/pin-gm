# pin-gm
PIN-dióda alapú Geiger Müller-számláló

Hackaday összefoglaló: https://hackaday.com/2014/10/25/use-a-cheap-pin-diode-as-a-geiger-counter/
Német oldal többek között ennek a GM-számlálónak a részletes leírásával: http://opengeiger.de/index_en.html

BOM (a through hole schematic alapján, de főleg smd alkatrészekkel, 4 diódával):
	- BPW34, 4 db (az érzékelő PIN fotodióda) ok
	- TL 072CD, 1 db (valami smd változat) ok
	- LM358, 1 db (elvileg felületszerelt) ok
	- Jack, 1 db (S6BB 3.5mm mono szigetelt forrfüles Jack aljzat) ok
	- 9V elem csati, 1 db ok
	- 47 uF, 2 db (SMD, 1206 méret) ok
	- 100 nF, 7 db (SMD, 1206 méret) ok
	- 10 pF, 3 db (SMD, 1206 méret, visszacsatolásokhoz) ok
	- 10-40 pF trimmer, 1 db (through hole, d=10 mm, ?-200 pF helyett) ok
	- 4.7 Ohm, 1 db (SMD, 1206 méret) ok
	- 47 Ohm, 1 db (SMD, 1206 méret) ok
	- 1 kOhm, 5 db (SMD, 1206 méret) ok
	- 5.1 kOhm, 3 db (SMD, 1206 méret, 4.1 kOhm helyett) ok
	- 4.7 kOhm trimmer, 1 db (5 kOhm helyett) ok
	- 10 kOhm, 2 db (SMD, 1206 méret) ok
	- 15 kOhm, 1 db (SMD, 1206 méret) ok
	- 100 kOhm, 1 db (SMD, 1206 méret) ok
	- 10 MOhm, 1 db (SMD, 1206 méret) ok
	- 1 mH, 1 db (SMD-SRR0604) ok
	- doboz (75\*115.5\*54.5 mm, alu)
	- elem