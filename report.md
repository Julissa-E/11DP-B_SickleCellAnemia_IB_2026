# Sickle Cell Anemia: A Bioinformatics study

**Authors:** [J.P. Espejo, M. Sarrias, S. Delcazo, M.D. Viella, U. Saltó]  
**Affiliation:** [Introduction to Bioinformatics, UPC, Barcelona, Spain]  

> **Limits & Guidelines:**
> * Maximum limit of **7 pages** or **5000 words** (whichever is shorter).
> * References do not contribute to page or word count (more than 1 page of references is not recommended).
> * Maximum of **5 figures or tables** must be respected and stored in the repository.

---

## Abstract
[Provide a structured abstract covering Background, Results, and Conclusions (Max 350 words).]

## Keywords
`Sickle Cell Anemia`, `SCA`, `Hemoglobin`, `HBB`, `HbS`

## Background
Part of background
The beta-globin, which is made by the gene HBB, is a subunit of a larger protein called hemoglobin, that contains 147 amino acids, located inside the red blood cells. It is  involved in the transport of oxygen from the lungs to other tissues around the body. 

For infants through adults, the hemoglobin consists of four protein subunits: Two beta-globins and two alpha globins. All of these subunits are bound to an iron-containing molecule called heme and consequently each heme can bind to one oxygen molecule.  (1)

The aim of our research is to understand the mutation in the beta-globin at chromosome 11 when two HbS alleles, one from each parent, passes it on to their progeny . Studies show that when this scenario occurs, the coding of the amino acid is affected, therefore in the sequence at, position 6, instead of obtaining a glutamic acid, there is a valine (E6V) which changes some properties of the residues that will affect the overall function of such protein.


## Results

The analysis of data sources containing nucleotide and protein sequences allowed us to identify similarities and differences between the sequences studied.

### Sequence comparison
                                          
#### Identification and Characterization of HBB gene and protein

Using BLAST, we compared the wild type (WT) Coding DNA Sequence (CDS) with the protein sequence, to verify that the identified protein corresponded to the gene identified in the WT CDS. Both matched, as they shared the same gene name, HBB, and were located on chromosome 11, with locus 11p15.4, the gene coding for the HBB protein, Hemoglobin-subunit beta, contained three exons. HBB it's expressed in several tissues and organs, including the lungs, fetal liver, placenta, liver, kidneys, heart, and the spleen. 
                          
#### Comparison of Wild Type and Mutant CDS and Protein sequences 
##### Comparison of Coding DNA Sequences 
After confirming the match, we compared the Wild type (WT) CDS, with the Muatnt CDS. We assured that the Mutant CDS corresponded to the same gene as the Wild type CDS, sharing both the same locus and gene name. However, differences were observed in their sequence alignment results;

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

The table illustrates the difference in the BLAST results comparing the Wild type CDS with the Mutant one:

| Variant | Coverage | Identity | E-value |
| --- | --- | --- | --- |
| WTF | 100% | 100% | 0.0 |
| Mutant | 100% | 99.55% | 0.0 |



#### Comparison of protein sequences
Finally, we compared the Wild type protein sequence with the Mutant protein sequence. We assured that both sequences were coded from the same gene, HBB, and had the same locus. Nevertheless, their sequence alignment results showed some differences; 

###### Wild type (WT) Protein
>SCA_protein_WT
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

###### Mutant Protein
>SCA_protein_mutant
MVHLTPVEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

The table illustrates the differences obtained after the BLAST search, comparing both protein sequences- 

| Variant | Coverage | Identity | E-value |
| --- | --- | --- | --- |
| WTF | 100% | 100% | $5 \times 10^{-103}$ |
| Mutant | 100% | 99.32% | $5 \times 10^{-102}$ |


#### Comparison of Wild type sequence with homologs sequences
##### Assigned Species: *Equus caballus*

###### DNA Sequence
>NM_001164018.1 Equus caballus hemoglobin, beta (HBB), mRNA
ATGGTGCAACTGAGTGGTGAAGAGAAGGCAGCTGTCTTGGCCCTGTGGGACAAGGTGAATGAGGAAGAAGTTGGTGGTGA
AGCCCTGGGCAGGCTGCTGGTTGTCTACCCATGGACTCAGAGGTTCTTTGACTCCTTTGGGGATCTGTCCAATCCTGGTG
CTGTGATGGGCAACCCCAAGGTGAAGGCCCACGGCAAGAAAGTGCTACACTCCTTTGGTGAGGGCGTGCATCATCTTGAC
AACCTCAAGGGCACCTTTGCTGCGCTGAGTGAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCT
GGGCAACGTGCTGGTTGTTGTGCTGGCTCGCCACTTTGGCAAGGATTTCACCCCAGAGTTGCAGGCTTCCTATCAAAAGG
TGGTGGCTGGTGTGGCCAATGCACTGGCCCACAAATACCACTGA

