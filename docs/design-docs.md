# Tiny URL Service

## Requirements

- It should be able to generate short urls by giving the long urls
- It should be redirect to the original url by giving the short url
- Deletion of the urls
- Updation of the urls
- expiry on the urls

## Components

- servers
- sequencer
- database: mongoDB because service is more read intensive
- load balancers
- caches
- rate limiter
- base 62 encoder

## APIs

- short the urls
- redirect the url
- delete the url


