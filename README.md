# Collegues Web API

```
GET    /collegues
GET    /collegues/1
POST   /collegues
PUT    /collegues/1
PATCH  /collegues/1
DELETE /collegues/1
```

Exemple de collègues :

```json

{
    "matricule": "bd540e65",
    "nom": "Ross",
    "prenom": "Roberts",
    "email": "robertsross@sultraxin.com",
    "dateNaissance": "1980-03-13T05:22:33 -01:00",
    "sexe": "male",
    "adresse": "363 Dunne Court, Gardners, 3979",
    "password": "$2a$04$Vbug2lwwJGrvUXTj6z7ff.97IzVBkrJ1XfApfGNl.Z695zqcnPYra",
    "photo": "https://randomuser.me/api/portraits/men/76.jpg",
    "subalternes": ["75e8048c", "8b2d3ac7"],
    "departement": "DSI"
}
```

Mot de passe : 123 en BCrypt
