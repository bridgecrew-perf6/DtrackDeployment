
[Read PDF](../Resources/sbom_at_a_glance_apr2021.pdf)

- [SBOM-Schema (bom1.4)](../Resources/bom_1_4.json)
    - Uses [Json Schema](../Resources/json-schema.json)
      - https://json-schema.org
      - https://json-schema.org/understanding-json-schema/


Fields:

- Serial Number: BOM Serial Number
    - "pattern": "^urn:uuid:[0-9a-f]{8}-[0-9a-f]{4}-[0-9a-f]{4}-[0-9a-f]{4}-[0-9a-f]{12}$"
- Components: A list of software and hardware components.
    ![](../Resources/02-definitions-01.png)
- x-trust-boundary
    ![](../Resources/07-definitions-06-service.png)
- commit information
    ![](../Resources/06-definitions-05.png)
- other information
    ![](../Resources/08-definitions-07.png)

## Resources

- https://ntia.gov/SBOM
- https://ntia.gov/files/ntia/publications/sbom_at_a_glance_apr2021.pdf
- https://cyclonedx.org/use-cases/
- https://github.com/CycloneDX


