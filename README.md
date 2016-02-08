# Registreringsapplikation

### Instruktioner

- ``` git clone https://github.com/jb223cp/1DV450_jb223cp.git ```
- Från mapp i vilken befinner sig applikation kör : ``` cd Registration ``` 
- ``` bundle install ``` (om användare använder Windows operativsystem, efter bundle istall, kör ```gem install tzinfo-data```
- ``` rake db:migrate```
- ``` rake db:seed```  Skapar en användare med admin rättigheter, och en användare med vanliga rättigheter
- ``` rails s -b $IP -p $PORT ``` i Cloud9 IDE eller ``` rails s  -b 0.0.0.0 ``` om applikationen ska köras lokalt

##### Administrator rättigheter:
USERNAME: admin
PASSWORD: test

##### Användare rättigheter:
USERNAME: calle
PASSWORD: test1

Lycka till!
