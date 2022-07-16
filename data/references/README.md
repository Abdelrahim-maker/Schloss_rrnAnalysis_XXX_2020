# README

Downloaded [SILVA v138 SEED file](https://mothur.org/wiki/silva reference files/) for alignment and taxonomy from:

https://mothur.s3.us-east-2.amazonaws.com/wiki/silva.seed_v138_1.tgz

we used `wget`, `mkdir`, and `tar` to download and extract silva seed files to `data/references/silva_Seed`

```
wget -nc -P data/references/ https://mothur.s3.us-east-2.amazonaws.com/wiki/sil$

mkdir data/references/silva_seed

tar xvzf data/references/silva.seed_v138.tgz -C data/references/silva_seed/
```
