## Radweb_Core for Magento 2

Core module for Radweb modules.

## Install

### Composer

1. cd to root folder

2. Enter following commands to install module:

    ```bash
    composer require radweb/core
    ```
    
3. Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```bash
    php bin/magento module:enable Radweb_Core --clear-static-content
    php bin/magento setup:upgrade 
    php bin/magento setup:di:compile
    php bin/magento cache:flush
    php bin/magento indexer:reindex
    ```

## Release Notes

1.0.0 

- Initial
