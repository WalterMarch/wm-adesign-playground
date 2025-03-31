# GET and POST API Requests

Write a program that makes a GET request (`https://ok.surf/api/v1/news-section-names`) and then uses one of the responses in a POST request.

Use [OkSurf News API](https://ok.surf/), for example.

## Get News Section Names

```json
"request": {
    "url": "https://ok.surf/api/v1/news-section-names",
    "method": "GET",
    "body": null
}
```

```json
"response": {
    "data": [
        "US",
        "World",
        "Business",
        "Technology",
        "Entertainment",
        "Sports",
        "Science",
        "Health"
    ]
}
```

## Post to retrieve news items

```json
"request": {
    "url": "https://ok.surf/api/v1/news-section",
    "method": "POST",
    "body": "{\"sections\":[\"Technology\"]}"
}
```

```jsonc
"response": {
    "data": [
        {
            "link": "https://news.google.com/read/CBMikwFBVV95cUxPNDgzN1FlRnU2ZUIybTlDV1E2Nk5kMEVLczhBWk5ybjBxVVBZV1JLeFh6X2NIN3VtelF6ekZQZi1CUk5vQjF4Zzk0TG9nUWdpVWcwMV9mbDZJa3hCRmdFSWoxYjZQcC1IOTU2T2ZZMEg0dm1Zbk5hNnNKOFdsaTBacDZiWm9vM2R4U1ZSSDF3OUg4ODA?hl=en-US&gl=US&ceid=US%3Aen",
            "og": "https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcSgX5I0NislYSkRmkus9qxHsh1exv-EdDCN0sH7D2iHvc48KCV_SyexoJkcZXq8JWZIwqg&fopt=w560-h336-rw-dcEUOQh66na2gC",
            "source": "Ars Technica",
            "source_icon": "https://encrypted-tbn0.gstatic.com/faviconV2?url=https://arstechnica.com&client=NEWS_360&size=96&type=FAVICON&fallback_opts=TYPE,SIZE,URL",
            "title": "The 8 most interesting PC monitors from CES 2025"
        }
        // many more article objects
    ]
}
```

## Implementations

Most of the completed implementations of this project are amateurish hacks (because that's what I am in most of these languages) and probably shouldn't be used in production.

* [C#](https://github.com/WalterMarch/wm-csharp-playground/tree/main/apiRequests)
* [Java](https://github.com/WalterMarch/wm-java-playground/tree/main/apiRequests)
* [JavaScript](https://github.com/WalterMarch/wm-javascript-playground/tree/main/apiRequests)
* Kotlin - need to learn about Maven for Kotlin first
* Pascal
* Perl
* Python
* Scala
* TypeScript
