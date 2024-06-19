# NetSuite -to-excel-online-integration

This repository contains a custom demo built using the MuleSoft Anypoint Platform that shows how to execute a NetSuite Saved Search and insert that data into an Excel worksheet using the [Microsoft Graph REST API v1.0](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0).

This demo was implemented as a point-to-point integration, as the emphasis was to address the following:

1. Leverage the [Anypoint Connector for NetSuite](https://www.mulesoft.com/exchange/com.mulesoft.connectors/mule-netsuite-connector/) to retrieve data from a Saved Search.
2. Clear (not delete or replace) an Excel sheet in Microsoft Office Online using the Microsoft Graph REST API.
3. Insert the NetSuite Saved Search data into the cleared Excel sheet.

The subfolder **postman-collection** contains a basic Postman collection for exploring and working with the Microsoft Graph REST API and Microsoft Excel Online.
