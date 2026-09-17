# REST API Demo

Using FactoryTalk Optix as REST API Server.

## Description

A REST API server that accepts POST requests with JSON Data 

## Getting Started

### Dependencies

* Newtonsoft.Json 13.0.4



## Sample JSON
A sample JSON string for passing batch parameters
```
{
"Test": {
    "TestRecipe2": {
      "Description": "Test Description",
      "TestParameters": {
        "BATCH_ID": "112",
        "S010_MIXING_SPEED": "FAST",
		"S020_DISCHARGE_TEMP": "22.2"
          }
      }
   }
}
```


## Authors

Contributors names and contact info

OTNetworkGuy

## Version History
* 0.1
    * Initial Release


## Acknowledgments

This project was based on the REST WEB WS Server located at the FactoryTalk Optix Repo.
* [REST_WEB_WS_Server]https://github.com/FactoryTalk-Optix/REST_WEB_WS_Server


## Disclaimer

You acknowledge and agree to accept sole responsibility and liability for any Repository content posted, transmitted, downloaded, or used by you.  There is no obligation to monitor or update Repository content

The examples provided are to be used as a reference for building your own application and should not be used in production as-is. It is recommended to adapt the example for the purpose, observing the highest safety standards.
