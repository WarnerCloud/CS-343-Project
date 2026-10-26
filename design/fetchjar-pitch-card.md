# FetchJar

## Team Members
- Jacob Moore
- Andrew Warner
 - Rawaz Askari

## Description

This app acts as a simple medium for randomness which can be used for simple entertainment or to channel productivity.

We will use various api's that can fetch random data which we will pool into one single collection. Example: https://kinduff.github.io/dog-api/ (random dog facts). We will also have some built-in generators, such as a coin flip or a dice roll. 

This app will create data based on what the app user has randomly collected with the ability for the user to manually save, delete, or potentially export their collection. This data will be stored as an array of collections, each of which contains an array of items:

```
[
    {
        "name": "collection 1",
        "items": [
            {
                "id": "1",
                "format": "text",
                "type": "cat fact",
                "content": "like humans, cats have a paw they prefer.",
                "source": "https://example.com/"
            },
            {
                "id": "2",
                "format": "number",
                "type": "number",
                "content": "31967",
                "source": "https://random.com/"
            }
        ]
    },
    {
        "name": "comics",
        "items": [
            {
                "id": "3",
                "format": "img",
                "type": "comic",
                "content": "https://imgs.xkcd.com/comics/forms_of_water_2x.png",
                "alt": "Forms of Water",
                "source": "https://xkcd.com/3315"
            }
        ]
    }
]
```

## Planned Stretch Goals So Far
- I1. Import & Export
- I8. Second API
- I16. Modules & Classes
- I17. Shareable URLs or S3. Single-Page App Routing
- S6. Accessible Custom Component