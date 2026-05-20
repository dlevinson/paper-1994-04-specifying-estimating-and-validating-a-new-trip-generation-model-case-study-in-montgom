# Specifying, Estimating, And Validating A New Trip Generation Model

## Bibliographic Information

- Row ID: `paper-1994-04`
- Authors: Ajay Kumar and David M. Levinson
- Year: 1994
- Venue: Transportation Research Record, 1413, 107-113
- Citation: Kumar, A., and Levinson, D. M. (1994). Specifying, estimating, and validating a new trip generation model: Case study in Montgomery County, Maryland. Transportation Research Record, 1413, 107-113.

## Package Status

This package is ready for public upload review. A paper-first audit found paper-specific aggregate trip-generation workbooks in the local `TRR-GENERATION` source folder. Those workbooks are staged here with modernized `.xlsx` and `.csv` sidecars.

The package does not include raw household travel survey microdata, raw Census-Update survey responses, raw site survey records, correspondence, drafts, presentation files, or broad MNCPPC land-use/tool directories. Generic Travel/2 source dependencies are referenced through shared-source pointers rather than duplicated here.

## Contents

- `paper/`: local reference copy of the published paper.
- `data/trip_generation_workbooks/original_legacy/`: selected legacy Lotus/Excel workbook files.
- `data/trip_generation_workbooks/modernized/xlsx/`: LibreOffice-converted workbooks.
- `data/trip_generation_workbooks/modernized/csv/`: value exports from each workbook.
- `data/trip_generation_workbooks/SOURCE_FILE_REVIEW.csv`: inclusion/exclusion decisions for the source folder.
- `data/trip_generation_workbooks/modernized/workbook_summary.json`: workbook metadata and checksums.
- `documentation/SHARED_SOURCE_POINTERS.md`: pointers to shared Travel/2 source bundles used across early papers.

## Source Folder Reviewed

`/Users/dlev2617/Documents/Papers/~05-Published/Transportation Research Record (TRR) - Journal of the Transportation Research Board/TRR-GENERATION`

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:23:47 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
