
### <span style="color:yellow">PUT</span> Générer le fichier JSON d'une branche

````
BASE_URL/branch/generate
````

## Méthode

- `PUT`

## EN-TÊTES

| Authorization | Bearer TOKEN |
| ------------- | ----------- |

## Exemple de Requête

```curl
curl --location BASE_URL/branch/generate' \
--header 'Authorization: Bearer TOKEN'
```

## Exemple de Réponse

::: details Corps  

```json
{
    "status": "success"
}
```

:::
