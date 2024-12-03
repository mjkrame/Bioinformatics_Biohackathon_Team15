# Bioinformatics_Biohackathon_Team15
**Clemson BCHM4400 Biohackathon Project: Team 15**

## Group Members
- Will McIntyre
- Mackenzie Kramer
- Michaela Mulvey
- Eve Joseph
- Adam Gatch

## Task A: Connecting with the team
On November 30th, the team's repository was created and shared with all group members. An email was sent introducing the project, outlining the various roles available, and requesting each member's preferences based on their comfort level and experience. The email also invited suggestions for diseases to study. Email collaboration and discussion continued from November 30th until December 2nd as the team decided on the disease of interest and assigned roles. To better facilitate communication, an iMessage group chat was created.

## Task B: Selecting a disease to study
Huntington's disease (HD) is a fatal neurodegenerative disease characterized by a number of progressive neurologic defects ultimately resulting in death. Signs and symptoms of HD generally begin in middle adulthood between the ages of 30 and 50 years. Initially, HD patients frequently show psychiatric symptoms including mood changes, depression, apathy, and other changes in mental state. Initial physical symptoms include uncontrollable jerky movements known as chorea, and movement dysfunction progresses to rigidity, abnormal posturing, and tremor-like symptoms. Additionally, as the disease progresses, patients experience significant difficulty with tasks requiring motor control, ultimately progressing to a physical condition requiring full-time support from caregivers. Completing a symptomatic triad, HD patients also show progressive cognitive decline towards dementia. HD patients experience progressive difficulty with executive functions such as planning, abstract thinking, behavioral control, and problems with memory begin to appear later in disease. Death usually occurs 15-20 years after onset of disease, most commonly due to aspiration pneumonia. Neuropathologically, HD is characterized by heavy neuronal loss within the striatal part of the basal ganglia and deep layers of the cerebral cortex. Atrophy and neuronal loss are also frequently seen in other brain regions such as the hippocambus, thalamus, subthalamic nucleus, substantia nigra, and cerebellum, with volumetric loss within affected regions frequently on the order of 20-60%. While the neuropathological presentation of HD is dependent on stage of disease, some findings such as caudate volume loss and white matter disorganization appear before the onset of obvious disease symptoms. Currently, there is no cure for HD and no treatment options effective in stopping or reversing the progression of dissease. However, treatments can alleviate certain symptoms in some cases, and tetrabenazine is frequently employed to treat movement problems in HD. Patients with early-stage HD often benefit from physical therapy and speech therapy, though the benefits from these treatments are ultimately temporary. In late-stages, full-time care is required as HD patients lose the ability to care for themselves, and palliative care is frequently employed to improve quality of life and reduce stress. 

## Task C: Find a gene underlying the disease
HD is caused by mutation of the HTT gene, which is located on chromosome 4 and encodes the protein huntingtin. Specifically, HTT posesses a trinoclueotide repeat expansion that is mutated in HD cases to contain many more repeats than normal, causing production of mutant huntingtin (mHtt). Due to this mutation, HD displays an autosomal dominant inheritance pattern. HTT is normally expressed at highest levels within the brain, and this holds true in HD. While expression levels of HTT are not necessarily altered in HD cases, the abnormal protein product mHtt is known to aggregate and mediate toxicity via several potential mechanisms. Three hypotheses for how HTT mutation (resulting in production of mHtt) leads to disease include the following: 1) mHtt abnormally interacts with transcription factors within the nucleus, resulting in transcriptional dysregulation and altered expression of critical genes necessary for cellular function and survival. 2) mHtt forms neurotoxic aggregates that impair the ability of the cell to degrade protein and directly disrupt cell structure and/or function. 3) mHtt induces mitochondrial dysfunction via aberrant interaction resulting in altered permeability and other defects.

## Task D: Build a protein:protein interaction (PPI) network using the known gene protein product(s) as seeds

## Task E: Find tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes
Find tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes
An eQTL, is a genetic locus that explains a fraction of the genetic variance of a gene expression phenotype. In other words, eQTLs are genetic variants that influence the expression levels of one or more genes. In the context of the human organism, eQTLs play a crucial role in understanding how genetic variations contribute to differences in gene expression among individuals. This is important because variations in gene expression can lead to differences in traits, including susceptibility to diseases such as HD.

Regarding the HTT gene, after focusing on eQTLs within brain tissues the significant (p-value < e-05) eQTLS identified include those with SNP ID's:
* rs13106262
* rs10007398
* rs28616835
* rs112435590
* rs113331544
* rs10009935

Of those significant eQTLs, SNP ID:rs13106262 is specific to the basal ganglia and SNP ID:rs10007398 is specific to the cortex which are more of interest for our research hypothesis. Information for these eQTLs is below:
* Gencode Id                  ENSG00000197386.14
Gene Symbol                                HTT
Variant Id                chr4_3563897_G_C_b38
SNP Id                              rs13106262
P-Value                                    0.0
NES                                      -0.23
Tissue         Brain - Caudate (basal ganglia)

* Gencode Id       ENSG00000197386.14
Gene Symbol                     HTT
Variant Id     chr4_3522136_A_G_b38
SNP Id                   rs10007398
P-Value                    0.000007
NES                            0.11
Tissue               Brain - Cortex

Given this information, presence of the first eQTL (SNP rs13106262) shows a decrease in HTT expression in the basal ganglia. In contrast, the presence of the second eQTL (SNP rs10007398) is associated with an increase in HTT expression in the cortex of the brain. 

## Task F: Construct an hypothesis that the genes caused the disease phenotype by mechanism X
The mutant huntingtin protein (mHtt) causes Huntington's disease phenotypes primarily through abnormal interactions with transcription factors in the nucleus, resulting in widespread transcriptional dysregulation of genes critical for neuronal function and survival.
