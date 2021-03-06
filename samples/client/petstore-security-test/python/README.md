# petstore-api
This spec is mainly for testing Petstore server and contains fake endpoints, models. Please do not use this for any other purpose. Special characters: \" \\  */ ' \" =end --       

This Python package is automatically generated by the [OpenAPI Generator](https://openapi-generator.tech) project:

- API version: 1.0.0 */ &#39; \&quot; &#x3D;end -- \\r\\n \\n \\r
- Package version: 1.0.0
- Build package: org.openapitools.codegen.languages.PythonClientCodegen

## Requirements.

Python 2.7 and 3.4+

## Installation & Usage
### pip install

If the python package is hosted on Github, you can install directly from Github

```sh
pip install git+https://github.com/GIT_USER_ID/GIT_REPO_ID.git
```
(you may need to run `pip` with root permission: `sudo pip install git+https://github.com/GIT_USER_ID/GIT_REPO_ID.git`)

Then import the package:
```python
import petstore_api 
```

### Setuptools

Install via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install --user
```
(or `sudo python setup.py install` to install the package for all users)

Then import the package:
```python
import petstore_api
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```python
from __future__ import print_function
import time
import petstore_api
from petstore_api.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = petstore_api.FakeApi(petstore_api.ApiClient(configuration))
unknown_base_type = petstore_api.UNKNOWN_BASE_TYPE() # UNKNOWN_BASE_TYPE |  (optional)

try:
    # To test code injection */ ' \" =end -- \\r\\n \\n \\r
    api_instance.test_code_inject____end__rn_n_r(unknown_base_type=unknown_base_type)
except ApiException as e:
    print("Exception when calling FakeApi->test_code_inject____end__rn_n_r: %s\n" % e)

```

## Documentation for API Endpoints

All URIs are relative to *http://petstore.swagger.io */ &#39; \&quot; &#x3D;end -- \\r\\n \\n \\r/v2 */ &#39; \&quot; &#x3D;end -- \\r\\n \\n \\r*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*FakeApi* | [**test_code_inject____end__rn_n_r**](docs/FakeApi.md#test_code_inject____end__rn_n_r) | **PUT** /fake | To test code injection */ &#39; \&quot; &#x3D;end -- \\r\\n \\n \\r


## Documentation For Models

 - [ModelReturn](docs/ModelReturn.md)


## Documentation For Authorization


## api_key

- **Type**: API key
- **API key parameter name**: api_key  */ ' " =end -- \r\n \n \r
- **Location**: HTTP header

## petstore_auth

- **Type**: OAuth
- **Flow**: implicit
- **Authorization URL**: http://petstore.swagger.io/api/oauth/dialog
- **Scopes**: 
 - **write:pets**: modify pets in your account  */ ' \" =end -- \\r\\n \\n \\r
 - **read:pets**: read your pets  */ ' \" =end -- \\r\\n \\n \\r


## Author

something@something.abc */ &#39; \&quot; &#x3D;end -- \\r\\n \\n \\r


