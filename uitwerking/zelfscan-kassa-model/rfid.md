# Zelfscan kassa met RFID

### Waarom heb ik RFID toegepast?

Ik heb onderzoek gedaan naar RFID en zag daar vele voordelen in. Uniqlo maakt alleen gebruik van RFID tags in hun winkel. Zij scannen en verwijderen het alarm in 1 keer door de toonbank.  Dit leek me handig om toe te passen aan de zelfscan kassa. Door de RFID zal de zelfscan kassa het betalingsproces sneller afmaken.

Onderstaande link gaat naar het RFID onderzoek

{% page-ref page="../../onderzoek/rfid/" %}

Onderstaande link gaat naar Uniqlo onderzoek

{% page-ref page="../../onderzoek/participant-observation/uniqlo.md" %}

### Hoe maakt de zelfscan kassa gebruik van RFID?

{% tabs %}
{% tab title="RFID tags" %}
![Voorbeeld van RFID tag \(atlasrfidstore tag, z.d.\)](../../.gitbook/assets/3001874_5000-2__54073.1404936240.480.480.jpg)

**Producten**

Alle producten moeten zijn voorzien van een RFID tag. De RFID tag houdt data bij over het product en geeft het een unieke code. De RFID tag kan op verschillende manieren toegevoegd worden aan het product:

![RFID wire tag \(Atlasrfidstore laundry tag, z.d.\)](../../.gitbook/assets/embeddable_rfid_wire_tag__40380.1545318619.480.480.jpg)

Deze RFID wire tag kan flexibel in het product toegevoegd worden. Het kan in de wasmachine en is beter bestemd tegen warmte dan standaard RFID tags. Door dat het zo flexibel is kan het bijna overal toegepast worden.

![RFID laundry tag \(Atlasrfidstore laundry tag, z.d.\)](../../.gitbook/assets/invengo_lintrak-slim_uhf_rfid_tag__86045.1523413518.480.480.png)

Deze RFID tag is subtiel toegevoegd aan het waslabel. Net als de RFID wire tag kan deze RFID tag ook in de wasmachine. Ik wil de RFID laundry tag aanraden aan H&M als ze beslissen om met RFID te werken.

{% embed url="https://www.atlasrfidstore.com/laundry-tracking-sample-pack/" caption="Bron producten \(Atlasrfidstore laundry tag, z.d.\)" %}

![RFID label \(Atlasrfidstore label, z.d.\)](../../.gitbook/assets/zebra_rfid_labels__57438.1517879615.1280.1280.jpg)

Als H&M niet wil dat de producten een RFID tag krijgen is er een andere oplossing. De RFID label kan gebruikt worden op de prijskaart. Het is hierdoor wel makkelijker te verwijderen van het product. 

{% embed url="https://www.atlasrfidstore.com/rfid-label-4x6-for-the-zebra-zq520-rfid-printer-case-of-12-rolls-75-labels-per-roll/" caption="Bron label \(Atlasrfidstore label, z.d.\)" %}

**Wat is er mis met de huidige alarm labels?**

De huidige alarm labels zijn groot, opvallend en hebben een naald. De naald gaat door het product heen en kan het product beschadigen. Omdat de huidige alarm labels groot zijn kunnen ze niet aan alle producten worden toegepast. Ze kunnen niet toegepast worden aan accessoires, sokken, schoenen en make-up artikelen. Hierdoor zijn deze producten niet beveiligd en kunnen makkelijker gestolen worden. 

Als er geen gebruik van de RFID tag wordt gemaakt zou de zelfscan kassa net als dat van Zara werken. Dan moesten de consumenten zelf de alarm labels handmatig verwijderen. Dit kan een gedoe zijn als de magneet, wat de alarm labels uit elkaar haalt, niet goed werkt. Het kan ook gevaarlijk zijn door de naald van de alarm labels. 
{% endtab %}

{% tab title="RFID reader" %}
![Voorbeeld ge&#xEF;ntegreerde RFID reader \(Atlasrfid reader, z.d.\)](../../.gitbook/assets/astra-ex_integrated_rfid_reader_45_angle.a76ef047d8d24c03823acdf41c4ee7c8__33258.1542730713.480.480.jpg)

**Waar zit de reader?**

De RFID reader zit onderaan de toonbank van de zelfscan kassa. Het maakt niet uit dat er een stuk materiaal tussen de RFID reader en de RFID tag zit. Een RFID reader kan namelijk radio frequente golven door materialen heen sturen. 

**Wat doet de reader?**

De RFID reader stuurt radio frequente golven uit via de antenne \(zie afbeelding hieronder\). Door de radio frequente golven ontvangen de RFID tags het signaal dat ze worden gescand. De RFID tags sturen een radio frequente golf terug met de data over het product. De antenne stuurt deze data naar de RFID reader. De RFID reader stuurt deze data dan weer door naar de zelfscan kassa.

![Voorbeeld RFID antenna \(Atlasrfid antenna, z.d.\)](../../.gitbook/assets/laird_s9025prs8655pr_rhcp_outdoor_rfid_antenna__06691.1480973451.480.480.jpg)

{% embed url="https://www.atlasrfidstore.com/laird-s9025pr-s8655pr-rhcp-outdoor-rfid-antenna-fcc-etsi/" caption="\(Atlasrfid antenna, z.d.\)" %}

**Hoe sterk is de reader?**

De toonbank van de zelfscan kassa is 50 cm hoog. Om alle producten hier in te scannen heeft de RFID reader en RFID antenna ongeveer 13.56 MHz nodig. Met dit aantal MHz kan de zelfscan kassa alles scannen op de toonbank.

MHz = De frequentie van radiozenders op de korte golf.

Ik heb een tabel gemaakt met de eigenschappen van de RFID tags, readers, antenna's en kabels. Dit is te vinden door op de page link hieronder te klikken.

{% page-ref page="../../onderzoek/rfid/wat-is-rfid.md" %}

**Hoe gaat het alarm eraf?**

Na het betalen stuurt de RFID reader radio frequente golven via de RFID antenna een kill code. De kill code wordt specifiek gestuurd naar de producten met de RFID tags en haalt hiervan het alarm eraf. 

Voor meer informatie klik op de page link hieronder.

{% page-ref page="../../onderzoek/rfid/hoe-kan-rfid-beveiligd-worden.md" %}
{% endtab %}

{% tab title="Winkel voordelen" %}
* Iedere ochtend voegen werknemers alarm labels toe aan de producten
  * Dit hoeft niet meer door de RFID tags
* Er kan via een aparte RFID reader en RFID antenna in een paar keer het magazijn gescand worden op producten. 
  * Hierdoor weten de werknemers welke producten er allemaal zijn en het aantal
  * De maximale afstand wat de RFID reader en RFID antenna kunnen scannen is 10 meter
* De poorten bij de uitgang maken ook gebruik van RFID reader en antenna's
  * Wanneer iets wordt gestolen weet de RFID reader precies welk product is gestolen door de unieke code in de RFID tag.
  * Het alarm gaat af wanneer het scant dat de RFID tag nog geen kill code heeft ontvangen.
{% endtab %}
{% endtabs %}

