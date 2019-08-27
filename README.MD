
## Aluksi
1. Asenna Docker
2. Luo kansioon tiedosto .env.production.local, johon tulee ympäristömuuttujat. 

## Sovelluksen ajaminen
### Käynnistä sovellus 
```$ docker-compose up```
Sovellus pyörii nyt osoitteessa http://localhost:5001/

### Sulje sovellus
```$ docker-compose down```

### Päivitä muutokset
```$ docker-compose build --no-cache```




