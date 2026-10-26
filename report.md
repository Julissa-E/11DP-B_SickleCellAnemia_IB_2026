# Sickle Cell Anemia: A Bioinformatics study

**Authors:** J.P. Espejo, M. Sarrias, S. Delcazo, M.D. Viella, U. Saltó  
**Affiliation:** Introduction to Bioinformatics, UPC, Barcelona, Spain  

---

## Abstract
Sickle Cell Anemia (SCA) is a hereditary hematological disorder caused by mutations in the HBB gene, which encodes the hemoglobin subunit beta. Although the molecular etiology of SCA is classically attributed to a specific missense mutation, comprehensive bioinformatics evaluations comparing nucleotide variations, structural changes, and evolutionary conservation remain vital for understanding phenotype severity and sequence constraints. This study aims to characterize the human wild type (WT) and mutant HBB sequences using comparative bioinformatics tools. 
Sequence alignment using BLASTn between human WT and mutant coding DNA sequences (CDS) revealed two single nucleotide substitutions: a synonymous mutation (c.9TC>C, preserving Histidine) and a missense mutation (c.20A>T). Protein alignment (BLASTp) confirmed that c.20A>T induces a p.Glu6Val change, substituting a polar, hydrophilic glutamic acid with a non-polar, hydrophobic valine on the protein surface. Multispecies comparison against Pan troglodytes (a 100% protein identity) and Equus caballus (83.67% protein identity) demonstrated that position 6, alongside key functional residues such as the distal (His63) and proximal (His92) histidines, is strictly conserved throughout evolution. Structural modeling analysis showed that while secondary and tertiary structures remain intact, the exposed hydrophobic Val6 residue alters quaternary interactions, driving pathological polymerisation of deoxygenated HbS molecules into rigid fibers. 
In summary, our findings show that position 6 is strictly conserved across species because surface residues play a critical functional role. The p.Glu6Val mutation does not disrupt individual protein folding, but drastically reduces hemoglobin solubility, leading to red blood cell sickling. This illustrates how a single-nucleotide change can cause severe structural disease and proves the value of BLAST tools in clinical genetics.

## Keywords
`Sickle Cell Anemia`, `Hemoglobin`, `HBB`, `HbS`

## Background

The beta-globin, which is made by the gene HBB, is a subunit of a larger protein called hemoglobin, that contains 147 amino acids, located inside the red blood cells. It is  involved in the transport of oxygen from the lungs to other tissues around the body. 

For infants through adults, the hemoglobin consists of four protein subunits: Two beta-globins and two alpha-globins. All of these subunits are bound to an iron-containing molecule called heme and consequently each heme can bind to one oxygen molecule.

The aim of our research is to understand the mutation in the beta-globin at chromosome 11 when two HbS alleles, one from each parent, passes it on to their progeny. Studies show that when this scenario occurs, the coding of the amino acid is affected, therefore in the sequence at, position 6, instead of obtaining a glutamic acid, there is a valine (E6V) which changes some properties of the residues that will affect the overall function of such protein.


## Results

The analysis of data sources containing nucleotide and protein sequences allowed us to identify similarities and differences between the sequences studied.

### Structure and Sequence Analysis of protein

The primary structure of both subunits have 147 amino acids and the main annotation in the sequence is E6V. While glutamic acid is negatively charged or acidic, hydrophilic and medium size, valine doesn’t have any charge, is hydrophobic and is a non-polar aliphatic medium size amino acid.
In regards to their angles and tortions, both subunits maintain identical main chain torsion angles across the subunit folds, position 6 maintains its alpha-helical backbone conformation, near the N-terminus of helix A, which is where the mutation can be found.

The secondary structure has 8 right handed alpha-helices from A to H united by short inter-helical loops and no beta-sheets, therefore their motifs are only alpha-alpha. No difference was observed between both beta-globins in regards to this structure.  

