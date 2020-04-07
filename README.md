# Humansis API Postman collection

Postman Collection demonstrating how to use the [Humansis](https://www.humansis.org) REST API.
More information about the API can be found on [Swagger](https://api-demo.humansis.org/swg/doc).

## Installation

Download the collection file from this repo, then import directly into Postman. Also download associated environments for Humansis platform.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *name* To use our API, you must have an username in format of valid email address with Rest API permissions.
- *password* Also password for is mandatory


## Usage

The collection is arranged in folders according to the API endpoints.

Almost all requests require a valid X-WSSE header.  The collection requests have a shared pre-request script, which generate this header from username and password.

More information on managing Postman environments and variables can be found [here](https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables).

|Variable       |Default value               |Set in         |May override in  |Example            |
|---------------|----------------------------|---------------|-----------------|-------------------|
|`wsse_user` 	|-                           |Environment    |Environment      |`user@domain.org`  |
|`wsse_password`|- 				       	     |Environment    |Environment      |`myPassword`       |

### Contribute

We welcome your contributions!  


## See Also

[Humansis API documentation](https://api-demo.humansis.org/swg/doc)

[Postman API development tool](https://www.getpostman.com/)