# myStrom-Switch

## Beschreibung 

Der Baustein liest einen myStrom Switch aus, und gibt Status, Version, Power (W), Temperatur und SSID aus.

Spenden sind gerne [hier](https://www.paypal.com/paypalme/reinhardsocha) willkommen


## Eingänge

| Nr. | Name         | Initialisierung | Beschreibung                                                                                            |
|-----|--------------|-----------------|---------------------------------------------------------------------------------------------------------|
| 1   | E1 IP        | ' '             | IP myStrom Switch                                                                                       |
| 2   | E2 Intervall | 0               | Bei einem Wert <> 0 werden die vom Switch zyklisch mit dem angegebenen Intervall in Sekunden abgerufen. |
| 3   | E3 Trigger   | 0               | Bei einem Wert <> 0 werden die Daten vom Switch abgerufen.                                              |
| 4   | E4 On/Off    | 0               | Hier kann der Switch Ein oder Aus geschalten werden (0 / 1)                                             |    


## Ausgänge

| Nr. | Name           | Initialisierung | Beschreibung                                            |
|-----|----------------|-----------------|---------------------------------------------------------|
| 1   | A1 Status      | 0               | Status On/Off                                           |
| 2   | A2 Version     | ' '             | Ausgabe Firmware vom Swtich                             |
| 3   | A3 Power [W]   | 0               | Ausgabe Power [W]                                       |
| 4   | A4 Temperatur  | 0               | Ausgabe Temperatur                                      | 
| 5   | A5 SSID        | ' '             | Ausgabe verbundene SSID                                 | 


## Beispielwerte

| Eingang | Ausgang |
| --- | --- |
| - | - |


## Other

- Neuberechnug beim Start: Nein
- Baustein ist remanent: nein
- Interne Bezeichnung: 12829
- Kategorie: Datenaustausch

### Change Log


 - v0.1
   - Initial

   
   


## Licence

Copyright 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
