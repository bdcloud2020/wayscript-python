# [<img src="https://user-images.githubusercontent.com/31461850/53454621-a1b39500-39dc-11e9-9b3c-276451d42437.png" width="155px" alt="WayScript" align="center">](https://wayscript.com) Python SDK

### A new way to build software.

* WayScript gives you flexible building blocks to seamlessly integrate, automate and host tools in the cloud. Unlock new potential with drag and drop programming.

* Instantly connect to hundreds of datasets including GitHub, Twitter, databases, ecommerce data, or build your own integration. WayScript can read data from Excel, Google Sheets, and an evergrowing list of third-party APIs.

* Seamlessly migrate to the cloud: Generate interfaces, instantly share, and run via event-based triggering. 

## Installation

```sh
pip install wayscript
```

## Basic Usage

1. Get the API Key from your WayScript user profile page

2. Run your WayScript programs from your Python code:

```python
import wayscript

api_key = 'YOUR_API_KEY'

wayscript = wayscript.authorize( api_key )

# Run a program by id
program_id = 1234
wayscript.run( program_id )

# Pass variables to a program
variables = [ 'one', 'two', 'three' ]
wayscript.run( program_id, variables )
```
