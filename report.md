# Sickle Cell Anemia: A Bioinformatics study

**Authors:** [J.P. Espejo, M. Sarrias, S. Delcazo, M.D. Viella, U. Saltó]  
**Affiliation:** [Introduction to Bioinformatics, UPC, Barcelona, Spain]  

> **Limits & Guidelines:**
> * Maximum limit of **7 pages** or **5000 words** (whichever is shorter).
> * References do not contribute to page or word count (more than 1 page of references is not recommended).
> * Maximum of **5 figures or tables** must be respected and stored in the repository.

---

## Abstract
Sickle Cell Anemia (SCA) is a hereditary hematological disorder caused by mutations in the HBB gene, which encodes the hemoglobin subunit beta. Although the molecular etiology of SCA is classically attributed to a specific missense mutation, comprehensive bioinformatics evaluations comparing nucleotide variations, structural changes, and evolutionary conservation remain vital for understanding phenotype severity and sequence constraints. This study aims to characterize the human wild-type (WT) and mutant HBB sequences using comparative bioinformatics tools. 
Sequence alignment using BLASTn between human WT and mutant coding DNA sequences (CDS) revealed two single nucleotide substitutions: a synonymous mutation (c.9TC>C, preserving Histidine) and a missense mutation (c.20A>T). Protein alignment (BLASTp) confirmed that c.20A>Tc.20A>T induces a p.Glu7Val change (Glu6Val in mature β-globin), substituting a polar, hydrophilic glutamic acid with a non-polar, hydrophobic valine on the protein surface. Multi-species comparison against Pan troglodytes (100% protein identity) and Equus caballus (83.67% protein identity) demonstrated that position 7, alongside key functional residues such as the distal (His63) and proximal (His92) histidines, is strictly conserved throughout evolution. Structural modeling analysis showed that while secondary (α-helical bundle) and tertiary (Globin fold) structures remain intact, the exposed hydrophobic Val7 residue alters quaternary interactions, driving pathological polymerisation of deoxygenated HbS molecules into rigid fibers. 
In summary, our findings show that position 7 is strictly conserved across species because surface residues play a critical functional role. The p.Glu7Val mutation does not disrupt individual protein folding, but drastically reduces hemoglobin solubility, leading to red blood cell sickling. This illustrates how a single-nucleotide change can cause severe structural disease and proves the value of BLAST tools in clinical genetics.

## Keywords
`Sickle Cell Anemia`, `Hemoglobin`, `HBB`, `HbS`

## Background
Part of background
The beta-globin, which is made by the gene HBB, is a subunit of a larger protein called hemoglobin, that contains 147 amino acids, located inside the red blood cells. It is  involved in the transport of oxygen from the lungs to other tissues around the body. 

For infants through adults, the hemoglobin consists of four protein subunits: Two beta-globins and two alpha globins. All of these subunits are bound to an iron-containing molecule called heme and consequently each heme can bind to one oxygen molecule.  (1)

The aim of our research is to understand the mutation in the beta-globin at chromosome 11 when two HbS alleles, one from each parent, passes it on to their progeny . Studies show that when this scenario occurs, the coding of the amino acid is affected, therefore in the sequence at, position 6, instead of obtaining a glutamic acid, there is a valine (E6V) which changes some properties of the residues that will affect the overall function of such protein.


## Results

The analysis of data sources containing nucleotide and protein sequences allowed us to identify similarities and differences between the sequences studied.

Proteins:
Structure and Sequence Analysis

The primary structure of both subunits have 147 amino acids and the main annotation in the sequence is E6V. While glutamic acid is negatively charged or acidic, hydrophilic and medium size, valine doesn’t have any charge, is hydrophobic and is a non-polar aliphatic medium size amino acid.
In regards to their angles and tortions, both subunits maintain identical main chain torsion angles across the subunit folds, position 6 maintains its -helical backbone conformation, near the N-terminus of helix A, which is where the mutation can be found.

