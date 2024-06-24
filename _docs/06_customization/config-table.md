---
title: Table
stub: config-table
section: customize
section_order: 5
---

{:.py-4 .mt-4 #config-table}
***

## Table Configuration (config-table.csv)

The table appears on the "Data" page. It uses [DataTables](https://datatables.net/) to generate a table that can be searched, sorted, and downloaded as a whole or in a filtered version.

We recommend not using more than 5 or 6 fields here, as the table can become overcrowded. 

- **field**: Determines the metadata field that is included on the table. 
- **display_name**: Determines the label that is displayed for that field.  

### Example 

{:.p-4 .bg-light .mb-4}
```
field,display_name
title,Title
date,Date
creator,Photographer
subject,Subjects
```