Open Advertising Protocol Schemas
=======================

This where we store the schemas of the models for the Open Advertising Protocol. Although the schemas 
are represented in XML Schemas, the Open Advertising Protocol is intented to support both XML and JSON. 

Unless you're a nerd genius, you're going to have some trouble making sense of the XSD files. These are
[XML Schema Definition](http://en.wikipedia.org/wiki/XML_Schema_%28W3C%29) files. Instead of viewing here,
clone the repository to your local hard drive and view the schema through a visual [XML Schema editor](http://en.wikipedia.org/wiki/XML_Schema_Editor) 
such as [XML Spy](http://www.altova.com/xmlspy.html) (30-day free trial available) or one of
many [other XML schema editors](http://en.wikipedia.org/wiki/XML_Schema_Editor#XML_Schema_Editors).

A lot of this will be self-explanatory. However, to better understand these XSD's, you'll want to understand XML Schemas.  There's an excellent
[XML Schema online course](http://altova-aot.s3.amazonaws.com/Altova%20XML%20Schema%201.1%20Technology/player.html) on the Altova website.

Overview
-------------
The main schemas are:

1. [Program](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/program.xsd) - describes an advertising program, such as a website's advertising options
2. [Order](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/order.xsd) - an insertion order for buying inventory from a [Program](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/program.xsd)
3. Invoice - (coming soon) an invoice related to an [Order](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/order.xsd)

Supporting schemas:

1. [Common](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/common.xsd) - a collection of common data types such as Person, Company, Email Address, Money, etc.
2. [Currency Code](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/currencyCode.xsd) - this is really an extention of [Common](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/common.xsd), but the list of currency codes was so long we stuck it in a separate file. There's also a handy [Currency Code Spreadsheet](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/currencyCodes.xlsx?raw=true) to help navigate the codes.
3. [Media Type]() - this is really an extention of [Program](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/program.xsd), but the list of media types was so long we stuck it in a separate file. There's also a handy [Media Type Spreadsheet](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/model/schemas/mediaTypes.xlsx?raw=true) to help navigate the codes, with the most common types highlighted.