The secondary structure has 8 right handed -helices from A to H united by short inter-helical loops and no -sheets, therefore their motifs are only -. No difference was observed between both -globins in regards to this structure. (link) 

As far as their tertiary and quaternary structures, they have only 1 domain which is globin, it is an all- protein fold. Hemoglobin is a heterotetramer which has 2 subunits  and 2 subunits , which form a hetero-oligomer linked by non-covalent forces. The monomers are united by hydrogen bonds which provide the alignment and structural stability and  also ionic bonds, which are crucial for the correct deoxygenated (T-state) and oxygenated (R-state) of the protein, and here is where the main difference appears. The mutation changes the electrostatic forces disturbing the overall allosteric regulation. Salt bridges are placed in the outer face of the protein while hydrophobic molecules are in the inner side of the molecule to keep the overall balance of the molecule and the environment that surrounds it, but the salt bridges between Lys132 (positive charge) and Glu7 (negative charge) are no longer possible in Hbs because Val7 has no charge and this perturbation drifts Lys132 and Val7 too apart, this makes the interaction impossible and the local peptide chain flexible and loose, weakening the salt bridges. Because Val7 has no interaction with Lys132, it will have an hydrophobic interaction with residues of the pocket ( Phe85 and Leu88). This change leads the tetramers to polymerize into stiff fibers which cause sickle-cell disease.

Structural Classification and Comparative Analysis

Analysis of both wild-type (HBB, PDB: 2HHB) and sickle cell mutant (HbS, PDB: 2HBS) beta-globin subunits confirms that both structures maintain identical high-level domain architectures under the Structural Classification of Proteins (SCOP) framework. As summarized in Table (x change later), the single amino acid substitution (Glu6Val) does not alter the overall fold classification, class, superfamily, or family assignments.


### Sequence comparison
                                          
#### Identification and Characterization of HBB gene and protein

Using BLAST, we compared the wild type (WT) Coding DNA Sequence (CDS) with the protein sequence, to verify that the identified protein corresponded to the gene identified in the WT CDS. Both matched, as they shared the same gene name, HBB, and were located on chromosome 11, with locus 11p15.4, the gene coding for the HBB protein, Hemoglobin-subunit beta, contained three exons. HBB it's expressed in several tissues and organs, including the lungs, fetal liver, placenta, liver, kidneys, heart, and the spleen. 
                          
#### Comparison of Wild Type and Mutant CDS and Protein sequences 
##### Comparison of Coding DNA Sequences 
The BLAST results comparing the Wild type CDS with the Mutant one showed that the mutant sequence shared a 99.55% of identity with the Wild Type and an E-value of 0.0. After confirming the match, we compared the Wild type (WT) CDS, with the Muatnt CDS. We assured that the Mutant CDS corresponded to the same gene as the Wild type CDS, sharing both the same locus and gene name. However, differences were observed in their sequence alignment results;


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

#### Comparison of protein sequences
The BLAST results of this search showed that the Mutant protein sequence shared a 99.32% of identity with the Wild Type one. Comparing the Wild type protein sequence with the Mutant protein sequence. We assured that both sequences were coded from the same gene, HBB, and had the same locus. Nevertheless, their sequence alignment results showed some differences; 

###### Wild type (WT) Protein
>SCA_protein_WT
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

###### Mutant Protein
>SCA_protein_mutant
MVHLTPVEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

#### Comparison of Wild type sequence with homologs sequences
##### Assigned Species: *Equus caballus*
The BLAST search showed that the *Equus caballus* CDS shared an identity of 87% with the *Homo sapines* one and a 83.67% with the protein sequence, while the *Pan troglodytes* shared an identity of 99.84% with the Wild type CDS and a 100% with the protein sequence. 

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


##### Other Homolog Species: *Pan Troglodytes*

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
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

