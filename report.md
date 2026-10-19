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
`Sickle Cell Anemia`, `SCA`, `Hemoglobin`, `HBB`, `Keyword`

## Background
[Explain the background to the study, its aims, and research gap.]

## Results
[Present your findings. Use subheadings as needed.]
                                          1.SEQUENCE SEARCH
                          1.1 Identification and Characterization of HBB Gene and protein
First, we compared the wild-type coding DNA sequence (WT CDS) with the protein sequence to verify that the identified protein corresponded to the gene identified in the WT CDS. We confirmed that both matched, as they shared the same gene name, HBB, and were located on the same chromosome. The gene is located on chromosome 11, specifically at locus 11p15.4, and contains three exons. It is expressed in several tissues and organs, including the lungs, fetal liver, placenta, liver, kidneys, heart, and spleen. The protein encoded by this gene is known as hemoglobin subunit beta.
                          
                          2.1 Comparison of Wild-Type and mutant Coding DNA sequences
After confirming this information, we compared the wild-type coding DNA sequence (WT CDS) with the mutated coding DNA sequence (mutant CDS). We verified that the mutant CDS corresponded to the same gene as the WT CDS, since both shared the same gene name and were located on the same chromosome. However, differences were observed in their sequence alignment results. The mutant CDS showed 100% coverage, an E-value of 0.0, and 99.55% identity, whereas the WT CDS showed 100% coverage, an E-value of 0.0, and 100% identity.
                        
                          3.1 Comparison of Wild-Type and mutant protein sequences
Finally, we compared the wild-type protein sequence with the mutated protein sequence. Both sequences corresponded to the same gene, as they shared the same name and were located on the same chromosome. Nevertheless, their sequence alignment results showed some differences. The mutant protein sequence had 100% coverage, an E-value of 5e-102, and 99.32% identity, while the WT protein sequence had 100% coverage, an E-value of 5e-103, and 100% identity.

# Hemoglobin Gene Sequences (Sickle Cell Anemia Analysis)

## Wild Type (WT) vs. Mutant CDS & Protein Comparison

### DNA Sequences (CDS)
#### Wild Type (WT) CDS
>SCA_CDS_WT
ACATTTGCTTCTGACACAACTGTGTTCACTAGCAACCTCAAACAGACACCATGGTGCATCTGACTCCTGAGGAGAAGTCT
GCCGTTACTGCCCTGTGGGGCAAGGTGAACGTGGATGAAGTTGGTGGTGAGGCCCTGGGCAGGCTGCTGGTGGTCTACCC
TTGGACCCAGAGGTTCTTTGAGTCCTTTGGGGATCTGTCCACTCCTGATGCTGTTATGGGCAACCCTAAGGTGAAGGCTC
ATGGCAAGAAAGTGCTCGGTGCCTTTAGTGATGGCCTGGCTCACCTGGACAACCTCAAGGGCACCTTTGCCACACTGAGT
GAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCTGGGCAACGTGCTGGTCTGTGTGCTGGCCCA
TCACTTTGGCAAAGAATTCACCCCACCAGTGCAGGCTGCCTATCAGAAAGTGGTGGCTGGTGTGGCTAATGCCCTGGCCC
ACAAGTATCACTAAGCTCGCTTTCTTGCTGTCCAATTTCTATTAAAGGTTCCTTTGTTCCCTAAGTCCAACTACTAAACT
GGGGGATATTATGAAGGGCCTTGAGCATCTGGATTCTGCCTAATAAAAAACATTTATTTTCATTGCAA

