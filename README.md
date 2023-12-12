# NYCU-BioML-2023
NYCU Biological Machine Learning Final Project

# Get modeule
- ```conda install matplotlib xgboost catboost scikit-learn pandas biopython```

# Generate NR by CD-Hit
- ```find testKmer/ -name "*.fasta" | xargs -I % bash -c 'cd-hit -i % -o testNR/$(basename % .fasta).nr050.fasta -c 0.5 -n 2 -T 0'```
