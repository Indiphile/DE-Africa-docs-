# Archive ODC Product/Datasets (in beta)

- This is repository contain script for archiving odc datasets. According to the 
[ODC API REFERENCE](https://datacube-core.readthedocs.io/en/latest/api/indexed-data/dataset-querying.html) ODC datasets can be archive and later restored.

## WARNING
 - ODC datasets can be restored using **dataset ids**, that means, **datasets ids** must stored before the archiving process.
 - The script in this repository stores the archived **dataset ids** in a ***csv  file*** in a format ***PRODUCT-NAME_archived.csv***


## Running archive_product script
 - Runs on ODC environment. [To configure ODC environment](https://datacube-core.readthedocs.io/en/latest/installation/setup/ubuntu.html#)
 - Input : existing **PRODUCT-NAME**
 - Output : ***PRODUCT-NAME_archived.csv*** containing archived **dataset ids**