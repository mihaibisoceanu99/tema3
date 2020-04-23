# Soluție

## 1. Traceroute

Am implementat soluția iar aici este output-ul:

### Ruta către IP1
```
IP154.14.32.129 - Meyrin, Geneva, Elvetia
89.149.136.121 - Neu Isenburg, Hesse, Germania
46.33.83.254 - Alfortville, Île-de-France, Franta
129.250.6.13 - Englewood, Colorado, Usa
129.250.7.8 - Englewood, Colorado, Usa
129.250.3.100 - Englewood, Colorado, Usa
129.250.2.240 - Englewood, Colorado, Usa
116.51.17.140 - Tokio, Tokio, Japonia
52.93.10.7 - Singapore, Singapore, Japonia
```

### Ruta către IP2
```
IP21 - Oraș, Regiune, Țară
IP22 - Oraș, Regiune, Țară
IP23 - Oraș, Regiune, Țară
...
IP2N - Oraș, Regiune, Țară
```

### Ruta către IP3
```
IP31 - Oraș, Regiune, Țară
IP32 - Oraș, Regiune, Țară
IP33 - Oraș, Regiune, Țară
...
IP3N - Oraș, Regiune, Țară
```


## 2. Reliable UDP

### Emițător - mesaje de logging
Rulăm `docker-compose logs emitator` și punem rezultatul aici:
```
....
....
....
....
....
```


### Receptor - mesaje de logging
Rulăm `docker-compose logs receptor` și punem rezultatul aici:
```
....
....
....
....
....
```
