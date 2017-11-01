#Magento2 Province Italiane

Questo modulo installa le province italiane in Magento2


##Installazione tramite composer:
 aggiungere la riga seguente al composer del proprio progetto:
 
```
composer require vmasciotta/magento2-province-italiane
```
 
 eseguire quindi all'interno della root di magento i seguenti comandi:

```
$ ./bin/magento cache:disable
$ ./bin/magento module:enable Vmasciotta_ProvinceItaliane
$ ./bin/magento setup:upgrade
$ ./bin/magento cache:enable
```
