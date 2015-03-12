# python-proliant-sdk
This repository will be used to house the Python ProLiant SDK.  This SDK will be used to help Python developers communicate with the [HP ProLiant REST API](http://hp.com/go/restfulapi).

## Directory Structure
- **docs**  -   Links to documents discussing the HP RESTful API
- **samples**  -  Examples of routine server maintenance using the HP RESTful API

## Requirements
To use the enclosed examples, you will need [Python 2.7](https://www.python.org/downloads/), and a ProLiant server running iLO 4 with network access  to the iLO network port.  Note that Python 2.7.9 enforces greater SSL verification requiring server certificates be installed.  Parameters to relax the requirements are available in the sample scripts, but these configurations are discouraged due to security concerns.

--test--
