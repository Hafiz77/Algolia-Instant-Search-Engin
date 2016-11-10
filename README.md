Instant-Search Demo
====================

This is a sample project implementing an instant-search based e-commerce website with [Algolia](http://www.algolia.com). Algolia is a Search API that provides hosted full-text, numerical and faceted search.


## Features
* Full-JavaScript/frontend implementation based on [instantsearch.js](https://community.algolia.com/instantsearch.js/)
* Results page refreshed as you type
* Hits
* Facets
* Pagination
* Relevant results from the first keystroke
* Typo-tolerance
* Multiple sort orders
* By Relevance
* By Highest Price
* By Lowest Price
* Backup search parameters in the URL



Then, you'll need to replace the demo credentials with your own:
- in ```js/app.js```, set your own ```APPLICATION_ID``` instead of ```"1952FGB3FT"``` (which is our demo ```APPLICATION_ID```),
- in ```js/app.js```, set your own ```SEARCH_ONLY_API_KEY``` instead of ```"451273d1ca2d987eeda80e9aa31b1e55"```,
- in ```js/app.js```, set your own ```index``` name instead of ```"instant_search"```.


## Tutorial

**Follow this [step by step tutorial](https://www.algolia.com/doc/tutorials/instant-search#) (on Algolia.com) to learn how this implementation works** and how it has been built using the [Algolia's Javascript API client](https://github.com/algolia/algoliasearch-client-js) and its [helper](https://github.com/algolia/algoliasearch-helper-js).


## Run and develop locally

To hack and develop on this current repository:

```sh
$ git clone https://github.com/Hafiz77/Algolia-Instant-Search-Engin.git
$ npm install
$ npm run dev
```
