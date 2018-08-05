
# ConfluenceMacs - Confluence Macros

## Introduction

[Confluence](https://www.atlassian.com/software/confluence) [macros](https://confluence.atlassian.com/doc/macros-139387.html) for various use cases in Confluence.

## Macro List

[Drop Down List - Status - Style 1](/drop-down-list-status-style-1.vtl)
* Macro Type: [User Macro](https://confluence.atlassian.com/doc/writing-user-macros-4485.html)
* Macro Name: drop-down-list-status-style-1
* Description: Add a drop down list for selecting from the following [status](https://confluence.atlassian.com/doc/status-macro-223222355.html) choices: NOT STARTED,IN PROGRESS,ON HOLD,COMPLETE,BLOCKED,CANCELLED
* Example Use Case: Embed a drop down list in a [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) table as the value for the row labeled "Status", and ensure that users are only able to choose from a list of predefined values that supply [status](https://confluence.atlassian.com/doc/status-macro-223222355.html)

[Page Data - Created By](/page-data-created-by.vtl)
* Macro Type: [User Macro](https://confluence.atlassian.com/doc/writing-user-macros-4485.html)
* Macro Name: page-data-created-by
* Description: Add the page creator's name to the page
* Example Use Case: Embed the page creator's name in a [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) table as the value for the row labeled "Requested By"

[Page Data - Created Date](/page-data-created-date.vtl)
* Macro Type: [User Macro](https://confluence.atlassian.com/doc/writing-user-macros-4485.html)
* Macro Name: page-data-created-date
* Description: Add the page's creation date to the page
* Example Use Case: Embed the page's creation date in a [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) table as the value for the row labeled "Opened"

[Page Data - Last Modified By](/page-data-last-modified-by.vtl)
* Macro Type: [User Macro](https://confluence.atlassian.com/doc/writing-user-macros-4485.html)
* Macro Name: page-data-last-modified-by
* Description: Add the last page modifier's name to the page
* Example Use Case: Embed the last page modifier's name in a [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) table as the value for the row labeled "Last Update By"

[Page Data - Last Modified Date](/page-data-last-modified-date.vtl)
* Macro Type: [User Macro](https://confluence.atlassian.com/doc/writing-user-macros-4485.html)
* Macro Name: page-data-last-modified-date
* Description: Add the page's last modified date to the page
* Example Use Case: Embed the page's last modified date in a [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) table as the value for the row labeled "Last Updated"

[Page Data - Version](/page-data-version.vtl)
* Macro Type: [User Macro](https://confluence.atlassian.com/doc/writing-user-macros-4485.html)
* Macro Name: page-data-version
* Description: Add the page's version to the page
* Example Use Case: Embed the page's version in a [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) table as the value for the row labeled "Updates"

## Credits
* [Confluence community](https://community.atlassian.com/t5/Answers-Developer-Questions/Confluence-5-x-API-extracting-page-metadata-created-by-date/qaq-p/529471) helped explain how to extract page metadata with a user macro.
* [Confluence community](https://community.atlassian.com/t5/Confluence-questions/Custom-drop-down-list-for-Statuses/qaq-p/445314) helped explain how to create a drop down list for predefined values that supply [status](https://confluence.atlassian.com/doc/status-macro-223222355.html) with a user macro.
* Various articles on how to utilize [Page properties](https://confluence.atlassian.com/doc/page-properties-macro-184550024.html) and [Page properties report](https://confluence.atlassian.com/doc/page-properties-report-macro-186089616.html) macros:
    * http://lightmanyfires.com/summary-pages-using-page-propeties-report-confluence/
    * https://confluence.atlassian.com/confcloud/create-a-blueprint-style-report-937893616.html
    * https://confluence.atlassian.com/doc/page-properties-macro-184550024.html
    * https://confluence.atlassian.com/doc/page-properties-report-macro-186089616.html
