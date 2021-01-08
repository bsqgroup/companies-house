# Companies House

**A library for interaction with Companies House**

'Companies House' is the United Kingdom's registrar of companies and is an executive agency and trading fund of Her Majesty's Government. It falls under the remit of the Department for Business, Energy and Industrial Strategy and is also a member of the Public Data Group.

This library interacts with the Companies House XML Gateway which offers electronic access to a core range of company information from Companies House Databases. The Companies House XML Gateway is accessible online over the internet by authorised XML Gateway customers. Data and documents are requested and delivered using XML (Extensible Markup Language). Customers must use standard XML data schemas as defined in the Interface Specification.

## Installation

The library can be installed via [Composer](http://getcomposer.org/). To install, simply add
it to your `composer.json` file:

```json
{
    "require": {
        "bsqgroup/companies-house": "0.*"
    }
}
```

And run composer to update your dependencies:

$ curl -s http://getcomposer.org/installer | php
$ php composer.phar update