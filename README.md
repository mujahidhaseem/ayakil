# Mage2 Module Eight25media OrdersModification

    ``eight25media/module-ordersmodification``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities


## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Eight25media`
 - Enable the module by running `php bin/magento module:enable Eight25media_OrdersModification`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require eight25media/module-ordersmodification`
 - enable the module by running `php bin/magento module:enable Eight25media_OrdersModification`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration




## Specifications

 - Helper
	- Eight25media\OrdersModification\Helper\ModifyOrders

 - Observer
	- sales_order_save_after > Eight25media\OrdersModification\Observer\Sales\OrderSaveAfter


## Attributes

 - Sales - Need Promise Date (need_promise_date)

 - Sales - Vendor Order Number (vendor_order_number)

 - Sales - Dropship available (dropship_available)