#### Mutant CDS
>SCA_CDS_mutant
ATGGTGCACCTGACTCCTGTGGAGAAGTCTGCCGTTACTGCCCTGTGGGGCAAGGTGAACGTGGATGAAGTTGGTGGTGA
GGCCCTGGGCAGGCTGCTGGTGGTCTACCCTTGGACCCAGAGGTTCTTTGAGTCCTTTGGGGATCTGTCCACTCCTGATG
CTGTTATGGGCAACCCTAAGGTGAAGGCTCATGGCAAGAAAGTGCTCGGTGCCTTTAGTGATGGCCTGGCTCACCTGGAC
AACCTCAAGGGCACCTTTGCCACACTGAGTGAGCTGCACTGTGACAAGCTGCACGTGGATCCTGAGAACTTCAGGCTCCT
GGGCAACGTGCTGGTCTGTGTGCTGGCCCATCACTTTGGCAAAGAATTCACCCCACCAGTGCAGGCTGCCTATCAGAAAG
TGGTGGCTGGTGTGGCTAATGCCCTGGCCCACAAGTATCACTAA


| Variant | Coverage | Identity | E-value |
| --- | --- | --- | --- |
| WTF | 100% | 100% | 0.0 |
| Mutant | 100% | 99.55% | 0.0 |


### Protein sequence
#### Wild type (WT) Protein
>SCA_protein_WT
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

#### Mutant Protein
>SCA_protein_mutant
MVHLTPVEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH


| Variant | Coverage | Identity | E-value |
| --- | --- | --- | --- |
| WTF | 100% | 100% | $5 \times 10^{-103}$ |
| Mutant | 100% | 99.32% | $5 \times 10^{-102}$ |


### Overview 


The gene that causes sickle cell anemia and the one that codes Hemoglobin is called HBB, found on the chromosome 11 with 11p15.4 as locus. Has accession: NM_000518.5 
The protein name is hemoglobin subunit beta (other names: Hb Monza protein, beta globin chain, hemoglobin beta subunit, hemoglobin, beta), found on gene HBB with accession NC_000011.10 / NP_000509.1 
The protein corresponds to the gene identified and both also share the same locus on chromosome 11. The gene has 3 exons and it’s expressed principally on the:
1. Lung
2. Liver (fetal)
3. Placenta
4. Spleen (-->bazo)
5. Heart
6. Liver


## Wild Type (WT) CDS & Protein Sequences for HBB Homologs

### Assigned Species: *Equus caballus*

#### DNA Sequence
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

#### Protein sequence
>NP_001157490.1 hemoglobin subunit beta [Equus caballus]
MVQLSGEEKAAVLALWDKVNEEEVGGEALGRLLVVYPWTQRFFDSFGDLSNPGAVMGNPKVKAHGKKVLHSFGEGVHHLD
NLKGTFAALSELHCDKLHVDPENFRLLGNVLVVVLARHFGKDFTPELQASYQKVVAGVANALAHKYH

| Gene | Accession | Coverage | Identity | E-value |
| --- | --- | --- | --- | --- |
| **HBB** | `NP_001157490.1` | 100% | 83.67% | $7 \times 10^{-80}$ |


### Other Homolog Species: *Pan Troglodytes*

#### DNA Sequence
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

#### Protein Sequence
>XP_508242.1 hemoglobin subunit beta [Pan troglodytes]
MVHLTPEEKSAVTALWGKVNVDEVGGEALGRLLVVYPWTQRFFESFGDLSTPDAVMGNPKVKAHGKKVLGAFSDGLAHLD
NLKGTFATLSELHCDKLHVDPENFRLLGNVLVCVLAHHFGKEFTPPVQAAYQKVVAGVANALAHKYH

| Gene | Accession | Coverage | Identity | E-value |
| --- | --- | --- | --- | --- |
| **HBB** | `XP_508242.1` | 100% | 100% | $2 \times 10^{-106}$ |



# Sequence alignment
## Wild type (WT) with mutant 
### mRNA sequence
### Protein sequence


## Wild Type (WT) [Homo sapiens] with homologs
### mRNA sequence
### Protein sequence


### [Subheading Example 1]
[Text for findings...]

### [Subheading Example 2]
[Text for findings...]

## Discussion
[Discuss implications, compare with existing research, and highlight limitations.]

## Conclusions
[State the main conclusions and their significance.]

## Methods
[Provide technical details for reproducibility: Data Sources, Implementation, Statistical Analysis.]

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
