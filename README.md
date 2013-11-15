Open Advertising Protocol
=======================

The Open Advertising Protocol defines the standards for electronically buying and selling advertising inventory.
Although the initial application is in digital advertising, it has potential application in offline advertising as well.

Overview
--------

For a high-level view of the protocol, see the [Open Advertising Protocol Diagram (PDF)](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/Programmatic-Direct-Open-Advertising-Protocol.pdf?raw=true).
In reviewing the diagram, you'll notice there are two sides to the protocol: (1) a buy side and (2) a sell side. 
Each side has it's own API. 

### Buyer API

The [OAP Buyer API](http://docs.oapbuyer.apiary.io/) is the interface sellers use to connect with buyers. Sellers can use this to 
publish information about their advertising programs in the buyer's system. They can use it to download orders and
to update the status of those orders.

### Seller API

The [OAP Seller API](http://docs.oapsellerapi.apiary.io/) is the interface buyers use to connect with sellers. Buyers can use this
to get up-to-the-minute information on advertising programs, inventory, and pricing. Buyers can use it to place orders
witn the seller, to modify orders, and to get current status of orders.

### Model

The [OAP Model](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/tree/master/model) describes the
electronic documents that are passed back and forth between buyers and sellers such as insertion orders. The model
is described using XML Schema Language because of its expressiveness and widespread availability of tools to work with
XML schemas. Beyond obvious application with XML documents, the model is also intented to represent JSON documents.

Status
------

As of November 15, 2013, the OAP is still very early stage.  The plan is to finalize the minimum viable product 
protocol (as shown in the [overview diagram](https://github.com/OpenAdvertisingProtocol/OpenAdvertisingProtocol/blob/master/Programmatic-Direct-Open-Advertising-Protocol.pdf?raw=true)) 
December 2014 and to complete initial reference implementations in February 2014.

Beyond that, we plan to complete the invoice and other parts of the protocol in stages.


Participating Companies
----------------------

* [Adslot](http://www.adslot.com/)
* [Bionic Advertising Systems](http://www.bionic-ads.com/)
* [iSocket](https://www.isocket.com/)
* [Operative](http://www.operative.com/)
* [Yieldex](http://www.yieldex.com/)
