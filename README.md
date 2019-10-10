# NaN_event01

Client
```
  id_client   
  nom_client
  email
  numero
  contact_client
```

User
```
  id_user
  nom_user
  prenom_user
  email_user
  contact_user
  #id_commune
```

Participant
````

  #id_user
  #id_event
  
````
Commune
 ```
  id_commune
  nom_commune
```

Categorie
```
  id_categorie
  nom_categorie
```

event_commune
```
  #id_event
  #id_commune
```
event
```
 id_event
 nom_event
 date_debut
 date_fin
 description
 photo
 prix
 #id_client
 #id_user
```