As far as their tertiary and quaternary structures, they have only 1 domain which is globin, it is an all-alpha protein fold. Hemoglobin is an heterotetramer which has 2 alpha subunits  and 2 beta subunits, which form an hetero-oligomer linked by non-covalent forces. The monomers are united by hydrogen bonds which provide the alignment and structural stability, and also by ionic bonds, which are crucial for the correct deoxygenated (T-state) and oxygenated (R-state) of the protein, is here where the main difference appears. The mutation changes the electrostatic forces disturbing the overall allosteric regulation. Salt bridges are placed in the outer face of the protein while hydrophobic molecules are in the inner side of the molecule to keep the overall balance of the molecule and the environment that surrounds it, but the salt bridges between Lys132 (positive charge) and Glu6 (negative charge) are no longer possible in Hbs because Val6 has no charge and this perturbation drifts Lys132 and Val6 too apart, this makes the interaction impossible and the local peptide chain flexible and loose, weakening the salt bridges. Because Val6 has no interaction with Lys132, it will have an hydrophobic interaction with residues of the pocket (Phe85 and Leu88). This change leads the tetramers to polymerize into stiff fibers which cause sickle-cell disease.

#### Structural Classification and Comparative Analysis

Analysis of both wild-type (HBB, PDB: 2HHB) and sickle cell mutant (HbS, PDB: 2HBS) beta-globin subunits confirms that both structures maintain identical high-level domain architectures under the Structural Classification of Proteins (SCOP) framework. As summarized in Table (figure 3), the single amino acid substitution (Glu6Val) does not alter the overall fold classification, class, superfamily, or family assignments. 


### Sequence comparison
                                          
#### Identification and Characterization of HBB gene and protein

Using BLAST, we compared the wild type (WT) Coding DNA Sequence (CDS) with the protein sequence, to verify that the identified protein corresponded to the gene identified in the WT CDS. Both matched, as they shared the same gene name, HBB, and were located on chromosome 11, with locus 11p15.4, the gene coding for the HBB protein, Hemoglobin-subunit beta, contained three exons. HBB it's expressed in several tissues and organs, including the lungs, fetal liver, placenta, liver, kidneys, heart, and the spleen. 
                          
#### Comparison of Wild Type and Mutant CDS and Protein sequences 
##### Comparison of Coding DNA Sequences 

The BLAST results comparing the Wild type CDS with the Mutant one showed that the mutant sequence shared a 99.55% of identity with the Wild Type and an E-value of 0.0. After confirming the match, we compared the Wild type (WT) CDS, with the Muatnt CDS. We assured that the Mutant CDS corresponded to the same gene as the Wild type CDS, sharing both the same locus and gene name. However, differences were observed in their sequence alignment results.

#### Comparison of protein sequences

The BLAST results of this search showed that the Mutant protein sequence shared a 99.32% of identity with the Wild Type one. Comparing the Wild type protein sequence with the Mutant protein sequence. We assured that both sequences were coded from the same gene, HBB, and had the same locus. Nevertheless, their sequence alignment results showed some differences. 


#### Comparison of Wild type sequence with homologs sequences
##### *Equus caballus* & *Pan Troglodytes*

The BLAST search showed that the *Equus caballus* CDS shared an identity of 87% with the *Homo sapines* one and a 83.67% with the protein sequence, while the *Pan troglodytes* shared an identity of 99.84% with the Wild type CDS and a 100% with the protein sequence. 

### Sequence alignment
#### Wild type (WT) with mutant

##### Coding DNA sequences

The comparison between the healthy  and mutant nucleotide sequence alignment revealed two substitutions. The first substitution, c.9T>C, is synonymous, as both codons, CAT and CAC, encode the same amino acid, Histidine (His), as they are complementary. The second substitution, c.20A>T, is a missense mutation, in which the codon GAG is replaced by GTG, resulting in the substitution of Glutamic acid (Glu) by Valine (Val); the changed nucleotides are not complementary.
Non insertions or deletions were identified in the nucleotide sequence alignment, we only observed nucleotide substitutions. This is why the reading frame remains unchanged and no frameshift occurs in the sequences analyzed.

