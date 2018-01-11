# yersinia-phylogeny-analysis
This archive contains data sets used and generated as a result of research published as 
PeerJ PrePrint *Olga O Bochkareva, Natalia O Dranenko, Elena S Ocheredko, German M Kanevsky, Yaroslav N Lozinsky,
Vera A Khalaycheva, Irena I Artamonova, Mikhail S Gelfand* **Genome rearrangements and phylogeny reconstruction in *Yersinia pestis***
*DOI: 10.7287/peerj.preprints.3223v1/supp-1*

## Folder 'genes'
contains orthology data set produced by *ad hoc* software based on the Relational Database Management System (RDBMS) Oracle Database Express Edition using BLASTP analysis.

## Folder 'common blocks'
contains the results of common synteny blocks construction, phylogenetic tree construction using [Maximum Likelihood
for Gene Order](http://www.geneorder.org/server.php) and [Bayesian Analysis to Describe Genomic Evolution by Rearrangement](http://badger.duq.edu/manual2/).
Calculations performed for different values of minimum synteny block length such as 500 bp, 1000 bp, 2000 bp and 5000 bp.

## Folder 'all blocks'
contains the results of all synteny blocks construction and phylogenetic tree construction using [MLGO](http://www.geneorder.org/server.php). Calculations performed for different values of minimum synteny block length.

## Folder 'rearrangements'
contains the results of reconstruction of the inversion history for given phylogeny produced by [MGRA2.2](http://mgra.cblab.org/) Calculations performed for two
sets of common synteny blocks with different values of minimum synteny block length (500 bp and 5000 bp) using [Sibelia](http://bioinf.spbau.ru/sibelia).
Folder 'parallel inversions' contains the lists of orthologous groups placed in inverted fragments and trees based on the concatination of
their nucleotide alignments.
