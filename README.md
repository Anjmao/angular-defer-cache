# About
Angular service to cache things like http requests, resources and custom defers which returns promise

## Example
```javascript
this.deferCacheService.getDeferred('cacke.key1', () => this.myApiResource.getAllItems().$promise);
```

## Dev setup
1. `git clone https://github.com/Anjmao/angular-defer-cache.git`
2. `npm install`
3. If you use vs code, simply click `ctrl+shift+b` to compile typescript files
4. To run tests type `karma start`

## Installation
Just grab compiled defer-cache-service.js from src and you a good to go. If you use Typescript, then  you would like to take defer-cache-service.ts and IDeferCacheService.ts

## Usage
See spec/** for unit tests and demo/** for real usage