### Sequence alignment
#### Wild type (WT) with mutant

##### Coding DNA sequences

The comparison between the healthy  and mutant nucleotide sequence alignment revealed two substitutions. The first substitution, c.9T>C, is synonymous, as both codons, CAT and CAC, encode the same amino acid, Histidine (His), as they are complementary. The second substitution, c.20A>T, is a missense mutation, in which the codon GAG is replaced by GTG, resulting in the substitution of Glutamic acid (Glu) by Valine (Val); the changed nucleotides are not complementary.
Non insertions or deletions were identified in the nucleotide sequence alignment, we only observed nucleotide substitutions. This is why the reading frame remains unchanged and no frameshift occurs in the sequences analyzed.

##### Protein sequences

The alignment revealed an aminoacid substitution at p.Glu7Val, having the Glutamic acid (Glu) replaced by Valine (Val). The Glutamic acid is polar, charged, and hydrophilic, while Valine is nonpolar, neutral, and hydrophobic. This mutation changes the chemical properties of the protein, making the affected area more hydrophobic.
The substitution of aminoacid can change the interactions that makes at this position, because Glutamic acid (Glu) is charged and hydrophilic, while Valine (Val) is neutral and hydrophobic. As a result, the mutation reduces the ability of the protein to form electrostatic interactions and favors hydrophobic interactions with other Hemoglobin molecules. Accordingly, Valine supports hydrophobic interactions with other Hemoglobin molecules instead of interactions with water, this causes Hemoglobin S (HbS) molecules to stick together and form rigid insoluble polymers. 
The mutation affects the protein folding and function, because the substitution of Glutamic acid by Valine, the chemical properties of the protein's surface change. Valine promotes interaction between Hemoglobin S (HbS) molecules because of its hydrophobic properties. As a result, the Hemoglobin molecules stick together and form rigid fibers, affecting the shape red blood cells, making them go from their biconcave disk shape to sickle shape with poited ends, and also affecting their normal function of carrying and delivering oxygen.


#### Wild Type (WT) with homologs
###### Coding DNA sequences

The sequence alignment between *Homo sapiens*, *Equus caballus* and *Pan troglodytes* revealed highly conserved regions across the CDS sequence. It shows that the *Homo sapiens* and the *Pan trglodytes* sequences have very few differences between them, while the *Equus caballus* sequence displays more variations between nucleotides. Even so, several regions remain conserved across all three species.
The nucleotide variatons among the three species included substitutions and gaps. The *Pan troglodytes* sequence shows very few substitutions when being compared with the *Homo sapiens* sequence, and no gaps in the aligned region. In the *Equus caballus* sequence, more nucleotide substitutions are present and several gaps- that can indicate possible insertions or deletions- , when being compared with the *Homo sapiens* one. 


###### Protein sequences
The protein sequence alignment between the three species revealed highly conserved regions among them. The *Pan trglodytes* and the *Homo sapiens* protein sequences are identical across the 147 aminoacids analyzed, showing no differences. The *Equus Caballus* sequence also shares many conserved aminoacids with the *Homo sapiens* sequence, although several substitutions are observed.
Not all nucleotide sequence variants between result in aminoacid changes, because different codons can encode the same amin acid, producing synonymous substitutions. In the alignments, the *Homo sapiens* and *Pan troglodytes* CDS sequences show some nucleotide differences, while their protein sequences remain identical.

The three species appear to be more similar at the protein level than at the CDS level. This is because some nucleotide substitutions are synonymous and do not change the encoded aminoacid. Therefore, we can identify more differences in the DNA sequences that do not always produce differences in the protein sequences.
Some protein positions remain conserved during evolution because they are essential for the protein's structure and function. In our sequence alignment, we identified two conserved Histidine residues at p.64 and p.93 corresponding to positions p.63 and p.92 in mature beta-globin, respectively. These amino acids are important for the Hemoglobin function. The distal Histidine (His63 in mature beta-globin) helps stabilize oxygen binding, while the proximal Histidine (His92 in mature beta-globin) binds directly to the iron of the heme group. Changes in these positions could affect the normal function of hemoglobin, which explains why tend to remain conserved during evolution.

