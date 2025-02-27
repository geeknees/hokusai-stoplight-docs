# Issuing an API key

Submit your request for an API key [here](https://0xhokusai.notion.site/Hokusai-API-Application-form-a6d8118d416b41d88632396e3156cddb). You will receive the key, which contains `HOKUSAI_API_KEY` and `HOKUSAI_CONTRACT_ID`. Currently, it takes 2-3 business days to issue the API Key. 

## Authentication
Hokusai authenticates all API requests using API keys. 
To authenticate requests, you should specify the API key in the `key` parameter of the URL query.
Here is an example of a request.
```:bash
https://api.hokusai.app/v1/nfts/{contractAddress}/mint?key={apiKey}
```
All endpoints must include the `key` parameter with the API key.
