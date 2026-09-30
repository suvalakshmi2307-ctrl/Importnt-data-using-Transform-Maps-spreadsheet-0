### Transform Map Script Example

```javascript(function runTransformScript(source, map, log, target /*undefined onStart*/ ) {

    // Example 1: Ignore record based on source condition
    if (source.u_status == 'Inactive') {
        ignore = true;
    }

    // Example 2: Field value transformation / data formatting
    if (source.u_email) {
        target.email = source.u_email.toString().toLowerCase().trim();
    }

    // Example 3: Default value assignment
    if (!source.u_category) {
        target.category = 'inquiry';
    }

})(source, map, log, target);
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
