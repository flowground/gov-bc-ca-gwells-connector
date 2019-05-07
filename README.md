# ![LOGO](logo.png) Groundwater Wells, Aquifers and Registry **flow**ground Connector

## Description

A generated **flow**ground connector for the Groundwater Wells, Aquifers and Registry API (version v1).

Generated from: https://api.apis.guru/v2/specs/gov.bc.ca/gwells/v1/openapi.json<br/>
Generated at: 2019-05-07T17:42:11+03:00

## API Description

The groundwater wells, aquifers and registry API contains information related to groundwater wells and aquifers as well as a register of qualified well drillers and well pump installers registered to operate in B.C.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### return a list of aquifer demand codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of aquifer material codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of aquifer productivity codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of quality concern codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of aquifer subtype codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of aquifer vulnerability codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of water use codes

*Tags:* `aquifer-codes`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### return a list of aquifers

*Tags:* `aquifers`

#### Input Parameters
* `aquifer_id` - _optional_
* `ordering` - _optional_ - Which field to use when ordering the results.
* `search` - _optional_ - A search term.
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### List all aquifers in a simplified format

*Tags:* `aquifers`

#### Input Parameters
* `search` - _optional_ - A search term.

### return details of aquifers

*Tags:* `aquifers`

#### Input Parameters
* `aquifer_id` - _required_ - A unique integer value identifying this aquifer.

### list files found for the aquifer identified in the uri

*Tags:* `aquifers`

#### Input Parameters
* `aquifer_id` - _required_

### returns a list of cities with a qualified, registered operator (driller or installer)

*Tags:* `cities`

### returns a list of cities with a qualified, registered operator (driller or installer)

*Tags:* `cities`

### serves general configuration

*Tags:* `config`

### Returns a list of all person records

*Tags:* `drillers`

#### Input Parameters
* `search` - _optional_ - A search term.
* `ordering` - _optional_ - Which field to use when ordering the results.
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### Search for a person in the Register

*Tags:* `drillers`

#### Input Parameters
* `search` - _optional_ - A search term.

### list files found for the aquifer identified in the uri

*Tags:* `drillers`

#### Input Parameters
* `person_guid` - _required_

### serves keycloak config

*Tags:* `keycloak`

### Options required for submitting activity report forms

*Tags:* `submissions`

### returns a list of active surveys

*Tags:* `surveys`

### returns a list of wells

*Tags:* `wells`

#### Input Parameters
* `limit` - _optional_ - Number of results to return per page.
* `offset` - _optional_ - The initial index from which to return the results.

### seach for wells by tag or owner

*Tags:* `wells`

#### Input Parameters
* `search` - _optional_ - A search term.
* `ordering` - _optional_ - Which field to use when ordering the results.

### list files found for the well identified in the uri

*Tags:* `wells`

#### Input Parameters
* `tag` - _required_

### Return well detail.<br/>
> This view is open to all, and has no permissions.

*Tags:* `wells`

#### Input Parameters
* `well_tag_number` - _required_ - A unique integer value identifying this well.

## License

**flow**ground :- Telekom iPaaS / gov-bc-ca-gwells-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