| Gene | Accession | Coverage | Identity | E-value |
| --- | --- | --- | --- | --- |
| **HBB** | `NM_001164018.1` | 70% | 87% | $2 \times 10^{-138}$ |

###### Protein sequence
>NP_001157490.1 hemoglobin subunit beta [Equus caballus]
MVQLSGEEKAAVLALWDKVNEEEVGGEALGRLLVVYPWTQRFFDSFGDLSNPGAVMGNPKVKAHGKKVLHSFGEGVHHLD
NLKGTFAALSELHCDKLHVDPENFRLLGNVLVVVLARHFGKDFTPELQASYQKVVAGVANALAHKYH

| Gene | Accession | Coverage | Identity | E-value |
| --- | --- | --- | --- | --- |
| **HBB** | `NP_001157490.1` | 100% | 83.67% | $7 \times 10^{-80}$ |


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

| Gene | Accession | Coverage | Identity | E-value |
| --- | --- | --- | --- | --- |
| **HBB** | `XM_508242.5` | 100% | 99.84% | 0.0 |

###### Protein Sequence
>XP_508242.1 hemoglobin subunit beta [Pan troglodytes]
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

| Gene | Accession | Coverage | Identity | E-value |
| --- | --- | --- | --- | --- |
| **HBB** | `XP_508242.1` | 100% | 100% | $2 \times 10^{-106}$ |


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



