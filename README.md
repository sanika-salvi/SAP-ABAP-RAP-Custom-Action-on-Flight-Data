# SAP-ABAP-RAP-Custom-Action-on-Flight-Data
This project demonstrates the implementation of a custom action using the RESTful ABAP Programming Model (RAP) in an SAP ABAP Cloud practice environment.  The application uses the standard /DMO/FLIGHT data source and displays flight information through a Fiori elements application.


Technologies Used
- SAP ABAP Cloud
- Eclipse ADT
- Core Data Services (CDS)
- RESTful ABAP Programming Model (RAP)
- Behavior Definition and Behavior Implementation
- OData V4
- SAP Fiori Elements

- 
Development Objects
- CDS Data Definition: ZR_FLIGHT_ACTION
- Behavior Definition: ZR_FLIGHT_ACTION
- Behavior Pool: ZBP_R_FLIGHT_ACTION
- Custom RAP Action: ShowFlightInfo
- Service Definition: ZUI_FLIGHT_ACTION
- Service Binding: ZUI_FLIGHT_ACTION_O4
- Data Source: /DMO/FLIGHT

- 
Features
- Displays flight records using CDS.
- Implements an unmanaged RAP behavior.
- Creates a custom ShowFlightInfo action.
- Exposes the action through a Fiori elements application.
- Retrieves selected flight information.
- Displays a success message after execution.

- Implementing local handler methods.
- Exposing RAP services using OData V4.
- Adding custom actions to Fiori elements applications.
