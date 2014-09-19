Geneious_Workflows
==================

Custom automated workflow pipelines that work in Geneious R7+

Briefly, by selecting a user defined sequence list (select all raw sequences > create list) as an input, the workflow will automatically perform a blast search, identify the best reference sequence (if availble on NCBI), map the input sequences to the reference sequence, identify all SNPs, and export the final SNP calls. Each step creates a sub-folder allowing the user to check the results. SNPs were only called if both the forward and reverse strands had the mutation.

PLEASE note that you will need the Geneious Software to use this workflow.  It is  availble at http://www.geneious.com
