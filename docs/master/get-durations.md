### <span style="color:green">GET</span>  Lister des  Durées

````
BASE_URL/duration/list
````
<br>

# Récupération de la liste des types de données
Ce guide vous aide à comprendre comment récupérer la liste des durées.

## Example de requête

```txt
curl --location 'BASE_URL/duration/list'
```

## Données reçues
L'API renverra une réponse JSON contenant la liste des durées :

## Exemple de Réponse

::: details Corps  

```json
{
    "status": "success",
    "durations": [
        {
            "id": 1,
            "label": "1 Mois",
            "code": "1_MOIS",
            "year": 0,
            "month": 1,
            "day": 0,
            "period": "Mensuelle"
        },
        {
            "id": 2,
            "label": "3 Mois",
            "code": "3_MOIS",
            "year": 0,
            "month": 3,
            "day": 0,
            "period": "Trimestrielle"
        },
        {
            "id": 3,
            "label": "6 Mois",
            "code": "6_MOIS",
            "year": 0,
            "month": 6,
            "day": 0,
            "period": "Semestrielle"
        }
    ]
}
```
:::

::: details En-Têtes (1)
 *Content-Type*    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     application/json
:::
