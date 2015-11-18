#Magento2 Province Italiane

Questo modulo installa le province italiane in Magento2


##Installazione tramite composer:
 aggiungere la riga seguente al composer del proprio progetto:
 
```
...
"require":{
    ...
    "vmasciotta/magento2-province-italiane":"1.0.0"
 },
 ...
 "repositories":[
     {"type": "vcs", "url":"git@github.com:vmasciotta/magento2-province-italianegit"}
 ]
```
 
 esegure quindi all'interno della root di magento i seguenti comandi:

```
$ composer update
$ ./bin/magento cache:disable
$ ./bin/magento module:enable Vmasciotta_ProvinceItaliane
$ ./bin/magento setup:upgrade
$ ./bin/magento cache:enable
```