##### Protein sequences

The alignment revealed an aminoacid substitution at p.Glu6Val, having the Glutamic acid (Glu) replaced by Valine (Val). The Glutamic acid is polar, charged, and hydrophilic, while Valine is nonpolar, neutral, and hydrophobic. This mutation changes the chemical properties of the protein, making the affected area more hydrophobic.
The substitution of aminoacid can change the interactions that makes at this position, because Glutamic acid (Glu) is charged and hydrophilic, while Valine (Val) is neutral and hydrophobic. As a result, the mutation reduces the ability of the protein to form electrostatic interactions and favors hydrophobic interactions with other Hemoglobin molecules. Accordingly, Valine supports hydrophobic interactions with other Hemoglobin molecules instead of interactions with water, this causes Hemoglobin S (HbS) molecules to stick together and form rigid insoluble polymers. 
The mutation affects the protein folding and function, because the substitution of Glutamic acid by Valine, the chemical properties of the protein's surface change. Valine promotes interaction between Hemoglobin S (HbS) molecules because of its hydrophobic properties. As a result, the Hemoglobin molecules stick together and form rigid fibers, affecting the shape red blood cells, making them go from their biconcave disk shape to sickle shape with pointed ends, and also affecting their normal function of carrying and delivering oxygen.


#### Wild Type (WT) with homologs
###### Coding DNA sequences

The sequence alignment between *Homo sapiens*, *Equus caballus* and *Pan troglodytes* revealed highly conserved regions across the CDS sequence. It shows that the *Homo sapiens* and the *Pan trglodytes* sequences have very few differences between them, while the *Equus caballus* sequence displays more variations between nucleotides. Even so, several regions remain conserved across all three species.
The nucleotide variatons among the three species included substitutions and gaps. The *Pan troglodytes* sequence shows very few substitutions when being compared with the *Homo sapiens* sequence, and no gaps in the aligned region. In the *Equus caballus* sequence, more nucleotide substitutions are present and several gaps- that can indicate possible insertions or deletions- , when being compared with the *Homo sapiens* one. 


###### Protein sequences

The protein sequence alignment between the three species revealed highly conserved regions among them. The *Pan trglodytes* and the *Homo sapiens* protein sequences are identical across the 147 aminoacids analyzed, showing no differences. The *Equus Caballus* sequence also shares many conserved aminoacids with the *Homo sapiens* sequence, although several substitutions are observed.
Not all nucleotide sequence variants between result in aminoacid changes, because different codons can encode the same amino acid, producing synonymous substitutions. In the alignments, the *Homo sapiens* and *Pan troglodytes* CDS sequences show some nucleotide differences, while their protein sequences remain identical.

This high level of sequence conservation is directly reflected in their three-dimensional structure. The 3D structural superposition between the *Homo sapiens* and *Equus Caballus* proteins demonstrates an overall backbone RMSD of 0.83 Å (Figure 1). The alignment shows that the core secondary structure is highly conserved, as observed in white sections, with minor spatial displacements (shown in red) restricted to flexible loop regions where amino acid substitutions occur. The *Pan troglodytes* structure was omitted from this 3D comparison as its protein sequence is 100% identical to the human sequence, resulting in an identical fold (RMSD of 0.0 Å).

The three species appear to be more similar at the protein level than at the CDS level. This is because some nucleotide substitutions are synonymous and do not change the encoded aminoacid. Therefore, we can identify more differences in the DNA sequences that do not always produce differences in the protein sequences.
Some protein positions remain conserved during evolution because they are essential for the protein's structure and function. In our sequence alignment, we identified two conserved Histidine residues at p.64 and p.93 corresponding to positions p.63 and p.92 in mature beta-globin, respectively. These amino acids are important for the Hemoglobin function. The distal Histidine (His63 in mature beta-globin) helps stabilize oxygen binding, while the proximal Histidine (His92 in mature beta-globin) binds directly to the iron of the heme group. Changes in these positions could affect the normal function of hemoglobin, which explains why tend to remain conserved during evolution.

