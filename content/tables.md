+++
comments = false
date = "2020-06-28T22:17:00+00:00"
draft = false
noauthor = true
share = false
title = "Data Tables"
type = "page"
[menu.main]
weight = 111
+++


##### [Table of TSS expression in LB](/data_tables/TSS_characterization.csv)

Coordinates and expression of 17767 experimentally characterized tss-associated promoters.
Sequences span 150 bp surrounding the reported tss position (-120 to +30 relative to the TSS).
This table includes the sequence tested, TSS position, experimentally-determined activity, and
whether the region passed our threshold for activity in LB during log-phase growth.

<br />

##### [Table of identified (Broad) promoter regions in LB](/data_tables/LB_promoter_regions.csv)

Fragments spanning the entire E. coli genome were screened for promoter activity during log-phase growth in LB media and averaged across the genome to determine promoter activity at single-nucleotide resolutions. Genomic regions demonstrating promoter activity across >60bp were identified. This table includes all identified promoter regions, the highest peak within the region, the summed promoter activity across the length of the region, and the level of activity detected at the regions peak.

<br />

##### [Table of identified (minimal) promoter regions in LB](/data_tables/LB_minimal_promoter_regions.csv)

Our survey of genomic fragments identified candidate regions of promoter activity larger than the expected size of typical promoters. To explore promtoer activity within these regions at higher resolution, we designed a library of 150 bp oligos tiling the lengths of each of the promoter regions identified in LB at 10 bp intervals. This approach allowed us to precisely identify the boundaries of sequence elements driving promoter activity by determining where along the promoter region tiled oligos gained and lost expression. This table includes the coordinates of the minimal region necessary for promoter activity and the mean activity of all tested sequences overlapping the minimal region.

<br />

##### [Table of identified (Broad) promoter regions in M9](/data_tables/M9_promoter_regions.csv)

Fragments spanning the entire E. coli genome were screened for promoter activity during log-phase growth in M9 minimal media and averaged across the genome to determine  promoter activity at single-nucleotide resolutions. Genomic regions demonstrating promoter activity across >60bp were identified. This table includes all identified promoter regions, the highest peak within the region, the summed promoter activity across the length of the region, and the level of activity detected at the regions peak.

<br />

##### [Table of putative regulatory regions controlling promoter activity in LB](/data_tables/regulatory_regions.csv)

Active TSSs were systematically mutated using a scanning mutagenesis approach. 10bp mutations were designed spanning the entire length of 150bp sequences and mutations that significantly altered promoter activity of the TSS were considered regulatory regions. This table includes the positions of these regulatory regions, the log2(fold change) in activity due to mutating these regions, whether it overlapped with TFBSs reported by regulonDB, and whether the reported effects (i.e. repressor vs activator) are in concordance with our observed effects.

<br />

##### [Table of putative E. coli operons](/data_tables/ecoli_operons_U00096.2.csv)

This table contains the coordinates of reported E. coli operons for genome version U00096.2.