# watermeter
Vattenmätare projekt för våra hästar


Viktigt! Jag tar inget ansvar här för att ni gör rätt :). 
Ni gör detta på eget bevåg. Jag bara delar med mig av min egen lösning som fungerar för mig och försöker förklara hur jag har gjort.


hårdvara.txt 
innehåller den hårdvara jag använt för att bygga mina sensorer.

esphome_sensor.yaml 
innehåller exempel på mina esphome sensorer för att mäta vatten förbrukningen.
Eftersom jag har flera vattenmätare så är det i princip bara att upprepa allt nedan fast med andra namn.
Därför kommer jag bara visa en sensor och vad jag gjort för en sensor. Men det är bara att kopiera varje sak om ni vill ha fler vattenmätare.

Tips! Notera vad entitet namnen är på esphome sensorn och på hjälparna ni skapar. Dessa behöver ni sedan ange i bla configuration.yaml
Då jag har kopierat min verkliga kod, så kan ni följa mina entiter och se vart dom används.

hjälpare.txt
innehåller mina hjälpare med förklaring.

utilitysensor.txt
innehåller alla mina utility sensorer jag skapat med förklaring. Kopiera ut yamlkoden om ni vill skapa identiska
Utilitysensor / mätare är ju en hjälpare också men jag valde att bryta ut den för sig själv

configuration.yaml
här ligger mina templates och övriga sensorer som jag behöver tillsammans med esphome sensorn för att skapa ytterligare fler sensorer
som tex: drack senast L, varaktighet etc.

automationer.txt 
innehåller alla mina automationer jag skapat inkl förklaring. Här får ni kopiera ut yamlkoden och klistra in när ni skapar era automationer.

utilitysensor.txt
innehåller alla mina utility sensorer jag skapat med förklaring. Kopiera ut yamlkoden om ni vill skapa identiska

hjälpare.txt
innehåller mina övriga hjälpare med förklaring.

script.txt
innehåller mina script som jag nyttjar från olika automationer m.m. inkl förklaringar.

lovelace.txt
innehåller mina kort som jag använder för att presentera datat. Bara att kopiera och sedan ändra efter ert behov och era sensorer.

nr.txt
här kommer jag lägga in alla node-red flöden, men dessa är inte "snygga" nog att läggas ut än.  ska se när jag orkar snygga till det.
Här ligger bara lite varningar huruvida flödet har stått på en längre stund.
Det går att lösa utanför node-red också om man vill.
