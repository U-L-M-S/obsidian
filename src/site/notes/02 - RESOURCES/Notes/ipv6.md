---
tags:
  - netzwerk/ip/ipv6
dg-publish: true
links: 
reference: "[[02 - RESOURCES/Notes/IP Address\|IP Address]]"
path: Notes
created: 2023-09-13 11:07
---
## ipv6 
128-bit-Binärzahlen, die in Hexadezimal dargestellt werden und mit "**:**" getrennt sind(Gruppen).
Es ist eine Erweiterung von [[02 - RESOURCES/Notes/ipv4\|ipv4]].

**2001:0db8:85a3:0000:0000:8a2e:0370:7334**

| 2001 | 0db8 | 85a3 | 0000 | 0000 | 8a2e | 0370 | 7334 |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0010000000000001 | 0000110111101000 | 1000010110100011 | 0000000000000000 | 0000000000000000 | 1000101000101110 | 0000001101110000 | 0111001100110100 |


### Verkürzung
Um IPv6 zu lesbarer zu machen kann man es verkürzen.
Hier sind die Regeln, die man es folgen muss:
- Führende Nullen in jeder Gruppe können weggelassen werden. 0db8 -> db8
- Gruppen von aufeinanderfolgenden Nullen können durch zwei Doppelpunkte "::" ersetzt werden, aber nur einmal pro Adresse. Dies kann nur gemacht werden, wenn es keine Verwechslungsmöglichkeiten gibt. 0000000000000000:0000000000000000 -> ::


| 2001 | 0db8 | 85a3 | 0000 | 0000 | 8a2e | 0370 | 7334 |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 2001 | db8  | 85a3 |      |      | 8a2e | 370  | 7334 |

**2001:0db8:85a3:0000:0000:8a2e:0370:7334**  -> **2001:db8:85a3::8a2e:370:7334**

