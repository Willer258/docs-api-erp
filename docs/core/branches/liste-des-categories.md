
### <span style="color:green">GET</span> Liste complète des catégories de branche

````
BASE_URL/branch/category/list
````

## EN-TÊTES

| Authorization | Bearer TOKEN |
| ------------- | ----------- |

## Exemple de Requête

```curl
curl --location BASE_URL/branch/category/list' \
--header 'Authorization: Bearer TOKEN'
```

## Exemple de Réponse

::: details Corps  

```json
{
    "status": "success",
    "categories": [
        // Liste des catégories de branche
    ]
}
```

:::