### Sickle Cell Anemia in humans
[The beta-globin, which is made by the gene HBB, is a subunit of a larger protein called hemoglobin, that contains 147 amino acids (reference to the sequence in whichever file is located), located inside the red blood cells. It is  involved in the transport of oxygen from the lungs to other tissues around the body. 
For infants through adults, the hemoglobin consists of four protein subunits: Two beta-globins and two alpha globins. All of these subunits are bound to an iron-containing molecule called heme and consequently each heme can bind to one oxygen molecule.  (1)

(Include information about the other mutation that is synonymous but not affecting) The focus of our research is the impact the mutation has in the beta-globin subunit when the gene transcription fails at chromosome 11. When this scenario occurs, the coding of the amino acid is affected therefore in the sequence at position 6, instead of obtaining a glutamic acid, there is a valine, E6V.

The change in the sequence of these amino acids has a great impact on the structure, charge, interactions with other molecules, size and resulting functions of the protein.

Here is a detailed chart with the main differences between the hemoglobin beta-subunit and mutant HBs.
### Comparative Analysis: Normal Human Beta-Globin Subunit (HBB) vs. Sickle Cell Beta-Globin Subunit (HbS)

---

#### Primary & Secondary Structure Organization

| Feature / Question | Wild-Type Beta Subunit ($\text{HBB}$ / $\text{HbA}$) | Sickle Cell Beta Subunit ($\text{HbS}$) |
| :--- | :--- | :--- |
| **Primary Structure & Sidechain Properties** | **147 amino acids** (mature chain). Position 6: **Glutamic Acid ($\text{Glu} / \text{E}$)** — Charged/Acidic, hydrophilic. Contains non-polar ($\text{Val}, \text{Leu}$), polar ($\text{Ser}, \text{Thr}$), charged ($\text{Lys}, \text{Asp}$), and atypical residues ($\text{Gly}, \text{Pro}, \text{Cys}$). | **147 amino acids** (mature chain). Position 6: **Valine ($\text{Val} / \text{V}$)** ($\text{Glu6Val}$) — Hydrophobic, non-polar aliphatic. All other 146 amino acids and sidechain categories are identical. |
| **Dihedral Angles ($\phi, \psi, \omega$) & Ramachandran Plot** | $\omega \approx 180^\circ$ (trans peptide bond). $\approx 75-80\%$ of residues fall into the **right-handed $\alpha$-helix region** ($\phi \approx -60^\circ, \psi \approx -45^\circ$). Inter-helical loops show variable angles; $\text{Gly}$/$\text{Pro}$ occupy unique flex/kink regions. | Identical mainchain torsion angles ($\phi, \psi, \omega$) across the subunit fold. Position 6 retains its $\alpha$-helical backbone conformation near the N-terminus of Helix A. |
| **Secondary Structure Elements** | Composed of **8 right-handed $\alpha$-helices** (helices A through H) connected by short inter-helical loops and turns. No $\beta$-sheets or $\beta$-strands present. | Composed of the same **8 right-handed $\alpha$-helices** (helices A through H) and loop connections. |
| **Supersecondary Motifs** | Consists of **$\alpha$-$\alpha$ structural motifs** (helix-turn-helix packing arrangements that enclose the hydrophobic heme pocket). Lacks $\beta$-hairpins, meanders, or $\beta$-$\alpha$-$\beta$ crossovers. | Identical **$\alpha$-$\alpha$ structural motifs**. |

---

#### Tertiary & Quaternary Structure

| Feature / Question | Wild-Type Beta Subunit ($\text{HBB}$ / $\text{HbA}$) | Sickle Cell Beta Subunit ($\text{HbS}$) |
| :--- | :--- | :--- |
| **Tertiary Domains** | Single-domain protein subunit consisting of a single compact **Globin domain**. | Single-domain protein subunit consisting of a single compact **Globin domain**. |
| **Quaternary Structure & Subunit Composition** | Assembles with two $\alpha$-globin chains ($\text{HBA}$) to form a **hetero-oligomer** ($\alpha_2\beta_2$). | Assembles with two $\alpha$-globin chains ($\text{HBA}$) to form a **hetero-oligomer** ($\alpha_2\beta_2^S$). Under deoxygenation, tetramers associate into **supramolecular polymer fibers**. |
| **Type of Oligomer** | **Tetramer** ($\alpha_2\beta_2$ functional hemoglobin unit). | **Tetramer** ($\alpha_2\beta_2^S$) at normal physiological state; forms long **14-strand helical fibers/polymers** upon deoxygenation. |
| **Protein Morphological Type** | **Globular protein** (compact spherical shape soluble in aqueous cytoplasm). | Individual tetramers are **globular**; polymerizes into **fibrous assemblies** inside red blood cells when deoxygenated. |

---

#### Principles of Architecture & Stabilizing Forces

| Feature / Question | Wild-Type Beta Subunit ($\text{HBB}$ / $\text{HbA}$) | Sickle Cell Beta Subunit ($\text{HbS}$) |
| :--- | :--- | :--- |
| **Non-Covalent Stabilizing Forces** | Core stabilized by the **hydrophobic effect**. Internal hydrogen bonds stabilize the $\alpha$-helices. Salt bridges and electrostatic interactions stabilize tertiary/quaternary interfaces (e.g., $\text{BPG}$ binding). | Identical internal non-covalent forces. Additionally, deoxygenation exposes hydrophobic $\text{Val6}$, which forms **inter-tetramer hydrophobic interactions** with a pocket ($\text{Phe85}, \text{Leu88}$) on an adjacent $\beta$-chain. |
| **Covalent Stabilizing Interactions** | **None.** No intramolecular or intermolecular disulfide bridges ($-\text{S}-\text{S}-$) exist in functional adult hemoglobin. | **None.** No disulfide bridges are involved in subunit folding or polymer fiber formation. |
| **Core vs. Surface Residue Distribution** | Densely packed **hydrophobic core** ($\text{Leu}, \text{Val}, \text{Ile}, \text{Phe}$) surrounding the heme group. Charged ($\text{Glu}, \text{Lys}, \text{Arg}$) and polar residues exposed on the hydrophilic surface. $\text{Glu6}$ is fully exposed. | Hydrophobic core and overall surface charge distribution are identical, **except at position 6**, where a non-polar **Valine** is pathologically exposed on the outer surface. |

---

#### SCOP Structural Classification

| Feature / Question | Wild-Type Beta Subunit ($\text{HBB}$ / $\text{HbA}$) | Sickle Cell Beta Subunit ($\text{HbS}$) |
| :--- | :--- | :--- |
| **SCOP Class** | **All $\alpha$-proteins** | **All $\alpha$-proteins** |
| **SCOP Fold** | **Globin-like** (8-helix bundle surrounding a heme prosthetic group) | **Globin-like** |
| **SCOP Superfamily** | **Globins** | **Globins** |
| **SCOP Family** | **Globin** (PDB: `2HHB`, UniProt: `P68871`) | **Globin** (PDB: `2HBS`, UniProt: `P68871` variant `VAR_002863`) |

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


## Abbreviations
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