Linking this with the mutant *Homo sapiens* CDS sequence, the disease-associated variant is located at a conserved position in the protein sequence. The alignment shows that Glutamic acid (Glu) at position 7 is conserved across *Homo sapiens*, *Pan troglodytes*, and *Equus caballus*. This aminoacid is located on the surface of the beta-globin protein, is negatively charged and hydrophilic. In the mutant variant that causes the sickle cell anemia, Glutamic acid is replaced by Valine (Val), which is neutral and hydrophobic. This substitution, as said earlier, changes the interactions that take place at this position and promotes the aggregation of deoxygenated HbS molecules.

---
### [Subheading Example 2]
[Text for findings...]

## Discussion
[Discuss implications, compare with existing research, and highlight limitations.]

## Conclusions
[State the main conclusions and their significance.]

## Methods
[Provide technical details for reproducibility: Data Sources, Implementation, Statistical Analysis.]

For The BLAST searches we used the selected algorithms and parameters for nucleotide and protein sequence comparisons. With The resulting alignments we evaluated the sequence identity, query coverage, E-values, substitutions, gaps, and conserved regions.

### 1.Sequence Identification Using BLAST
To identify and verify the nucleotide and protein sequences associated with sickle cell anemia, we used the Basic Local Alignment Search Tool (BLAST), available through the National Center for Biotechnology Information (NCBI).First, we analyzed the wild-type coding DNA sequence (WT CDS) and the corresponding wild-type protein sequence of the HBB gene, which encodes hemoglobin subunit beta.
We used BLAST to verify the identity of the sequences by comparing them with sequences available in the NCBI databases. We examined the gene name, chromosome location, sequence identity, query coverage, and E-value to determine whether the sequences corresponded to the HBB gene.
For nucleotide sequences, we used Nucleotide BLAST (BLASTn), while for amino acid sequences, we used Protein BLAST (BLASTp).

### 2. Comparison Between Wild-Type and Mutant Sequences
After identifying the sequences, we used BLAST to compare the wild-type and mutant versions of the HBB gene at both the nucleotide and protein levels. First, we performed a nucleotide sequence alignment between the wild-type coding DNA sequence (WT CDS) and the mutant coding DNA sequence (mutant CDS) using BLASTn. The alignment was examined to identify nucleotide substitutions, insertions, deletions, and possible changes in the reading frame. Next, we compared the wild-type and mutant protein sequences using BLASTp. This alignment allowed us to identify amino acid substitutions and examine differences between the protein sequences. For both comparisons, we analyzed the sequence alignments and their corresponding identity percentages, query coverage, and E-values.

### 3. Identification of Homologous Sequences Across Species
To identify homologous sequences of the HBB gene in other species, we used BLAST and the NCBI sequence databases. We selected three species for comparison: Homo sapiens, Pan troglodytes, and Equus caballus.
The human sequence was used as the reference sequence (Query), while the chimpanzee and horse sequences were introduced as subject sequences. First, we used BLASTn to compare the coding DNA sequences of the three species. The sequences were aligned to identify conserved nucleotide regions, substitutions, and gaps.
Afterward, we used BLASTp to perform the same comparison at the protein level, using the amino acid sequences of hemoglobin subunit beta from the three species.
The resulting alignments were examined to identify conserved amino acid regions, substitutions, and gaps.

### 4. Comparison of Nucleotide and Protein Alignments
Finally, we compared the nucleotide and protein sequence alignments obtained using BLAST.
We examined the conservation patterns across the three species at both the CDS and protein levels.
We also compared the nucleotide and amino acid variations to determine whether changes in the coding DNA sequences corresponded to changes in the protein sequences. Additionally, we examined specific amino acid positions associated with hemoglobin function and the disease-related variant identified in the human HBB gene.

