# Project Overview

### DataService Package

1. Access the UiPath Automation Cloud Platform at https://cloud.uipath.com/.
2. Enable Data Service for the designated tenant: <br>
     i. Navigate to Admin -> DefaultTenant -> Services. <br>
    ii. Click on "Add Services" -> "Data service" -> "Add." <br>
3. In the UiPath Studio, ensure that the Data Service package is installed. This can be done through the "Manage Packages" section.
4. Within Orchestrator, go to "Manage Entities" to create a new entity with specified fields. <br>
   **Entity: Invoice** <br>
   **Fields: InvoiceID, SupplierName** <br>
6. Import the newly created entity into your UiPath Studio workspace by selecting it in the "Manage Entities" section.

### Objective
To add new data records into the **Invoice** Entity using the **DataService** package activities.
