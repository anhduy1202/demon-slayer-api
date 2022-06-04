# Demon Slayer API
> A simple web-scraped API for Demon Slayer fans 
> 
> Web scraped from https://kimetsu-no-yaiba.fandom.com

![tanjiro](https://user-images.githubusercontent.com/58461444/171970590-61e55510-c891-4509-aefc-1e8136ca9ee8.gif)

## Endpoints:

### Get All Characters

```GET https://demon-slayer-api.onrender.com/v1/``` 

> Query limit: ```GET https://demon-slayer-api.onrender.com/v1?limit=5``` 

| Keys  | Type |
| ------------- | ------------- |
| name  | String  |
| url  | String  |
| image | String |

### Get One Character
```GET https://demon-slayer-api.onrender.com/v1/Tanjiro_Kamado```

| Keys  | Type |
| ------------- | ------------- |
| name  | String  |
| gallery  | [String]  |
| image | String |
| race | String |
| gender | String |
| age | String |
| height | String |
| weight | String |
| birthday | String |
| hair color | String |
| eye color | String |
| affiliation | String |
| occupation | String |
| combat style | String |
| partner(s) | String |
| status | String |
| relative(s) | String |
| manga debut | String |
| anime debut | String |
| japanese va | String | 
| english va | String |
| stage play | String |
