## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Thu Mar 06 2025 07:49:39 GMT+1100 (Australian Eastern Daylight Time)|
|**App Generator**<br>@sap/generator-fiori-freestyle|
|**App Generator Version**<br>1.16.5|
|**Generation Platform**<br>Visual Studio Code|
|**Template Used**<br>simple|
|**Service Type**<br>None|
|**Service URL**<br>N/A|
|**Module Name**<br>project1|
|**Application Title**<br>App Title|
|**Namespace**<br>|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.133.0|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|

## project1

An SAP Fiori application.

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```
    npm start
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)


### Notes

- The original url was src="resources/sap-ui-core.js" in index.html. This works only when run locally or deploy to SAP BTP. If we deploy to a non-SAP platform like Netlify it won't work even if we add the proxy in ui5.yaml. Because that file is not recognised by non-SAP plaforms. So one work around is to change the url to full url like this - src="https://ui5.sap.com/resources/sap-ui-core.js".Another way is to create a redirects file.