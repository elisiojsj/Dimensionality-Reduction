# Dimensionality Reduction
When dealing with datasets with many attributes, high-dimensional space, it's desirable to reduce its complexity by transforming them into a low-dimensional space. It makes the task of training the model faster as it'll have to deal with less features. Besides, it may considerably save computational resources. 

## Project
The objective with this project is to use PCA for dimensionality reduction of a dataset with many attributes. It's a simple application of the PCA library of scikit-learn and will work as a reference for future projects. One disadvantage of PCA is that the new data may not be easily interpretable anymore because of the transformations it suffer.
<br>
<br>
To visualise the data the t-SNE algorithm was also applied. 


## Dataset
The chosen dataset is the UCI [Codon usage Data Set](https://archive.ics.uci.edu/ml/datasets/Codon+usage).
Some information of the dataset from the UCI website:
<br>
<br>
"We examined codon usage frequencies in the genomic coding DNA of a large sample of diverse organisms from different taxa tabulated in the CUTG database, where we further manually curated and harmonized these existing entries by re-classifying CUTG's bacteria (bct) class into archaea (arc), plasmids (plm), and bacteria proper (keeping with the original label 'bct'). The reclassification in the original 'bct' domain was simplified by extracting from files 'qbxxx.spsum.txt' (where xxx = bct (bacteria), inv (invertebrates), mam (mammals), pln (plants), pri (primates), rod (rodents), vrt (vertebrates)) the different genus names of the entries, and making the classification by genus. There were 514 different genus names. The different genus categories were checked and relabeled as 'arc' where appropriate. In the eubacterial entries, the distinction was made of the bacterial genomes proper (keeping with the original label 'bct'), and bacterial plasmids (now labeled 'plm')."
