Open Advertising Protocol Schemas
=======================

This where we store the schemas of the models for the Open Advertising Protocol. Although the schemas 
are represented in XML Schemas, the Open Advertising Protocol is intented to support both XML and JSON. 

Overview
-------------
The Open Advertising Protocol includes the key documents involved in the [42-step process](http://www.bionic-ads.com/workflow) of ordering advertising inventory. The six main schemas are:

1. [Program](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/program.xsd) - describes an advertising program and defines the adverting `Product`s sold through the program. For example, Yahoo Finance is a program and the advertising placements you can buy are its products.
2. [RFP](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/rfp.xsd) - represents a request from a buyer for a proposal from the seller
3. [Proposal](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/proposal.xsd) - represents a proposal from the seller to a buyer, often in response to an `RFP`
4. [Order](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/order.xsd) - an insertion order for buying inventory from a seller. Includes line items of `Placement`s and `Package`s referencing the  `Program`'s `Product`s
3. [Invoice](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/invoice.xsd) - an invoice related to an `Order`
4. [Payment](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/payment.xsd) - a payment on an `Invoice`

Supporting schemas:

1. [Common](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/common.xsd) - a collection of common data types such as Person, Company, Email Address, Money, etc.
2. [Currency Code](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/currencyCode.xsd) - this is really an extention of [Common](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/common.xsd), but the list of currency codes was so long we stuck it in a separate file. There's also a handy [Currency Code Spreadsheet](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/currencyCodes.xlsx?raw=true) to help navigate the codes.
3. [Media Type]() - this is really an extention of [Program](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/program.xsd), but the list of media types was so long we stuck it in a separate file. There's also a handy [Media Type Spreadsheet](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/mediaTypes.xlsx?raw=true) to help navigate the codes, with the most common types highlighted.


How to review the OAP Schemas
------------------------
Unless you're a nerd genius, you're going to have some trouble making sense of the XSD files. These are
[XML Schema Definition](http://en.wikipedia.org/wiki/XML_Schema_%28W3C%29) files. Instead of viewing here,
clone the repository to your local hard drive and view the schema through a visual [XML Schema editor](http://en.wikipedia.org/wiki/XML_Schema_Editor).

Recommended steps:

1. Install a github client if you don’t already have one (e.g. [github for windows](http://windows.github.com/))
2. Download the [Open Advertising Protocol](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol) from github to your local hard drive
3. Install an XML schema editor if you don't already have one. For windows, I recommend [XML Spy **professional edition**](http://www.altova.com/download_current.html# ). A 30-day free trial available. Be sure to get the **professional** edition of **XML Spy** (not mission kit or the enterprise version - Don’t make the same mistake that I did and get the free trial of enterprise because it’s much more expensive at the end of the trial and you don’t need it for this). Many [other XML schema editors](http://en.wikipedia.org/wiki/XML_Schema_Editor#XML_Schema_Editors) are available.
4. Use XML Spy to review the OAP schemas with particular attention to `order.xsd` which is the lynchpin

A lot of this will be self-explanatory. However, to better understand these XSD's, you'll want to understand XML Schemas.  There's an excellent
[XML Schema online course](http://altova-aot.s3.amazonaws.com/Altova%20XML%20Schema%201.1%20Technology/player.html) on the Altova website.



