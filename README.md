### Transform Map Script Example

```javascript
(function runTransformScript(source, map, log, target /*undefined onStart*/ ) {

    // 1. Inactive status irundha transform panna koodadhu
    if (source.u_status == 'Inactive') {
        ignore = true; 
    }

    // 2. Target field-ukku value map panradhu
    if (source.u_email != '') {
        target.email = source.u_email.toLowerCase();
    }

})(source, map, log, target);
```# Importnt-data-using-Transform-Maps-spreadsheet-0
Transform Maps are used in servicenow to import data from spreadsheets into the appropriate tables.  They helps map spreadsheet fields to servicenow fields, transform the data, and ensure that the information is imported accurately and efficiently.
