Einfaches Tastatur-Layout für deutsche Apple-Tastatur unter Windows.

Erstellt mit dem Microsoft Keyboard Layout Creator:
https://www.microsoft.com/en-us/download/details.aspx?id=102134

Zunächst muss der Bootcamp-Treiber installiert werden.


Dieser kann mit Brigadier heruntergeladen werden:
https://github.com/timsutton/brigadier
```
.\brigadier.exe -m MacBookAir9,1
```
Der Treiber ist dann in der `.inf`-Datei unter `BootCamp/Drivers/Apple/AppleKeyboardMagic2` zu finden.