Linking this with the mutant *Homo sapiens* CDS sequence, the disease-associated variant is located at a conserved position in the protein sequence. The alignment shows that Glutamic acid (Glu) at position 6 is conserved across *Homo sapiens*, *Pan troglodytes*, and *Equus caballus*. This aminoacid is located on the surface of the beta-globin protein, is negatively charged and hydrophilic. In the mutant variant that causes the sickle cell anemia, Glutamic acid is replaced by Valine (Val), which is neutral and hydrophobic. This substitution, as said earlier, changes the interactions that take place at this position and promotes the aggregation of deoxygenated HbS molecules.

---

## Discussion
This study demonstrates how a single-nucleotide mutation (c.20A>T) in the HBB gene drives Sickle Cell Anemia (SCA) pathogenesis without altering the core globin fold. Sequence alignment confirmed that the reading frame is preserved alongside a silent mutation (c.9T>C). However, the p.Glu6Val substitution replaces a surface-exposed, hydrophilic Glutamic acid with a hydrophobic Valine, disrupting a stabilizing salt bridge with Lys132. In deoxygenated states, exposed Val6 binds a hydrophobic pocket (Phe85/Leu88) on adjacent tetramers, triggering HbS polymerization into rigid fibers that change the characteristic sickling of red blood cells. (Bishop & Ferrone, 2023; Harrington et al., 1997).
Evolutionary comparison highlights strict purifying selection at critical functional nodes. The 100% amino acid identity between Homo sapiens and Pan troglodytes (RMSD=0.0 Å) reflects complete hominid conservation. Sequence alignment with Equus caballus (83.67% identity) yields a backbone RMSD of 0.83 Å demonstrating conserved secondary structure with minor spatial shifts confined to flexible loops. Crucially, position 6 and histidines (His63/His92) are strictly conserved across species, confirming their functional necessity.
These findings align with therapeutic models like voxelotor, which stabilizes the oxygenated state to block Val6-mediated aggregation (Suhail, 2024; Berg et al., 2002). Limitations of this study include reliance on static crystal structures (PDB:2HHB, 2HBS), lack of molecular dynamics simulations to calculate binding kinetics, and a limited three-species taxon sample.


## Conclusions

This study confirms that the c.20A>T mutation in the HBB gene induces a p.Glu6Val type point substitution, in other words, there are no insertions or deletions, therefore preserving the reading frame and the overall alpha-helix globin fold structure. However, this mutation fundamentally changes the quaternary protein interactions by replacing a polar, negatively charged amino acid with an apolar, neutral one. Therefore, changing the glutamic acid, which is hydrophilic and interacts favorably with water, inside of a red blood cell, for a hydrophobic valine. While the glutamic acid at position 6 forms stable electrostatic attraction with Lys132, Valine has no electrical charge, breaking the stable bond and leaving this region unstable. Under deoxygenated conditions, this exposed valine 6 residue, engages in hydrophobic interactions with a pocket (Phe85/Leu88) on neighboring molecules. As a result, driving the HbS polymerization into rigid fibres, deforming normal biconcave red blood cells into a sickle shape. These rigid, sticky cells provokes dramatic alterations to the hemoglobin solubility and blocks blood flow in capillary vessels, causing severe pain and progressive organ damage due to oxygen deprivation in the tissues. 

In conclusion, sequence alignment and structural modeling of HBB effectively enable us to link molecular genetic data directly with sickle cell disease pathology.

## Methods
### BLAST

For The BLAST searches we used the selected algorithms and parameters for nucleotide and protein sequence comparisons. With The resulting alignments we evaluated the sequence identity, query coverage, E-values, substitutions, gaps, and conserved regions.

#### 1.Sequence Identification Using BLAST

