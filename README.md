Overview
This release delivers important hotfixes, reporting enhancements, and usability improvements for SimplicitETL.Client, focusing on EDI document processing, reporting, and user interface stability.

Hotfixes & Improvements
1. Reports & Intercept Client Compatibility
    - Adjusted report logic to ensure compatibility with custom scenarios.
2. Extract Comm Direction Handling
•	Fixed issues with the Direction field in Extract Comm
3. Report File Management
•	Reports are now correctly moved to the appropriate folder when Load Comm is disabled in Document Relationship (DR).
4. Data Splitter & Extract Comm
•	Resolved errors that appeared when saving Extract Comm after using Data Splitter through lookup.
5. Communication Entry Validation
•	Fixed broken validation state for disabled Communication Entry forms.
6. X12 824 PDF Report Generation
•	Backend support added for generating X12 824 PDF Reports.
7. Signature Value Entry
•	Added empty fields for backend during Signature Value generation to improve data integrity.
8. Reprocess & Report Reprocess Logic
•	Enhanced logic for reprocessing documents and reports, improving reliability and traceability.
9. Logs/Documents for DR Without Transform
•	Improved display and handling of logs and documents for DRs without transformation steps.
10. Report Settings for X12 824
•	Added and improved report settings for X12 824 PDF Reports.
11. Error Handling
•	Now displays an error if a report is created as empty, preventing silent failures.
12. Logs/Documents Grid Enhancements
•	Added Source File Report Location column for better traceability in logs and documents.
13. Document Reports
•	Added support for reports for Documents 850, 830, and 997.
14. Miscellaneous Fixes
•	812 Report testing results, improved entity name display, and backend support for DR Without Transformation.
