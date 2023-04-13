# CHIP
Cyber Health Information and Posture (CHIP) is a Power BI Report built to help organizations centralize and monitor their Microsoft Security


## Documenation
1. Open the Template File
1. Input your TenantId - [See documentation to find TenantId](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-to-find-tenant)
1. Authenticate to the datasources
   1. Select Organizational Account, and provide it with credentials that have Global Reader and Security Reader.
   1. You will have to do this multiple times the first time you load the report
    1. MDE
    1. Sentinel (Log Analytics)
    1. Reports.Office.com
  1. Accept Privacy Levels Warning
    1. This is just warning that combining data can be dangerous and expose data in the wrong places or to the wrong people.
    1. Ensure that anyone the report is shared with should be able to access the data in the report.
    1. Select "Ignore Privacy Levels checks for this file"
1. If you see a "Pending changes in your queries..." warning, apply changes, and wait for reload.