To identify and verify the nucleotide and protein sequences associated with sickle cell anemia, we used the Basic Local Alignment Search Tool (BLAST), available through the National Center for Biotechnology Information (NCBI).First, we analyzed the wild-type coding DNA sequence (WT CDS) and the corresponding wild-type protein sequence of the HBB gene, which encodes hemoglobin subunit beta.
We used BLAST to verify the identity of the sequences by comparing them with sequences available in the NCBI databases. We examined the gene name, chromosome location, sequence identity, query coverage, and E-value to determine whether the sequences corresponded to the HBB gene.
For nucleotide sequences, we used Nucleotide BLAST (BLASTn), while for amino acid sequences, we used Protein BLAST (BLASTp).

#### 2. Comparison Between Wild-Type and Mutant Sequences

After identifying the sequences, we used BLAST to compare the wild-type and mutant versions of the HBB gene at both the nucleotide and protein levels. First, we performed a nucleotide sequence alignment between the wild-type coding DNA sequence (WT CDS) and the mutant coding DNA sequence (mutant CDS) using BLASTn. The alignment was examined to identify nucleotide substitutions, insertions, deletions, and possible changes in the reading frame. Next, we compared the wild-type and mutant protein sequences using BLASTp. This alignment allowed us to identify amino acid substitutions and examine differences between the protein sequences. For both comparisons, we analyzed the sequence alignments and their corresponding identity percentages, query coverage, and E-values.

###### Wild Type (WT) CDS
>SCA_CDS_WT
ACATTTGCTTCTGACACAACTGTGTTCACTAGCAACCTCAAACAGACACCATGGTGCATCTGACTCCTGAGGAGAAGTCT
GCCGTTACTGCCCTGTGGGGCAAGGTGAACGTGGATGAAGTTGGTGGTGAGGCCCTGGGCAGGCTGCTGGTGGTCTACCC
TTGGACCCAGAGGTTCTTTGAGTCCTTTGGGGATCTGTCCACTCCTGATGCTGTTATGGGCAACCCTAAGGTGAAGGCTC
ATGGCAAGAAAGTGCTCGGTGCCTTTAGTGATGGCCTGGCTCACCTGGACAACCTCAAGGGCACCTTTGCCACACTGAGT
GAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCTGGGCAACGTGCTGGTCTGTGTGCTGGCCCA
TCACTTTGGCAAAGAATTCACCCCACCAGTGCAGGCTGCCTATCAGAAAGTGGTGGCTGGTGTGGCTAATGCCCTGGCCC
ACAAGTATCACTAAGCTCGCTTTCTTGCTGTCCAATTTCTATTAAAGGTTCCTTTGTTCCCTAAGTCCAACTACTAAACT
GGGGGATATTATGAAGGGCCTTGAGCATCTGGATTCTGCCTAATAAAAAACATTTATTTTCATTGCAA

###### Mutant CDS
>SCA_CDS_mutant
ATGGTGCACCTGACTCCTGTGGAGAAGTCTGCCGTTACTGCCCTGTGGGGCAAGGTGAACGTGGATGAAGTTGGTGGTGA
GGCCCTGGGCAGGCTGCTGGTGGTCTACCCTTGGACCCAGAGGTTCTTTGAGTCCTTTGGGGATCTGTCCACTCCTGATG
CTGTTATGGGCAACCCTAAGGTGAAGGCTCATGGCAAGAAAGTGCTCGGTGCCTTTAGTGATGGCCTGGCTCACCTGGAC
AACCTCAAGGGCACCTTTGCCACACTGAGTGAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCT
GGGCAACGTGCTGGTCTGTGTGCTGGCCCATCACTTTGGCAAAGAATTCACCCCACCAGTGCAGGCTGCCTATCAGAAAG
TGGTGGCTGGTGTGGCTAATGCCCTGGCCCACAAGTATCACTAA

###### Wild type (WT) Protein
>SCA_protein_WT
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

###### Mutant Protein
>SCA_protein_mutant
MVHLTPVEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

