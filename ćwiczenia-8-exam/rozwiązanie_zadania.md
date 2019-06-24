# Podsieci:
Sieć ```172.22.128.0/17``` należy podzielić na dwie podsieci ```LAN1``` mieszczącą 500 hostów oraz ```LAN2``` mieszczącą 5000 hostów.

Wyliczam maskę dla większej podsieci: potrzebna będzie maska /19 dająca nam 8192 hosty (/20 byłaby niewystarczająca ponieważ mieści jedynie 4094 hosty).

Adres podsieci ```LAN1```: ```172.22.128.0/19``` z adresem rozgłoszeniowym ```172.22.159.255```

Adres podsieci ```LAN2```: ```172.22.160.0/23``` z adresem rozgłoszeniowym ```172.22.161.255```

---

# Konfiguracja:

## Sieć NAT LAN1:
![LAN1](lan1.png)

## Sieć NAT LAN2:
![LAN2](lan2.png)

---
# Diagram:
![Diagram](Diagram_zadanie8.png)
