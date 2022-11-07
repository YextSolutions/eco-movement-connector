##### eco-movement-connector

# Product Description & Purpose

Eco-movement, a data aggregator, is the leading platform for electric vehicle charge point data. Yext is partnering with Eco-Movement for our first EV solution. We will be creating a comprehensive integration with Eco-movement that will loop data— a) pull EV data from Eco-movement to Yext  b) send enriched fields from Yext to Eco-movement.
This repository contains the app for part a) pulling data from Eco-Movement to add to Yext location entities, this includes EVSE, Connector, energy source data and more.



This app creates the following custom connectors:	

- ecomovement\_locationConnector

This app uses the built-in Location entity type and adds the following custom Eco-Movement fields to the entity type:	

- ecomovement\_accessType
- ecomovement\_brandDetails
- ecomovement\_chargingBehavior
- ecomovement\_chargingWhenClosed
- ecomovement\_eVSE1
- ecomovement\_eVSE2
- ecomovement\_eVSE3
- ecomovement\_energyProduct
- ecomovement\_energySupplier
- ecomovement\_greenEnergy
- ecomovement\_locationTypeDetails
- ecomovement\_nearbyFacilities
- ecomovement\_operatorDetails
- ecomovement\_ownerDetails
- ecomovement\_relabilityScore
- ecomovement\_suboperatorDetails

This app also creates custom field types that are used as fields above:	
- ecomovement\_connectorData
- ecomovement\_eVSEData
- ecomovement\_operatorDetails
- ecomovement\_typeDesc


# Requirements

To use this app you will need to have the following before you install:

- Generated and have access to your Eco-Movement bearer token
- ##### \*If you have existing Yext Location entities your entity IDs  MUST MATCH between Yext and Eco-Movement for the connector to update entities as designed.

Follow the step-by-step instructions below to install the Eco-Movement EV Location Connector app.

# How to Install

If you are an existing Yext customer, you can install the  Eco-Movement EV Location Connector here <https://www.yext.com/s/me/apps/tbd

If you are currently using a Yext sandbox account, you can install the Eco-Movement EV Location Connector here <https://sandbox.yext.com/s/me/apps/tbd>.

If you are not an existing customer, but interested in learning more, try out a free trial here for a production account, or sign up for Hitchhikers and get started with a sandbox account, here <https://hitchhikers.yext.com/>. 

Install the connector to begin pulling in your Eco-Movement data into your Knowledge Graph! 


### To install the Eco-Movement EV Location Connector:

1. Click the Install button.
2. Provide your Eco-Movement bearer access token.
3. Enter your brand name to be used for the name of your locations.
3. Authorize the changes to your account and click Submit.

Once the app is installed you will be directed to the Connectors page where you will manually run the connector.
You can make any custom changes to your connector based on your use case before running. These customizations may include mapping the address field, changing the location names, or adding more EVSEs or Connectors per location.

Once you have manually run the connector you are finished! The connector will run once per day, keeping all EV charging information up to date. 