#### 3. Identification of Homologous Sequences Across Species

To identify homologous sequences of the HBB gene in other species, we used BLAST and the NCBI sequence databases. We selected three species for comparison: Homo sapiens, Pan troglodytes, and Equus caballus.
The human sequence was used as the reference sequence (Query), while the chimpanzee and horse sequences were introduced as subject sequences. First, we used BLASTn to compare the coding DNA sequences of the three species. The sequences were aligned to identify conserved nucleotide regions, substitutions, and gaps.
Afterward, we used BLASTp to perform the same comparison at the protein level, using the amino acid sequences of hemoglobin subunit beta from the three species.
The resulting alignments were examined to identify conserved amino acid regions, substitutions, and gaps.

##### *Equus caballus*
###### DNA Sequence
>NM_001164018.1 Equus caballus hemoglobin, beta (HBB), mRNA
ATGGTGCAACTGAGTGGTGAAGAGAAGGCAGCTGTCTTGGCCCTGTGGGACAAGGTGAATGAGGAAGAAGTTGGTGGTGA
AGCCCTGGGCAGGCTGCTGGTTGTCTACCCATGGACTCAGAGGTTCTTTGACTCCTTTGGGGATCTGTCCAATCCTGGTG
CTGTGATGGGCAACCCCAAGGTGAAGGCCCACGGCAAGAAAGTGCTACACTCCTTTGGTGAGGGCGTGCATCATCTTGAC
AACCTCAAGGGCACCTTTGCTGCGCTGAGTGAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCT
GGGCAACGTGCTGGTTGTTGTGCTGGCTCGCCACTTTGGCAAGGATTTCACCCCAGAGTTGCAGGCTTCCTATCAAAAGG
TGGTGGCTGGTGTGGCCAATGCACTGGCCCACAAATACCACTGA

###### Protein sequence
>NP_001157490.1 hemoglobin subunit beta [Equus caballus]
MVQLSGEEKAAVLALWDKVNEEEVGGEALGRLLVVYPWTQRFFDSFGDLSNPGAVMGNPKVKAHGKKVLHSFGEGVHHLD
NLKGTFAALSELHCDKLHVDPENFRLLGNVLVVVLARHFGKDFTPELQASYQKVVAGVANALAHKYH

##### *Pan troglodytes*
###### DNA Sequence
>XM_508242.5 PREDICTED: Pan troglodytes hemoglobin subunit beta (HBB), mRNA
ATCTATTGCTTACATTTGCTTCTGACACAACTGTGTTCACTAGCAACCTCAAACAGACACCATGGTGCACCTGACTCCTG
AGGAGAAGTCTGCCGTTACTGCCCTGTGGGGCAAGGTGAACGTGGATGAAGTTGGTGGTGAGGCCCTGGGCAGGCTGCTG
GTGGTCTACCCTTGGACCCAGAGGTTCTTTGAGTCCTTTGGGGATCTGTCCACTCCTGATGCTGTTATGGGCAACCCTAA
GGTGAAGGCTCATGGCAAGAAAGTGCTCGGTGCCTTTAGTGATGGCCTGGCTCACCTGGACAACCTCAAGGGCACCTTTG
CCACACTGAGTGAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCTGGGCAACGTGCTGGTCTGT
GTGCTGGCCCATCACTTTGGCAAAGAATTCACCCCACCAGTGCAGGCTGCCTATCAGAAAGTGGTGGCTGGTGTGGCTAA
TGCCCTGGCCCACAAGTATCACTAAGCTCGCTTTCTTGCTGTCCAATTTCTATTAAAGGTTCCTTTGTTCCCTAAGTCCA
ACTACTAAACTGGGGGATATTATGAAGGGCCTTGAGCATCTGGATTCTGCCTAATAAAAAACATTTATTTTCATTGCAA

###### Protein Sequence
>XP_508242.1 hemoglobin subunit beta [Pan troglodytes]
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKY

