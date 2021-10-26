# FUNGuild_R
R version of FUNGuild with offline mode

### Notice:
1.Only support UNITE annotated taxonomy data.
2. R packages 'optparse','jsonlite','funr','stringr' are required.

### Useage
Rscript Funguild_R.r -i otu_table.txt -t taxonomy -f tsv -o funguild.txt

-i: input otu/asv table
-t: appoint the column name of taxa info
-f: table type, tsv or csv
-o: output file name

The results table is the same format as FUNGuild.
