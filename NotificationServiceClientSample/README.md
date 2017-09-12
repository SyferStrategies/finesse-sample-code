# Cisco Finesse - Notification Service Client Sample
The notification service client sample presents a Java program that has the step by step process to connect to the Cisco Finesse Notification Service and receive the Finesse notifications (XML events). The example program implements the logic to connect to the Finesse Notification Service using the OpenSource XMPP client library [Smack](https://www.igniterealtime.org/projects/smack/) to connect and receive Finesse notifications. Other [Java XMPP libraries](http://xmpp.org/software/libraries.html) are also available. This code has been tested with Finesse 10.5 and Smack 3.4.1.

This sample contains the following files:

    _readme.txt
    SampleNoticicationService.pdf
    SampleXMPPClient.java
    smack-3.4.1.jar
    smackx-3.4.1.jar

## Requirements
1. [XMPP Library](http://xmpp.org/software/libraries.html): [Smack](https://www.igniterealtime.org/projects/smack/) is the XMPP library used to connect to the Notification Service to receive events.

 * smack-3.4.1.jar - Smack is an Open Source XMPP (Jabber) client library for 
instant messaging and presence. This library provides the client side functionality 
as specified in the core XMPP specifications as related to the client side of 
said specifications.
 * smackx-3.4.1.jar - Smack extensions. Classes and methods that implement support 
for the various XMPP XEPs (Multi-User Chat, PubSub, …) and other XMPP extensions

## Usage
In order to run this Finesse Java program, follow the **SampleNotificationService.pdf** documentation for how to modify the program for your Finesse environment.

1. Change the following variables in the Java program for your Finesse environment:
 * hostname
 * password

## Additional Information
##### Finesse REST API
Documentation for the Finesse REST API can be found in the [Finesse Developer Guide](https://developer.cisco.com/site/finesse/docs/#rest-api-dev-guide).

## Disclaimer
This sample code is only a sample and is **NOT guaranteed to be bug free and production quality**.

The sample code is meant to:
- Serve as an example of the step by step process of connecting to the Finesse Notification Service and receive Finesse notifications.
- Provided as a guide for a developer to see how to use a Java XMPP library to receieve the Finesse notifications.

The Finesse sample code is made available to Cisco partners and customers as a convenience to help minimize the cost of Cisco Finesse customizations. Cisco does not permit the use of this library in customer deployments that do not include Cisco Finesse.

## Support Notice
[Support](http://developer.cisco.com/site/devnet/support) for the sample code is provided on a "best effort" basis via DevNet. Like any custom deployment, it is the responsibility of the partner and/or customer to ensure that the customization works correctly and this includes ensuring that the sample code is properly integrated into 3rd party applications.

Cisco Systems, Inc.<br>
[http://www.cisco.com](http://www.cisco.com)<br>
[http://developer.cisco.com/site/finesse](http://developer.cisco.com/site/finesse)