# Soluție

## 1. Traceroute

Am implementat soluția iar aici este output-ul:

### Ruta către IP1
```
www.intoday.in - India

154.14.32.129 - Meyrin, Geneva, Elvetia
89.149.136.121 - Neu Isenburg, Hesse, Germania
46.33.83.254 - Alfortville, Île-de-France, Franta
129.250.6.13 - Englewood, Colorado, USA
129.250.7.8 - Englewood, Colorado, USA
129.250.3.100 - Englewood, Colorado, USA
129.250.2.240 - Englewood, Colorado, USA
116.51.17.140 - Tokio, Tokio, Japonia
52.93.10.7 - Singapore, Singapore, Japonia
52.93.11.55 - Singapore, Singapore, Japonia
52.93.11.52 - Singapore, Singapore, Japonia
52.93.8.73 - Singapore, Singapore, Japonia
52.93.10.75 - Singapore, Singapore, Japonia
```

### Ruta către IP2
```
www.ukzn.ac.za - Africa de sud

62.115.165.186 - Budapesta, Budapesta, Ungaria
62.115.118.194 - Rasunda, Stockholm, Suedia
62.115.136.219 - Rasunda, Stockholm, Suedia
130.117.14.217 - Washington, Virginia, USA
130.117.1.205 - Washington, Virginia, USA
154.54.38.205 - Washington, Virginia, USA
130.117.1.10 - Washington, Virginia, USA
149.11.39.2 - Amsterdam, North Holland, Olanda
155.232.1.86 - Pretoria, Gauteng, Africa de sud
155.232.31.198 - Durban, KwaZulu-Natal, Africa de sud
155.232.152.59 - Durban, KwaZulu-Natal, Africa de sud

```

### Ruta către IP3
```
my.gov.au - Australia

195.66.224.166 - Londra, England, Marea britanie
202.84.247.18 - Wan Chai, Wan Chai, Hong kong
202.84.247.38 - Wan Chai, Wan Chai, Hong kong
203.50.13.93 - Sidney, New South Wales, Australia
203.50.6.96 - Sidney, New South Wales, Australia
203.50.6.129 - Canberra, ACT, Australia
203.50.8.33 - Canberra, ACT, Australia
165.228.52.50 - Hallam, Victoria, Australia

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
