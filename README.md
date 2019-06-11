# ![LOGO](logo.png) DropX **flow**ground Connector

## Description

A generated **flow**ground connector for the DropX API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/dropx.io/1.0.0/swagger.json<br/>
Generated at: 2019-06-06T16:12:12+03:00

## API Description

dropX.io API provides programmatic access to the e-commerce intelligence data.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Get product details by providing the product IDs

> Returns product details

*Tags:* `Product Details`

#### Input Parameters
* `pids` - _required_ - search array of ids

### Search for similar products by providing a link to any e-commerce product.

> Returns list of e-commerce product that are close to the one provided -- one from each provider

*Tags:* `LookUp`

#### Input Parameters
* `url` - _required_ - URL must be a url encoded value
* `providers` - _optional_ - A valid e commerce website link(eg. www.flipkart.com or http://www.amazon.in) by a ',' seperated values to filter response by required e-commerce providers

### Search for similar products by providing a link to any e-commerce product.

> Returns list of e-commerce product that are close to the one provided -- one from each provider

*Tags:* `LookUp`

#### Input Parameters
* `url` - _required_ - URL must be a url encoded value
* `providers` - _optional_ - A valid e commerce website link(eg. www.flipkart.com or http://www.amazon.in) by a ',' seperated values to filter response by required e-commerce providers

### Search for any product using title

> Returns one unique result from every provider that dropx.io tracks

*Tags:* `LookUp`

#### Input Parameters
* `term` - _required_ - search terms giving any title of products that are sold online
* `providers` - _optional_ - A valid e commerce website link(eg. www.flipkart.com or http://www.amazon.in) by a ',' seperated values to filter response by required e-commerce providers

### Search for any product using title

> Returns one unique result from every provider that dropx.io tracks

*Tags:* `LookUp`

#### Input Parameters
* `term` - _required_ - search terms giving any title of products that are sold online
* `providers` - _optional_ - A valid e commerce website link(eg. www.flipkart.com or http://www.amazon.in) by a ',' seperated values to filter response by required e-commerce providers

### Search for any product using title

> Returns list of product ids

*Tags:* `LookUp`

#### Input Parameters
* `term` - _required_ - search terms giving any title of products that are sold online

### Get API usuage details

> Returns API request consumption details.

*Tags:* `Monitor`

## License

**flow**ground :- Telekom iPaaS / dropx-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
