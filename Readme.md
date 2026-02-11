# A paconn cli sample

## Prerequisites
1. Install paconn cli (https://learn.microsoft.com/en-us/connectors/custom-connectors/paconn-cli#install)
 
## Instructions
1. Clone repo
2. `cd` to repo folder
3. Update `apiDefinition.swagger.json` and `apiProperties.json` with your connector values.  **Important**:  update path to mcp endpoint on line `33` in the `apiDefinition.swagger.json` file.
4. Run `paconn login` with the admin account that has access to the target power platform environment that the connector is to be deployed to.
5. Run `paconn create --api-prop .\apiProperties.json --api-def .\apiDefinition.swagger.json` 
6. Follow the prompt to select the power platform environment
7. Confirm successful creation and check the connector is created in the power platform environment.
 