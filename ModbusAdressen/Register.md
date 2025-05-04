| Function ID (HEX) | Name                               | Bytes | Datentyp | Skalierung | Beispielwert (Hex) | Beispielwert (Dezimal) | Beschreibung                                   |
|-------------------|------------------------------------|-------|----------|------------|--------------------|------------------------|------------------------------------------------|
| 0x0001            | PV1 voltage                        | 2     | u16      | 0.1 V      | 450 (0EC)          | 45 V                   | Spannung von PV1                               |
| 0x0002            | PV1 current                        | 2     | u16      | 0.1 A      | 150 (0EC)          | 15 A                   | Strom von PV1                                  |
| 0x0003            | PV1 power                          | 2     | u16      | 1 W        | 250 (0EC)          | 250 W                  | Leistung von PV1                               |
| 0x0004            | PV2 voltage                        | 2     | u16      | 0.1 V      | 450 (0EC)          | 45 V                   | Spannung von PV2                               |
| 0x0005            | PV2 current                        | 2     | u16      | 0.1 A      | 150 (0EC)          | 15 A                   | Strom von PV2                                  |
| 0x0006            | PV2 power                          | 2     | u16      | 1 W        | 250 (0EC)          | 250 W                  | Leistung von PV2                               |
| 0x0007            | PV3 voltage                        | 2     | u16      | 0.1 V      | 450 (0EC)          | 45 V                   | Spannung von PV3                               |
| 0x0008            | PV3 current                        | 2     | u16      | 0.1 A      | 150 (0EC)          | 15 A                   | Strom von PV3                                  |
| 0x0009            | PV3 power                          | 2     | u16      | 1 W        | 250 (0EC)          | 250 W                  | Leistung von PV3                               |
| 0x000A            | PV4 voltage                        | 2     | u16      | 0.1 V      | 450 (0EC)          | 45 V                   | Spannung von PVA                               |
| 0x000B            | PV4 current                        | 2     | u16      | 0.1 A      | 150 (0EC)          | 15 A                   | Strom von PVA                                  |
| 0x000C            | PV4 power                          | 2     | u16      | 1 W        | 250 (0EC)          | 250 W                  | Leistung von PVA                               |
| 0x000D            | grid power                         | 2     | u16      | 1 W        | 500 (0EC)          | 500 W                  | Netzleistung                                   |
| 0x000F            | battery voltage                    | 2     | u16      | 0.1 V      | 550 (0EC)          | 55 V                   | Batteriespannung                               |
| 0x0010            | battery SOC                        | 2     | u16      | 1 %        | 100 (0EC)          | 100 %                  | Batterie-Ladezustand (SOC)                     |
| 0x0013            | Daily power generation             | 4     | u32      | 0.01 kWh   | 100 (0EC)          | 1 kWh                  | Tägliche Energieerzeugung                      |
| 0x0015            | Monthly power generation           | 4     | u32      | 0.01 kWh   | 100 (0EC)          | 1 kWh                  | Monatliche Energieerzeugung                    |
| 0x0017            | Daily grid-connected electricity   | 4     | u32      | 0.01 kWh   | 100 (0EC)          | 1 kWh                  | Tägliche Netzeinspeisung                       |
| 0x0019            | Monthly grid-connected electricity | 4     | u32      | 0.01 kWh   | 100 (0EC)          | 1 kWh                  | Monatliche Netzeinspeisung                     |
| 0x001B            | get the device ID                  | 2     | u16      | –          | –                  | –                      | Geräte-ID abrufen                              |
| 0x001C            | EMS version                        | 2     | u16      | –          | –                  | –                      | Version des EMS-Systems                        |
| 0x001D            | INV version                        | 2     | u16      | –          | –                  | –                      | Version des Wechselrichters                    |
| 0x001E            | MPPT version                       | 2     | u16      | –          | –                  | –                      | Version des MPPT-Controllers                   |
| 0x001F            | BMS version                        | 2     | u16      | –          | –                  | –                      | Version des Batteriemanagementsystems (BMS)    |
| 0x0022            | screen version                     | 2     | u16      | –          | –                  | –                      | Version der Anzeige                            |
| 0x0025            | device type                        | 2     | u16      | –          | –                  | –                      | Gerätetyp                                      |
| 0x1004            | PV1 working status                 | 2     | u16      | –          | –                  | –                      | Arbeitsstatus von PV1                          |
| 0x1005            | PV2 working status                 | 2     | u16      | –          | –                  | –                      | Arbeitsstatus von PV2                          |
| 0x1006            | PV3 working status                 | 2     | u16      | –          | –                  | –                      | Arbeitsstatus von PV3                          |
| 0x1007            | PV4 working status                 | 2     | u16      | –          | –                  | –                      | Arbeitsstatus von PV4                          |
| 0x1008            | INV working status                 | 2     | u16      | –          | –                  | –                      | Arbeitsstatus des Wechselrichters              |
| 0x1009            | charge and discharge marker        | 2     | u16      | –          | –                  | –                      | Lade-/Entlade-Marker                           |
| 0x100A            | allowable discharge power          | 2     | u16      | 1 W        | –                  | –                      | Zulässige Entladeleistung                      |
| 0x4000            | surplus power feed-in              | 2     | u16      | –          | –                  | –                      | Überschussleistungseinspeisung                 |
| 0x4001            | reset the jugter                   | 2     | u16      | –          | –                  | –                      | Zurücksetzen des Jugters (unbekannter Begriff) |
| 0x4002            | select EMS mode                    | 2     | u16      | –          | –                  | –                      | EMS-Modus auswählen                            |
| 0x4003            | set the grid-connected power       | 2     | u16      | 1 W        | –                  | –                      | Netzeinspeiseleistung festlegen                |
| 0x4004            | set the Device ID                  | 2     | u16      | –          | –                  | –                      | Geräte-ID festlegen                            |



![image](https://github.com/user-attachments/assets/8e10a0b8-39a0-4dcb-9799-d3f58f7e57cd)
