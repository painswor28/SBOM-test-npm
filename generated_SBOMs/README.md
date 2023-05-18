# SBOM Generation Test Results

## github-generated.json

Generated using github's SBOM creation tool. (Insights > Dependency graph > Export SBOM)
SPDX Version: 2.3

- packages: 978
  - SPDXID
  - name
  - version
  - licsenseconcluded (sometimes)
  - externalRefs
    - referenceCategory
    - referenceLocator
    - referenceType
- files: 0
- relationships: 0

## tool-generated.json

Generated using [microsoft/sbom-tool](https://github.com/microsoft/sbom-tool).
SPDX Version: 2.2

- packages: 961
  - name
  - SPDXID
  - version
  - supplier
  - externalRefs
    - referenceCategory
    - referenceLocator
    - referenceType
- files: 61205
- relationships: 961
  - package to root only

**Summary:** Less packages and no license conclusions but suppliers are found
