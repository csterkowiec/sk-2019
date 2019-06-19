# Podsieci:
Sieć ```172.22.128.0/17``` należy podzielić na dwie podsieci ```LAN1``` mieszczącą 500 hostów oraz ```LAN2``` mieszczącą 5000 hostów.

Wyliczam maskę dla większej podsieci: potrzebna będzie maska /19 dająca nam 8192 hosty (/20 byłaby niewystarczająca ponieważ mieści jedynie 4094 hosty).

Adres podsieci ```LAN1```: ```172.22.128.0/19``` z adresem rozgłoszeniowym ```172.22.159.255```
