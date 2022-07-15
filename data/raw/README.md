obtained files from the rrnDB located at 
https://rrndb.umms.med.umich.edu/static/download/ 
These are files from version 5.6, released in 2019

we aoutomated downloading and extracting the tsv file with wget and unzip
wget --directory-prefix=data/raw/ --no-clobber https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8.tsv.zip

 unzip -n -d data/raw/ data/raw/rrnDB-5.8.tsv.zip

 wget -nc -P data/raw/ https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_16S_rRNA.fasta.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.6_16S_rRNA.fasta.zip

wget -nc -P data/raw/ https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_16S_rRNA.fasta.zip 
unzip -n -d data/raw/ data/raw/rrnDB-5.8_16S_rRNA.fasta.zip

wget -nc -P data/raw/ https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_pantaxa_stats_NCBI.tsv.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.8_pantaxa_stats_NCBI.tsv.zip

