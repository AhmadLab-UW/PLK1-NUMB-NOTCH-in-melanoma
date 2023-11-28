# PLK1-NUMB-NOTCH-in-melanoma

## Content
### Script
"TCGA_SKCM.Rmd" is the file used to process TCGA melanoma and GTEX skin data.

"02-2023_partition_GTEx.ipynb" is the file used to extract NUMB isoform expression from GTEx database.
### Data
The folder "TCGAdata" contains the data that are processed by the R script.
### Data resource
TCGA melanoma: expression and patient survival were downloaded from `https://www.cbioportal.org/`; isoform expression was downloaded from Broad GDAC Firehose `https://gdac.broadinstitute.org/runs/stddata__2016_01_28/data/SKCM/20160128/gdac.broadinstitute.org_SKCM.Merge_rnaseqv2__illuminahiseq_rnaseqv2__unc_edu__Level_3__RSEM_isoforms_normalized__data.Level_3.2016012800.0.0.tar.gz`.

GTEx: isoform expression was downloaded from `https://storage.cloud.google.com/adult-gtex/bulk-gex/v8/rna-seq/GTEx_Analysis_2017-06-05_v8_RSEMv1.3.0_transcript_tpm.gct.gz`, and was renamed as `GTEx_transcript_v8.gct` afterwards (File is too large to upload); sample annotation were downloaded from `https://storage.cloud.google.com/adult-gtex/annotations/v8/GTEx_Analysis_v8_Annotations_SampleAttributesDS.txt` .
