```
In this project,
You will be reading a genomic data science paper and answering some questions to help you learn about how the different fields in genomic data science work together.
To evaluate your understanding of some of the concepts we have learned throughout the course. 

The paper we are reading is called: “Microbial Genes in the Human Genome: Lateral Transfer or Gene Loss?” 

You can access the paper from the Science Magazine site here: 
http://www.sciencemag.org/content/292/5523/1903.full. 

You’ll need to register for a free Science account to access the full text. 
If you aren’t able to do that, then you can also access the via this link: 

Salzberg et al. 2001 
(https://d396qusza40orc.cloudfront.net/genintro/misc/Salzberg-etal-2001-Science.pdf)

You may also find the annotated version of the manuscript helpful for the project. 

Annotated version 
(http://www.sciencemag.org/site/feature/data/scope/keystone1/)
```
```
Question 1

Why did the authors write this paper?

(i) To prove that there are a large number of genes shared between humans and bacteria.
(ii) To show that sample size formulae for “lateral” gene transfer are not correct.
(iii) To propose a plausible alternative to the hypothesis that genes had been “laterally” transferred to humans.
(iv) To show that species cluster together by their human hyaluronan synthase protein sequences.
```
```
Question 2

What is “lateral gene transfer”?

(i) When genetic material is passed between one human and another human.
(ii) When genetic material is passed from the genome of one organism to another through a process other than reproduction.
(iii) When genetic material is transferred from RNA to proteins.
(iv) When genes are transferred out of the nucleus and into the cell.
```
```
Question 3

Why is lateral gene transfer (LGT) from bacteria to humans unlikely?

(i) Bacterial genes are so different from human genes that a human could not survive with bacterial genes in his/her chromosomes.
(ii) Because a bacterium would have to infect a germline cell, enter the nucleus of that cell, and insert some of its DNA into one of the host’s chromosomes, after which the mutation would then have to provide an evolutionary advantage to spread through the population.
(iii) Because bacteria never actually enter human cells during an infection.
(iv) Because human cells destroy bacteria too quickly for LGT to occur.
```
```
Question 4

What are homologs?

(i) Genes that perform similar biochemical functions but have different sequences.
(ii) Two copies of a gene in different organisms that share a common ancestor.
(iii) Genes that have evolved to have the same function but different sequences.
(iv) Genes that are greater than 99% similar in DNA sequence
```
```
Question 5

What was the main method used to rule out lateral gene transfers between humans and bacteria?

(i) If a homolog of a bacteria was also found in humans.
(ii) If a homolog of a gene found in humans was also found in a species of nonvertebrate eukaryotes.
(iii) If genes were found to have mutated between humans and bacteria.
(iv) If a homolog of a gene was found in prokaryotic genomes.
```
```
Question 6

Why would this method rule out lateral gene transfers?

(i) Inheritance of common genes is less common than lateral gene transfer and nonvertebrate eukaryotic organisms and humans are evolutionarily “closer” than bacteria and humans. If humans and bacteria share a homologous gene, it was likely directly passed from bacteria to humans.
(ii) Nonvertebrate eukaryotic organisms and bacteria are evolutionarily “closer” than invertebrate eukaryotic organisms and humans. If they share a homologous gene, then bacteria are likely to have passed genes directly to humans.
(iii) Humans and bacteria are both likely to have shared an evolutionary history with nonvertebrate eukaryotic organisms, so genes are likely to be homologous across all three.
(iv) Lateral gene transfer is an unusual process compared to standard inheritance and nonvertebrate eukaryotic organisms and humans are evolutionarily “closer” than bacteria and humans. If humans and nonvertebrates share a homologous gene, it was likely not directly passed from bacteria to humans.
```
```
Question 7

What are the biological, computational, and statistical parts of Figure 1?

(i) Biological: the argument that gene should be ruled out if there is a human/nonvertebrate eukaryote homologs. 
Computational: Observing and quantifying the trend in genes shared versus genome sample size. 
Statistical: The identification of homologs by performing Blastp searches on known protein sets.
(ii) Biological: the argument that a Blast cutoff of 10^-10 should define homologs 
Computational: The identification of homologs by performing Blastp searches on known protein sets. 
Statistical: Observing and quantifying the trend in genes shared versus genome sample size.
(iii) Biological: the argument that lateral transfer should be ruled out if there is a human/nonvertebrate eukaryote homologs. 
Computational: The identification of homologs by performing Blastp searches on known protein sets. 
Statistical: Observing and quantifying the trend in genes shared versus genome sample size.
(iv) Biological: the argument that a Blast cutoff of 10^-10 should define homologs 
Computational: The plotting of number of genomes versus number of genes in common 
Statistical: Observing and quantifying the trend in genes shared versus genome sample size.
```
```
Question 8

What are the biological, computational, and statistical parts of Figure 2?

(i) Biological: the argument that lateral gene transfer is less common than standard gene flow through reproduction 
Computational: The storage of data in a low redundancy protein database. 
Statistical: The inference that humans cluster more closely (have smaller distances to) other eukaryotes than to bacteria.
(ii) Biological: the argument that lateral gene transfer is less common than standard gene flow through reproduction 
Computational: The identification of homologs of human HAS genes by iterative BlastP searches and application of the neighbor-joining algorithm to create the phylogenetic tree. 
Statistical: The inference that humans cluster more closely (have smaller distances to) other eukaryotes than to bacteria.
(iii) Biological: the argument that lateral gene transfer is less common than standard gene flow through reproduction. 
Computational: The calculation of statistical significance of the protein hits in the Blastp search. 
Statistical: The statistical modeling of protein sequences via a Markov Model.
(iv) Biological: the argument that proteins should have more similar sequences if they are evolutionarily closer. 
Computational: The identification of homologs of human HAS genes by iterative BlastP searches and application of the neighbor-joining algorithm to create the phylogenetic tree. 
Statistical: The inference that humans cluster more closely (have smaller distances to) other eukaryotes than to bacteria.
```
```
Question 9

The analysis in this paper required multiple data sources. 
Which of the following data sources was not used in the paper?

(i) The complete set of noncoding RNA genes from the human genome.
(ii) The complete set of annotated genes from two different versions of the human genome.
(iii) The set of all known genes (at the time) from the malaria parasite, Plasmodium falciparum.
(iv) The complete set of genes from the fruit fly, nematode worm, yeast, and mustard weed genomes.
```
```
Question 10

In the end what is the conclusion of the paper?

(i) That genes are more likely to be laterally transferred from certain types of bacteria to humans.
(ii) That clustering organisms by protein similarity is the right way to discover lateral gene transfer events.
(iii) That a more plausible explanation for the observation of homologous genes found in bacteria and humans but not in non-vertebrate eukaryotes is gene loss and low sample size.
(iv) That the argument for lateral gene transfer is statistical because we must average over multiple possible transfer events.
```