#### 4. Comparison of Nucleotide and Protein Alignments

Finally, we compared the nucleotide and protein sequence alignments obtained using BLAST.
We examined the conservation patterns across the three species at both the CDS and protein levels.
We also compared the nucleotide and amino acid variations to determine whether changes in the coding DNA sequences corresponded to changes in the protein sequences. Additionally, we examined specific amino acid positions associated with hemoglobin function and the disease-related variant identified in the human HBB gene.

### Protein analysis 

Amino acid sequence data for human beta-globin (HBB) was retrieved from the UPC Fasta File (Accession: P68871). Three-dimensional atomic coordinates for wild-type human deoxyhemoglobin (HbA) and mutant sickle cell hemoglobin (HbS) were obtained from the RCSB Protein Data Bank ID: 2hhb for and ID: 2hbs, respectively. Sequence and Structural Analysis Primary sequence alignments and mutation mapping (Glu6Val), taking into account that the numbering begins after the first amino acid of the sequence which is methionine, were performed to compare sidechain physico-chemical property transitions, for this purpose UniProtKB ID: P68871 was used for -globin subunit. Backbone torsion angles (Φ, Ψ, ω) and Ramachandran plot distributions were evaluated to assess secondary structure stability across individual subunits (Harrington et al.,1997). Structural superimposition and surface accessibility analyses were conducted using molecular 3D visualization software PyMOL, based on  crystallographic information obtained from PDB’s asymmetric unit, an x-ray diffraction crystal of 1.74 Å high resolution, to analyze non-covalent interactions and hydrophobic surface exposure at position 6, obtaining an RMSD of 0.266 Å as shown in figure 2.

## Abbreviations
* **SCA:** Sickle Cell Anemia
* **AI:** Artificial Intelligence
* **WT:** Wild Type
* **CDS:** Coding sequence


## Declarations
* **Availability of data and materials:** [Statement on repository/access]
* **Authors' contributions:** [Specify roles]

## References

1. Bishop MF, Ferrone FA. The sickle cell fiber revisited. *Biomolecules*. 2023.

2. Zhai J, Papizan JB, Yao Y, Arnold ED, Yu J, Tran T, et al. A Mouse model for hemoglobin SC disease recapitulates characteristic human pathologies. *Blood Advances*. 2025.

3. Ikolo B, Oyelami M, Mgbeke O, Jones K, Thomas S, Ikolo F. Sickle Cell Disease: From Ancient Origins to Modern Breakthroughs in Gene Therapy. *PubMed Central*. 2026.

4. Germano I, Santos B, Delgadinho M, Ginete C, Lopes P, Arez AP, et al. Genetic Modulation of anemia severity, hemolysis level, and hospitalization rate in Angolan children with Sickle Cell Anemia. *Molecular Biology Reports*. 2022.

5. Van der Meer M, Velsink K, Tong WH, Schoones JW. Is There a Difference in Occurrence of Complications Between Adults With Hemoglobin SS and Hemoglobin SC Disease: An Extended Systematic Review. *European Journal of Haematology*. 2026.
   
6. Suhail M. Biophysical chemistry behind sickle cell anemia and the mechanism of voxelotor action. *Scientific Reports*. 2024.
  
7. Harrington DJ, Adachi K, Royer WE. The high resolution crystal structure of deoxyhemoglobin. Journal of Molecular Biology. 1997.

8. Kirkham JK, Estepp JH, Weiss MJ, et al. Genetic variation and sickle cell disease severity: a systematic review and meta-analysis. JAMA Network Open. 2023.

9. Ilechukwu GE. From HBB Mutation to Precision Medicine: Molecular Pathogenesis, Genetic Modifiers, and Population Genetics of Sickle Cell Disease. Path of Science: International Electronic Scientific Journal. 2026.
  


## IN-TEXT CITATIONS

In-text citation: (Harrington et al. 1997), (Bishop & Ferrone, 2023; Harrington et al., 1997).



