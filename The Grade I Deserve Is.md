Use VariantsToTable to make R readable table of annotations

We’ve already done something like this earlier so this should be very familiar:

java ‐jar GenomeAnalysisTK.jar \

‐T VariantsToTable \

‐R ref/human_g1k_b37_20.fasta \

‐V sandbox/NA12878_Combined_SNPs_20.vcf \

‐o sandbox/NA12878_Combined_SNPs_20.table \

‐F CHROM ‐F POS ‐F set ‐F QD ‐F FS \

‐‐allowMissingData \

‐‐showFiltered
