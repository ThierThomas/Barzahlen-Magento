# Barzahlen Payment Module (Magento)

## User Manual
DE - https://integration.barzahlen.de/de/shopsysteme/magento/nutzerhandbuch
EN - https://integration.barzahlen.de/en/shopsystems/magento/user-manual

## Current Version
1.3.5

## Changelog

### 1.3.5 (06.08.2015)
* adaptions for recent Magento patches
  * SUPEE-5994 which introduces strict check for admin controllers
  * SUPEE-6285 by adding _isAllowed() check

### 1.3.4 (11.06.2015)
* improved payment selection
* updated to Barzahlen PHP SDK v1.1.8

### 1.3.3 (24.02.2015)
* showing credit memo button only within invoice
* improved error messages

### 1.3.2 (18.12.2014)
* intern version number correction for Magento Connect

### 1.3.1 (18.12.2014)
* bugfix to allow older transaction to expire on callback

### 1.3.0 (19.11.2014)
* integrated Barzahlen transactions better with Magento transactions
* avoiding overwriting other buttons in adminhtml/sales_order_view
* improved payment selection and api communication
* updated Barzahlen API PHP SDK

### 1.2.1 (25.06.2013)
* fixed automatic version check for multi store installations

### 1.2.0 (25.04.2013)
* implemented automatic plugin version check (weekly)
* using PSR2 coding standard

### 1.1.9 (10.04.2013)
* updated Barzahlen API PHP SDK
* added automatic payment slip cancelation together with order cancelation

### 1.1.8 (02.04.2013)
* enabled backend orders with Barzahlen

### 1.1.7 (28.03.2013)
* improved email sending

### 1.1.6 (27.03.2013)
* avoiding rounding mistakes in amounts
* added automatic email notification for paid / expire

### 1.1.5 (12.03.2013)
* enabled all settings for store views

### 1.1.4 (11.03.2013)
* changed image urls to make use of https
* updated cURL certificate bundle

### 1.1.3 (04.03.2013)
* avoid Barzahlen_Exception during other payment methods offline refunds

### 1.1.2 (19.02.2013)
* added automatic iso conversion for payment requests

### 1.1.1 (29.01.2013)
* redesigned payment selection and checkout success page

### 1.1.0 (31.10.2012)
* implemented new api geocoding feature to get the closest points of sales
* reduced the maximum amount to 999.99 Euros
* small changes in the language files

### 1.0.0 (26.09.2012)
* initial release

## Support
The Barzahlen Team will happily assist you with any problems or questions. Send us an email to support@barzahlen.de or use the contact form at https://integration.barzahlen.de/en/support.

## Copyright
(c) 2015, Cash Payment Solutions GmbH
https://www.barzahlen.de

## NOTICE OF LICENSE
This source file is subject to the Open Software License (OSL 3.0) that is bundled with this package in the file LICENSE.txt.

It is also available through the world-wide-web at this URL: http://opensource.org/licenses/osl-3.0.php

If you did not receive a copy of the license and are unable to obtain it through the world-wide-web, please send an email to info@barzahlen.de so we can send you a copy immediately.
