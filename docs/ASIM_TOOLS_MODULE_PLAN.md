# Asim Tools Module Plan — personal-profile

Date: 2026-10-08

## Role
personal profile/portfolio site

## Rule
These are **backend modules to copy locally**, not a remote tool service. Do not call, iframe, link, or fetch Asim Tools at runtime. Do not add a standalone Tools page/section. Integrate the copied functionality into this repository's existing backend or service layer.

## Assigned modules
### Text


### Developer


### SEO & Web


### Security


### Design


### Images


### Time


### Data & Developer


### Generators


## Implementation sequence
1. Copy the smallest needed module and its focused tests.
2. Adapt imports/types/error handling to this repository.
3. Register the helper in the existing service layer.
4. Add repository-native tests before exposing the behavior.
5. For network tools, retain explicit target validation/privacy/rate-limit boundaries.
6. For EXTRACT-FIRST tools, wait for the canonical backend extraction from Asim Tools; do not copy DOM/UI behavior from `src/app.js`.
