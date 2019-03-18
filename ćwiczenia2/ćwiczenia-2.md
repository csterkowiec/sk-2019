Ustawianie parametrów sieci
---------------------------

![alt text][network]

[network]: ./network.png "Logo Title Text 2"

1. na 1 z komputerów zainstaluj oprogramowanie ``http-chat`` dostępne pod adresem ``https://github.com/jkanclerz/http-chat``

Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | 10.0.2.4 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  |  | |
| IP - address  | 10.0.2.5 | |
| MASKA  | 255.255.255.0 | |

Weryfikacja połączenia

Polecenie
```
ping 10.0.2.5 (będąc na komputerze z adresem 10.0.2.4)
```

Efekt
```
Pakiety zostają przesłane - komputery się "widzą".
```

Statyczna konfiguracja parametrów połączenia
Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | 192.168.10.10 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  |  | |
| IP - address  | 172.16.100.100 | |
| MASKA  | 255.255.0.0 | |

Weryfikacja połączenia

Polecenie
```
ping 172.16.100.100
```

Efekt
```
Docelowy host będzie nieosiągalny, ponieważ komputery znajdują się w różnych sieciach.
```

Nowa statyczna konfiguracja 

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  |  | |
| MASKA  |  | |
|   |  | |
| PC 2  |  | |
| IP - address  |  | |
| MASKA  |  | |

Weryfikacja połączenia

Polecenie
```
```

Efekt
```
```

Warto wiedzieć
--------------

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
| Lokalizacja pliku z konfiguracją sieci| /etc/sysconfig/network-scripts/ | |
| UP -> Wyłączenie interfejsu sieciowego| ifdown | |
| DOWN -> Włączenie interfejsu sieciowego| ifup | |
| Sprawdzenie obecnych parametrów | | |
| lista wszystkich interfejsów | | |
| Które interfejsy jakie porty słuchają | | |
