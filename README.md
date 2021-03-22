# Data from INFERNAL pipeline: Exiguobacterium

comand:
```shell
cmsearch --tblout result-cutga-full.txt --noali --cut_ga --rfam --cpu 4 Rfam-14.4.cm base.fasta
```
or

```shell
cmsearch --tblout result-evalue-full.txt--noali -E 0.00001 --rfam --cpu 4 Rfam-14.4.cm base.fasta
```

Description of the repository files

- **result-evalue-full.txt**: Raw output file with e-value (E) parameter
- **result-cut_ga-full.txt**: Raw output file with cut_ga parameter
- **result-evalue.txt**: Clean output file
- **result-cut_ga.txt**: Clean output file
- **lista-rnas-cut_ga.csv**: sRNAs list with cut_ga parameter
- **lista-rnas-evalue.csv**: SRNAS list with e-value parameter
- **resultados-filtrados-cut_ga.csv**: Final result with the cut requirements for the cut_ga parameter
- **resultados-filtrados-evalue.csv**: Final result with the cut requirements for the e-value parameter
