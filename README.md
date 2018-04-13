Files to recreate shorter-than-expected Isovar generated peptide for variant of interest.

(python2) [sbrown@gphost08 /projects/sbrown_prj/POG/immunoPOG/analysis/isovar/COLO829]
λ PYTHONPATH="/projects/sbrown_prj/bin/isovar/" python2 /projects/sbrown_prj/bin/isovar/script/isovar-protein-sequences.py --vcf COLO829_17_81042903_snv.pvcf --bam COLO829_17_81042903_reads_1mut.bam --min-alt-rna-reads 2 --protein-sequence-length 23 --output COLO829_17_81042903_isovar_180111.csv > COLO829_17_81042903_isovar_stdout_180111.txt
