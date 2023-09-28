# Semantic-Search API

## Description:
The Semantic Search API is a powerful tool that allow developers to perform advanced searches based on the meaning or context of a query rather than just keyword matching. It leverages semantic analysis and natural language processing techniques to understand the intent behind a search and provide more relevant results.

## Key Features:

### Semantic Understanding:
The API employs sophisticated algorithms to analyze the meaning of a query. This means it can recognize synonyms, related concepts, and contextual nuances, leading to more accurate search results.

### Contextual Relevance:
Unlike traditional keyword-based searches, which may return results based on exact matches, this API considers the context of the query. It understands the relationships between words and identifies relevant information even if the exact keywords are not present.

## Use Cases:

### E-Commerce Search:
Enhance product search by understanding customer intent and returning more relevant results, even when they don't use exact product names.

### Content Discovery:
Improve content recommendation systems by considering the meaning and context of user queries.

### Customer Support Chatbots:
Enable chatbots to understand user inquiries in a more natural and contextually accurate manner.

## How to Use:

### Make a POST Request:
Send a POST request to the API endpoint with the query you want to perform a semantic search on.

#### API Endpoint - https://chattesting.virtualforce.io/semantic-search

### Query/Request Body: 
```
{
    "query":"black shirt"
}
```

### Receive JSON Response:
The API will process the query and return a JSON response containing the most relevant results.
```
{"status": "ok", "data": ["7237635408022", "7740064006294", "7237635309718", "6797623427222", "7777050525846",
"7505372414102", "7505372545174", "7043935862934", "7240843919510", "7490273443990", "7208239726742", "7385454149782",
"6982733725846", "6982724976790", "7527809843350", "6604265521302", "7240841658518", "6604265390230", "6982733496470",
"7505372840086", "7382709797014", "6982741000342", "7240841298070", "7721462726806", "6982732185750", "7586612641942",
"7160756830358", "6982746144918", "6604265160854", "6999788257430"]}
```
