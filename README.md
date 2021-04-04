# Magelearn_RestrictPayment
Disable specific payment methods on checkout page when cart have at least one product from specific category.

### Screenshots

#### Cash on delivery method will display before added module
[![Checkout-1.png](https://i.postimg.cc/ZnLKVsmx/Checkout-1.png)](https://postimg.cc/64yXQ0y8)

#### After adding module cashondelivery method will not display
[![Checkout.png](https://i.postimg.cc/RC1FShtJ/Checkout.png)](https://postimg.cc/dD1vnq4J)

## Installation

### Using Composer (Recommended)
 - Install the module composer by running `composer require magelearn/module-restrictpayment`
 - Enable the module by running `php bin/magento module:enable Magelearn_RestrictPayment`
 - apply database updates by running `php bin/magento setup:upgrade`
 - Flush the cache by running `php bin/magento cache:flush`

### Manual File Transfer
- Clone or unzip this repository to `app/code/Magelearn/RestrictPayment`
- Enable the module by running `php bin/magento module:enable Magelearn_RestrictPayment`
- Apply database updates by running `php bin/magento setup:upgrade`
- Flush the cache by running `php bin/magento cache:flush`

## Configuration

### How to Configure

### Settings Explanation

## Compatibility
This module has been tested and validated to work on Magento versions 2.3 to 2.4.2.

## Bugs & Issues
If you find a bug or issue please create a new issue [here](https://github.com/vijayrami/Magelearn_FreeShippingProgressBar/issues) and include as much detail and context as possible including screenshots.

## License
This module is licensed under the Open Software License V3.0 which you can refer to [here](LICENSE.txt).
