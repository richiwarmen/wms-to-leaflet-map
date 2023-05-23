# WMS-bestand uitlezen en beschikbaar maken op leaflet kaart
[RIVM WMS Dat](https://data.rivm.nl/geo/alo/wms) als voorbeeld wms bestand

Deze file demonstreert het gebruik van RIVM-data als een voorbeeld WMS-bestand met behulp van Leaflet en JavaScript. Het bevat code om de lagenlijstcontainer (`#layerListContainer`) aan de linkerkant van de pagina weer te geven, met een maximale hoogte van het scherm en een verticale schuifbalk indien nodig. De Leaflet-kaart (`#map`) neemt de rest van de beschikbare ruimte aan de rechterkant in beslag.

## Functionaliteiten

- Weergave van lagenlijstcontainer aan de linkerkant van de pagina.
- Maximale hoogte van de lagenlijstcontainer op basis van het scherm.
- Verticale schuifbalk toegevoegd aan de lagenlijstcontainer indien nodig.
- Verplaatsing van geselecteerde lagen naar de bovenkant van de lijst wanneer de bijbehorende checkbox is geselecteerd. Hierdoor worden de geselecteerde lagen altijd bovenaan de lijst weergegeven.
