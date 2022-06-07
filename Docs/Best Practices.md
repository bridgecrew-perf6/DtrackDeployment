# Best Practices

## Summary

BOMs are a statement of facts, and the type of facts a BOM has will greatly impact how effective the system will be when performing component risk analysis.

## Generating and Obtaining BOMs

- When developing software, generate BOMs during Continuous Integration (CI)
- If using Jenkins, use the Dependency-Track Jenkins Plugin with synchronous publishing mode enabled
- Contractually require BOMs (CycloneDX from vendors
- Generate or acquire BOMs from commercial-off-the-shelf (COTS) software

### Sumary

The ability for an organization to generate a complete bill-of-material during continuous integration is one of many maturity indicators. BOMs are increasingly required for various compliance, regulatory, legal, or economic reasons.

## Analyzers

- Enable Internal Analyzer
- Enable OSS Index

## Data Sources

- Enable National Vulnerability Database mirroring
- Enable GitHub Advisories mirroring

### Summary

Sonatype OSS Index provides accurate vulnerability information for application dependencies. All components in the portfolio should have valid Package URLs to take advantage of OSS Index and GitHub Advisories. Non-application dependencies such as operating systems, hardware, firmware, etc, should have valid CPEs to take advantage of the internal CPE analyzer.

## Leverage APIs and Integrations

- Make findings actionable by leveraging Webhooks (via notifications)
- Automate response to various events if necessary
- Leverage vulnerability aggregation capabilities of:
  - Fortify Software Security Center
  - Kenna Security
  - ThreadFix
- Leverage ChatOps (via notifications) to keep teams informed
