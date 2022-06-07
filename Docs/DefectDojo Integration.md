# DefectDojo Integration

Dependency-Track can automatically publish results to DefectDojo providing a consolidated view of security-centric code findings and vulnerable component findings.

## Configuration

Step 1: Create a product (or navigate to one you’ve created already
Step 2: Create a CI/CD engagement for your product
Step 3: Note down the ID of the new engagement
Step 4: Note down your API key
Step 5: Add the API key in Dependency-Track configuration

### Per-project configuration

Dependency-Track includes the ability to specify configuration properties on a per-project basis. This feature is used to map projects in Dependency-Track to engagements in DefectDojo.

| Attribute      | Value                                                          |
|----------------|----------------------------------------------------------------|
| Group Name     | `integrations`                                                 |
| Property Name  | `defectdojo.engagementId`                                      |
| Property Value | The CI/CD engagement ID to upload findings to, noted in Step 3 |
| Property Type  | `STRING`                                                       |