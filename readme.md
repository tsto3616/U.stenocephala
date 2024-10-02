---
bibliography: references.bib
---

# Navigating this repository:

Welcome to the repository for the study of *Uncinaria stenocephala* genomics. Within this repository, we focus primarily on *U. stenocephala* and its genomics and or transcriptomics; however, we draw on the genomics of four hookworms (Ancylostomatidae), two members of Strongylidae and one member of Chabertidae. These seven comparative genomes were selected for their varied lifecycles and pathogenesis, as well as their close relationship with U. stenocephala. The contents of this repository as split into four sections: (1) sampling and sequencing, (2) data preparation and annotation, (3) genomics and transcriptomics and (4) pipeline development and practicing. vvvvvvvvvvv

# Why *Uncinaria stenocephala*?

U. stenocephala is the most common hookworm of European dogs (Martinez-Moreno et al. 2007), despite this, this hookworm remains vastly understudied. Much of this species remains unknown, particularly its pathogenic potential - the focus of this study. Among much of the literature it is considered to be clinically irrelevant. This assumption possibly originated from the unpublished conclusions set out by Miller (1968), in which the authors concluded that the blood loss from infection and haemotophagy of *U. stenocephala* is negligible. However, there is significant evidence to suggest that there is immunopathology associated with infection (Gibbs 1958; DOW et al. 1959; Gorski et al. 1999), undermining the claims of clinical irrelevance. If this parasite proves to be pathogenic, there must be reconsideration of the current hookworm management practices of dogs - particularly in temperate regions. Within temperate regions canine hookworms are considered to be exclusively consisting of *U. stenocephala* infections, thus in temperate regions hookworm infections are considered to be clinically irrelevant.

# Can genomics establish pathogenicity?

The seminal review by @vineyGenomicBasisNematode2018

[@vineyGenomicBasisNematode2018] establishes three pipelines for the identification of mechanisms believed to underline the evolution of parasitism. These approaches are not mutually exclusive and consist of:

1.  Compare free living and parasitic life cycles of different species.
2.  Compare free living and parasitic life cycles within the same species, applying transcriptomics to observe the expression patterns of certain gene families.
3.  Discover excretory and or secretory proteins (ESPs) of the species.

Although this study focuses on the pathogenicity rather than the evolution of parasitism, the same fundamental principles apply. Rather than apply all three approaches, due to logistical constraints, the first and third approaches were utilised. The need to culture free living stages, the cost of multiple rounds of transcriptomics and the time required to process the extra data proved to be unrealistic for the timeline of this project.

### Comparing a variety of pathogenic states, through genomics:

The first pipeline can easily be adapted to the study of pathogenic potential and or mechanisms. Reflecting upon a review of Nematoda and the associated taxonomy

it was decided that of the order, Rhabditina, three families serve as suitable comparisons for the study of *U. stenocephala* and its pathogenic potential. These three families are Ancylostomatidae, Chabertidae and Strongylidae. Although other families are suspected to be closely related to *U. stenocephala*, these three families are sufficient in their diverse life cycles and pathogenic mechanisms. Nematodes chosen for genomic comparisons are limited to species with their entire genome sequenced, greatly limiting the list of available comparisons. Of the family Ancylostomatidae, four species of hookworms were chosen - these were *Ancylostoma caninum, Ancylostoma ceylaniucm, Ancylostoma duodenale* and *Necator americanus*. One species (*Oesophagostomum dentatum*) of Chabertidae and two species (*Cyclicostephanus goldi* and *Strongylus vulgarus*) of Strongylidae were also selected for comparisons. All seven comparative genomes will serve as controls, used to study the expansion and shrinking of gene families. These gene families will be compared with existing literature, with the hopes of identifying a role for each suspected pathogenic gene family. If associations with pathogenicity can be established, these gene families will then be compared to *U. stenocephala* in order to study the expansion or break down of gene families.

These control genomes vary greatly in lifecycle and pathogenic potential, as shown in Table 1. The hookworms *A. caninum, A. ceylanicum* and *A. duodenale* will serve as controls for high rates of haemorrhaging and blood consumption, with relatively little pathology otherwise. *N. americanus* will be used for an intermediate control, whereby minimal blood loss and blood consumption is observed. *O. dentatum* will serve as a non pathogenic control, with minimal pathogenesis. *C. goldi* will remain as the immunopathology positive control. *S. vulgaris* is a control for significant haemorrhaging in the absence of significant blood consumption. Further justification of this experimental design and greater depth and detail of the life cycles of each species will be included in the Genomics and Transcriptomics branch.

![Table 1: A brief visual representation of the controls, compared to our hookworm of interest *Uncinaria stenocephala*. Red represents drastic pathology, orange represents intermediate and yellow represents minimal pathology. ??? denotes a suspected/ unevaluated effect of pathology.](images/Picture1.png)

### 

### Studying the ESPs of *Uncinaria stenocephala*:

A hybrid approach will be entailed for the identificaiton of potential ESPs, which are frequently identified as pathogenic agents of parasites **REF**. This hybrid approach involves combining transcriptomics and screening for the molecular weight of known ESPs of *U. stenocephala* to identify:

1.  Gene families relatively over or under expressed.
2.  ESPs as determined by proteomics, through the estimation of molecular weights gathered from transcriptomic data.
3.  The relative expression of ESPs detected through proteomics.

This hybrid approach is ideal to circumevent the mismatch between transcritpomic expression levels and protein levels - observed fior nematode ESPs **REF**. In addition, it avoids assumptions of over expressed genes representing ESPs. It also enables the detection fo ESPs that are infrequently expressed, perhaps in response to the move towards a symbonic relationship - rather than a pathogenic relationship with the host. The most significant of all benefits; however, is its ability to provide the foundations for the quantification of ESPs in the absence of proteomic measures of abundance. This would be of great benefit to the study of *U. stenocephala* considering that the only two proteomic studies of *U. stenocephala* **REFS** fail to quantify the abundance of ESPs. testing 1234

DOW, C., W. F. JARRETT, F. W. JENNINGS, W. I. McINTYRE, and W. MULLIGAN. 1959. “The production of active immunity against the canine hookworm Uncinaria stenocephala.” *Journal of the American Veterinary Medical Association* 135 (October): 407–11.

Gibbs, H. C. 1958. “On the Gross and Microscopic Lesions Produced by the Adults and Larvae of Dochmoides Stenocephala (Raillet, 1884) in the Dog.” *Can J Comp Med Vet Sci* 22 (11): 382–85. <https://www.ncbi.nlm.nih.gov/pubmed/17649092>.

Gorski, P, M Krawiec, JM Behnke, and H Wędrychowicz. 1999. “Mast Cell, Eosinophil and IgE Antibody Response of BALB/c Mice to Percutaneous Infection with the Canine Hookworm Uncinaria Stenocephala.”

Martinez-Moreno, F. J., S. Hernandez, E. Lopez-Cobos, C. Becerra, I. Acosta, and A. Martinez-Moreno. 2007. “Estimation of Canine Intestinal Parasites in Cordoba (Spain) and Their Risk to Public Health.” *Vet Parasitol* 143 (1): 7–13. <https://doi.org/10.1016/j.vetpar.2006.08.004>.

Miller, T. A. 1968. “Pathogenesis and Immunity in Hookworm Infection.” *Trans R Soc Trop Med Hyg* 62 (4): 473–89. [https://doi.org/10.1016/0035-9203(68)90130-2](https://doi.org/10.1016/0035-9203(68)90130-2).
