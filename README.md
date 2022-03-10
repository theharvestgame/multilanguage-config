# the harvest game multilanguage-config

```
/en -> English
/es -> Spanish
/pt -> Portuguese
```
Also you can access to marketplace using domain.com/en/marketplace or domain.com/es/marketplace and among others langs

The langs supported are in next i18n config file in the root of the app: locales: ['en', 'es', 'pt']
The default lang is en
so domain.com without prefix should be show the site in English

The json files with contains lang tokens are in public/locales/${lang}

home_${section}.json is the file that contain the tokens for the home page
marketplace_${section}.json is the file that contain the tokens for the marketplace page

We should add a new files for each new page in the site using the following format: ${page}_${section}.json
Is not required but is a easier way to handle langs in the future
