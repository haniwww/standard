<style>
.wy-nav-content {
    max-width:100000px;
}
</style>
<script>window.setTimeout(replaceLinks, 1000);
function replaceLinks() {
        $("a").each(function() { $(this).attr("href",$(this).attr("href").replace("http://standard.open-contracting.org/latest/es_MX/schema/codelists/","").replace("latest/es_MX","latest/es").replace("http://localhost:8000/es_MX/schema/full/","")) } )
        $(".wy-nav-side").remove()
        $("div[role='navigation']").remove()
        $(".wy-nav-content-wrap").css("margin-left","0px")
}
</script>

# OCDS: Localized translation

This page provides a reference list of fields in the core OCDS 1.1 schema, along with localized translations prepared by the Mexico Ministry of Finance. 

Fields from 1.0, deprecated in version 1.1, have been removed from the schema.

Other fields may be present in the published data through the use of OCDS extensions.

## Release package schema 

```eval_rst

.. jsonschema:: ../../../../build/current_lang/release-package-schema.json
    :include:
    :collapse:
    :nocrossref:
```

## Release schema

```eval_rst 

.. jsonschema:: ../../../../build/current_lang/release-schema.json
    :include:
    :collapse:

```

## Open Codelists

### Party Role

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/partyRole.csv
```


### Item Classification Scheme

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/itemClassificationScheme.csv
```

### Unit Classification Scheme

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/unitClassificationScheme.csv
```

### Organization Identifier Scheme

The Organization Identifier Scheme currently uses the codes from [org-id.guide](http://www.org-id.guide). 

### Document Type


```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :widths: 10 10 10 20 50
   :file: ../../../schema/codelists_translated/documentType.csv
```

### Award Criteria

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :widths: 20 20 50 10
   :file: ../../../schema/codelists_translated/awardCriteria.csv
```

### Submission Method

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/submissionMethod.csv
```

### Related Process

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/relatedProcess.csv
```

### Related Process Scheme

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/relatedProcessScheme.csv
```


### Milestone Type

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/milestoneType.csv
```

### Extended Procurement Category

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/extendedProcurementCategory.csv
```


## Closed Codelists 

### Release Tag

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/releaseTag.csv
```

### Initiation Type

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/initiationType.csv
```

### Tender Status

```eval_rst
.. csv-table-no-translate:: 
   :header-rows: 1
   :file: ../../../schema/codelists_translated/tenderStatus.csv
```

### Method

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/method.csv
```

### Procurement Category

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/procurementCategory.csv
```

### Award Status

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/awardStatus.csv
```

### Contract Status

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/contractStatus.csv
```

### Milestone Status

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/milestoneStatus.csv
```

### Currency

The currency for each amount should always be specified using the uppercase 3-letter currency code from [ISO4217](http://www.iso.org/iso/home/standards/currency_codes.htm).

```eval_rst
.. csv-table-no-translate::
   :header-rows: 1
   :file: ../../../schema/codelists_translated/currency.csv
```