For protein:

Amino acid sequence data for human beta-globin (HBB) was retrieved from the UPC Fasta File (Accession: P68871). Three-dimensional atomic coordinates for wild-type human deoxyhemoglobin (HbA) and mutant sickle cell hemoglobin (HbS) were obtained from the RCSB Protein Data Bank ID: 2hhb for and ID: 2hbs, respectively. Sequence and Structural Analysis Primary sequence alignments and mutation mapping (Glu6Val), taking into account that the numbering begins after the first amino acid of the sequence which is methionine, were performed to compare sidechain physico-chemical property transitions, for this purpose UniProtKB ID: P68871 was used for -globin subunit. Backbone torsion angles (Φ, Ψ, ω) and Ramachandran plot distributions were evaluated to assess secondary structure stability across individual subunits (Harrington et al.,1997). Structural superimposition and surface accessibility analyses were conducted using molecular 3D visualization software PyMOL, based on  crystallographic information obtained from PDB’s asymmetric unit,an x-ray diffraction crystal of 1.74 Å high resolution, to analyze non-covalent interactions and hydrophobic surface exposure at position 6, obtaining an RMSD of 0.266 Å as shown in figure #.

## Abbreviations
* **SCA:** Sickle Cell Anemia
* **AI:** Artificial Intelligence


## Declarations
* **Availability of data and materials:** [Statement on repository/access]
* **Authors' contributions:** [Specify roles]

## References
1. Author A, Author B. Title. *BMC Bioinformatics*. Year; Vol:Pages.

---

# Formatting & Style Guide

### Mini Oxford SCIMED Reference Style Guide
* References are listed alphabetically by author surname.
* When there are 4 or more authors, list the first author name followed by *et al.*
* Page spans are elided (e.g., 213–5, 137–87, 1185–2042).
* The Latin phrase *ibid* is discouraged.

#### Reference Formats
* **Journal article:** Kennedy T, Jones R. Effect of obesity on esophageal transit. *Am J Surg* 1985;149:177–81.
* **Book:** Long HC, Blatt MA, Higgins MC *et al.* *Medical Decision Making*. Boston: Butterworth-Heinemann, 1997.
* **Book chapter:** Manners T, Jones R, Riley M. Relationship of overweight to hiatus hernia and reflux oesophagitis. In: Newman W (ed.), *The Obesity Conundrum*. Amsterdam: Elsevier Science, 1997, 352–74.
* **Websites:** Public Health Laboratory Service. Antimicrobial Resistance in 2000: England and Wales. http://www.hpa.org.uk./infections/topics_az/antimicrobial_resistance/amr.pdf (7 January 2004, date last accessed).

#### In-Text Citations
* **In-text citation:** (Smith 1994)
* **Multiple citations:** List chronologically: (Smith 2015, Wong 2015, Patel 2016)

#### Quotations
* Quotations over 4 lines should be pulled out of the text, single-spaced, and indented.
* Use single quotation marks (`'...'`). Quotes within quotes use double quotation marks (`"..."`).

#### Abbreviations
* Define abbreviations at first mention in both the abstract and the text.
* Shorten units of measure (e.g., `km`).
* In running text, spell out US states. In addresses, use two-letter abbreviations.

#### Spelling & Punctuation
* Use UK spelling (`-ize` suffix) per the *Oxford English Dictionary* (https://www.oed.com/).
* Use the Oxford/serial comma.
* No comma after `i.e.` and `e.g.`, and place them within parentheses. Use `e.g.` instead of `eg.`.

#### Numbers and Dates
* Spell out numbers less than 10; use numerals for 10 and above.
* Thousand separator: Use a thin space for 10 000 and above.
* Date format: `day month year` (e.g., 23 July 2019).
