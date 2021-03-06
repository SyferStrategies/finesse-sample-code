# Cisco Finesse - Learning Sample Gadget
The learning sample gadget demonstrates how to use the User and Dialog objects. There is step-by-step instructions on how to instantiate the User and Dialog objects, get User and Dialog data, change the user's state, place a call, and create a screenpop in an iframe by building a url using a Dialog's call variable.

![Sample Gadget Screenshot](Screenshot.png)

This sample gadget contains the following files:

	FinesseJavaScriptLibrary/
		readme.txt
	SampleGadget/
		SampleGadget.css
		SampleGadget.js
		SampleGadget.xml
		SampleGadget_Final.css
		SampleGadget_Final.js
		SampleGadget_Final.xml
	_readme.txt
	LearningSampleGadget.pdf

Download the version of the sample gadget that matches the Finesse version. Starting Finesse 11.0(1), sample gadgets will be forward compatible until compatibilty is broken. At that time, a new version of the sample gadget will be published with the starting Finesse version number in the filename.

## Requirements
1. A route point where the logged in agent is assigned to the queue.
2. A value in callVariable3.

## Usage
1. Read the document LearningSampleGadget.pdf for an overview about this sample gadget as well as step-by-step instructions on how to build and upload your gadget.

## Additional Information
##### Finesse REST API
Documentation for the Finesse REST API can be found in the [Finesse Developer Guide](https://developer.cisco.com/site/finesse/docs/#rest-api-dev-guide).

##### Finesse JavaScript Library
Documentation Finesse JavaScript library can be found on [DevNet](https://developer.cisco.com/site/finesse/docs/#javascript-library) and is also located on the Finesse server at the following URL: http(s)://&lt;FQDN&gt;:&lt;port&gt;/desktop/assets/js/doc/index.html

- You can access the JavaScript library at the following URL (starting Finesse 10.6(1)): http(s)://&lt;FQDN&gt;:&lt;port&gt;/desktop/assets/js/finesse.js.

 If you have third-party gadgets, the third-party gadgets can access the JavaScript library at: /desktop/assets/js/finesse.js.

- You can access JQuery at the following URL (starting Finesse 10.6(1)): http(s)://&lt;FQDN&gt;:&lt;port&gt;/desktop/assets/js/jquery.min.js.

 If you have third-party gadgets, the third-party gadgets can access JQuery at: /desktop/assets/js/jquery.min.js.

**For proper functioning of the JavaScript library, you must import both the JavaScript library and JQuery.**

## Disclaimer
This gadget is only a sample and is **NOT guaranteed to be bug free and production quality**.

The sample gadgets are meant to:
- Illustrate how to use the Finesse REST and JavaScript APIs
- Serve as an example of the step by step process of building a gadget using the Finesse JavaScript Library
- Provided as a guide for a developer to see how to initialize a gadget and set up handlers for user and dialog updates.

The Finesse JavaScript library and the sample gadget are made available to Cisco partners and customers as a convenience to help minimize the cost of Cisco Finesse customizations. Cisco does not permit the use of this library in customer deployments that do not include Cisco Finesse.

## Support Notice
[Support](http://developer.cisco.com/site/devnet/support) for the JavaScript library is provided on a "best effort" basis via DevNet. Like any custom deployment, it is the responsibility of the partner and/or customer to ensure that the customization works correctly and this includes ensuring that the Cisco Finesse JavaScript is properly integrated into 3rd party applications. Cisco reserves the right to make changes to the JavaScript code and corresponding API as part of the normal Cisco Finesse release cycle.

It is Cisco's intention to ensure JavaScript compatibility across versions as much as possible and Cisco will make every effort to clearly document any differences in the JavaScript across versions in the event that a backwards compatibility impacting change is made.

Cisco Systems, Inc.<br>
[http://www.cisco.com](http://www.cisco.com)<br>
[http://developer.cisco.com/site/finesse](http://developer.cisco.com/site/finesse)