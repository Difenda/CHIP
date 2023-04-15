# CHIP
Cyber Health Information and Posture (CHIP) is a Power BI Report built to help organizations centralize and monitor their Microsoft Security

## Initial Set Up
### Step 1. Template File
1. Open the Template File
1. Input Parameters
   1. Input your TenantId - [See documentation to find TenantId](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-to-find-tenant)
   1. Sentinel Workspace Id - [Find your Workspace Id](https://learn.microsoft.com/en-us/azure/sentinel/create-custom-connector#find-your-workspace-id-and-key)
   <img width="531" alt="image" src="https://user-images.githubusercontent.com/106833847/232038579-558982e5-0233-4a21-8f74-56b1accad1ee.png">
1. Authenticate to the datasources
   1. Select Organizational Account, and provide it with credentials that have Global Reader and Security Reader.
      1. <img width="530" alt="image" src="https://user-images.githubusercontent.com/106833847/232039266-560d93e4-025c-4f67-9b4e-22347fe9045c.png">
      2. You will have to do this multiple times the first time you load the report
  1. Accept Privacy Levels Warning
      2. This is just warning that combining data can be dangerous and expose data in the wrong places or to the wrong people.
      1. Ensure that anyone the report is shared with should be able to access the data in the report.
      1. Select "Ignore Privacy Levels checks for this file"

### Step 2. Publish to Power BI Service (Optional)

Publishing to the Power BI Service allows you to easily share the report with others.
1. Create a Workspace
   1. [Official Documenation](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-create-the-new-workspaces#create-a-workspace)
1. Deploy to Power BI Service
   1. [See official Microsoft Documentation](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-upload-desktop-files#to-publish-a-power-bi-desktop-dataset-and-reports)

## Microsoft "Scores" Information

1. Organization Exposure Score - This score reflects the current exposure associated with devices in your organization. The score is potentially impacted by active exceptions.
2. Secure Score for Devices - This score reflects the collective security configuration posture of your devices across OS, Application, Network, Accounts and Security Controls Score is potentially impacted by active exceptions.
3. Cloud Secure Score

