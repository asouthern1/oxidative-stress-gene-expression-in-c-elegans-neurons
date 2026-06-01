# Exploratory Analysis of Oxidative Stress–Associated Genes in Adult Dopaminergic Neurons

## Project Overview

This project investigates the expression of oxidative stress–associated genes across adult neuronal populations in *Caenorhabditis elegans* using publicly available single-cell RNA sequencing data from the CeNGEN consortium.

Oxidative stress contributes to aging, neuronal dysfunction, and neurodegeneration. Dopaminergic neurons are particularly susceptible to oxidative damage due to dopamine metabolism and reactive oxygen species production. Understanding neuron-specific expression of stress-response genes may provide insight into mechanisms that contribute to neuronal resilience and vulnerability.

---

## Research Question

How do oxidative stress–associated genes differ in expression across adult *C. elegans* neuronal populations, particularly within dopaminergic neuron subclasses?

---

## Biological Background

Several genes involved in oxidative stress regulation and insulin signaling were selected for analysis:

### age-1

*age-1* encodes a phosphatidylinositol 3-kinase involved in the insulin/IGF-1 signaling pathway, a major regulator of aging and stress responses in *C. elegans*.

### sod-3

*sod-3* encodes a mitochondrial superoxide dismutase that protects cells from reactive oxygen species and oxidative damage.

### skn-1

*skn-1* is a transcription factor that regulates antioxidant and detoxification pathways and serves as a major oxidative stress-response regulator.

---

## Dataset

**Source:** CeNGEN Adult Single-Cell RNA Sequencing Dataset

**Organism:** *Caenorhabditis elegans*

**Neuron Classes of Interest:**

* ADE
* CEP
* PDE

Additional neuronal populations were examined to identify broader expression patterns across the nervous system.

---

## Methods

1. Retrieved gene expression data from the CeNGEN adult single-cell RNA sequencing dataset.
2. Selected oxidative stress–associated genes (*age-1*, *sod-3*, and *skn-1*).
3. Examined transcript abundance across neuronal populations.
4. Visualized expression patterns using a dot plot where:

   * Dot size represents the proportion of cells expressing the gene.
   * Color intensity represents scaled transcript abundance (TPM).
5. Compared expression patterns among dopaminergic neuron subclasses.

---

## Results

### Oxidative Stress Gene Expression Across Adult Neurons

# Exploratory Analysis of Oxidative Stress–Associated Genes in Adult Dopaminergic Neurons

## Project Overview

This project investigates the expression of oxidative stress–associated genes across adult neuronal populations in *Caenorhabditis elegans* using publicly available single-cell RNA sequencing data from the CeNGEN consortium.

Oxidative stress contributes to aging, neuronal dysfunction, and neurodegeneration. Dopaminergic neurons are particularly susceptible to oxidative damage due to dopamine metabolism and reactive oxygen species production. Understanding neuron-specific expression of stress-response genes may provide insight into mechanisms that contribute to neuronal resilience and vulnerability.

---

## Research Question

How do oxidative stress–associated genes differ in expression across adult *C. elegans* neuronal populations, particularly within dopaminergic neuron subclasses?

---

## Biological Background

Several genes involved in oxidative stress regulation and insulin signaling were selected for analysis:

### age-1

*age-1* encodes a phosphatidylinositol 3-kinase involved in the insulin/IGF-1 signaling pathway, a major regulator of aging and stress responses in *C. elegans*.

### sod-3

*sod-3* encodes a mitochondrial superoxide dismutase that protects cells from reactive oxygen species and oxidative damage.

### skn-1

*skn-1* is a transcription factor that regulates antioxidant and detoxification pathways and serves as a major oxidative stress-response regulator.

---

## Dataset

**Source:** CeNGEN Adult Single-Cell RNA Sequencing Dataset

**Organism:** *Caenorhabditis elegans*

**Neuron Classes of Interest:**

* ADE
* CEP
* PDE

Additional neuronal populations were examined to identify broader expression patterns across the nervous system.

---

## Methods

1. Retrieved gene expression data from the CeNGEN adult single-cell RNA sequencing dataset.
2. Selected oxidative stress–associated genes (*age-1*, *sod-3*, and *skn-1*).
3. Examined transcript abundance across neuronal populations.
4. Visualized expression patterns using a dot plot where:

   * Dot size represents the proportion of cells expressing the gene.
   * Color intensity represents scaled transcript abundance (TPM).
5. Compared expression patterns among dopaminergic neuron subclasses.

---

## Results

### Oxidative Stress Gene Expression Across Adult Neurons

![Oxidative Stress Gene Expression](figures/oxidative_stress_dotplot.png)

**Figure 1.** Dot plot showing expression of oxidative stress–associated genes across adult *C. elegans* neuronal populations. Dot size represents the proportion of cells expressing the gene, while color intensity indicates scaled transcript abundance.

### Key Findings

* *age-1* expression was broadly distributed across neuronal populations.
* *sod-3* expression demonstrated neuron-specific variability and differential abundance.
* *skn-1* expression was highly restricted and concentrated within a limited subset of neurons.
* Dopaminergic neuron subclasses exhibited distinct expression profiles, supporting transcriptomic heterogeneity within the dopaminergic system.

### Dopaminergic Neuron Expression

| Gene  | ADE     | PDE | CEP    |
| ----- | ------- | --- | ------ |
| age-1 | 235.083 | 0   | 33.962 |
| sod-3 | 113.354 | 0   | 54.171 |
| skn-1 | 0       | 0   | 0      |

ADE neurons demonstrated the highest expression of both *age-1* and *sod-3*. CEP neurons exhibited moderate expression of these genes, while PDE neurons showed little to no detectable expression. Baseline *skn-1* expression was not detected in ADE, CEP, or PDE neurons.

---

## Discussion

The results suggest substantial transcriptomic heterogeneity among adult dopaminergic neuron subclasses.

The coordinated expression of *age-1* and *sod-3* within ADE and CEP neurons may indicate differential activation of insulin-signaling and oxidative stress-response pathways. These findings support the possibility that individual dopaminergic neuron populations utilize distinct protective mechanisms to respond to oxidative stress.

The limited detection of *skn-1* suggests either neuron-specific regulation or expression levels below the detection threshold within the neuronal populations examined.

Because oxidative stress is strongly implicated in aging and neurodegenerative disease, further investigation of these pathways may provide insight into mechanisms underlying neuronal vulnerability and resilience.

---

## Skills Demonstrated

### Bioinformatics

* Single-cell RNA sequencing analysis
* Transcriptomic data interpretation
* Gene expression profiling
* Biological data visualization

### Computational Biology

* CeNGEN dataset analysis
* Neurobiology-focused data exploration
* Oxidative stress pathway investigation

### Data Science

* Exploratory data analysis
* Scientific communication
* Data visualization
* Biological hypothesis generation

---

## Future Directions

* Expand analysis to additional oxidative stress and aging-associated genes.
* Investigate differential expression across developmental stages.
* Perform pathway enrichment analyses.
* Examine neuron-specific signatures associated with neurodegeneration.
* Compare stress-response pathways across multiple neuronal subclasses.

---

## Author

**Autumn Southern, M.S. Biotechnology**

Interests: Bioinformatics, Aging Biology, Neurodegeneration, Transcriptomics, Genomics, and Computational Biology.


**Figure 1.** Dot plot showing expression of oxidative stress–associated genes across adult *C. elegans* neuronal populations. Dot size represents the proportion of cells expressing the gene, while color intensity indicates scaled transcript abundance.

### Key Findings

* *age-1* expression was broadly distributed across neuronal populations.
* *sod-3* expression demonstrated neuron-specific variability and differential abundance.
* *skn-1* expression was highly restricted and concentrated within a limited subset of neurons.
* Dopaminergic neuron subclasses exhibited distinct expression profiles, supporting transcriptomic heterogeneity within the dopaminergic system.

### Dopaminergic Neuron Expression

| Gene  | ADE     | PDE | CEP    |
| ----- | ------- | --- | ------ |
| age-1 | 235.083 | 0   | 33.962 |
| sod-3 | 113.354 | 0   | 54.171 |
| skn-1 | 0       | 0   | 0      |

ADE neurons demonstrated the highest expression of both *age-1* and *sod-3*. CEP neurons exhibited moderate expression of these genes, while PDE neurons showed little to no detectable expression. Baseline *skn-1* expression was not detected in ADE, CEP, or PDE neurons.

---

## Discussion

The results suggest substantial transcriptomic heterogeneity among adult dopaminergic neuron subclasses.

The coordinated expression of *age-1* and *sod-3* within ADE and CEP neurons may indicate differential activation of insulin-signaling and oxidative stress-response pathways. These findings support the possibility that individual dopaminergic neuron populations utilize distinct protective mechanisms to respond to oxidative stress.

The limited detection of *skn-1* suggests either neuron-specific regulation or expression levels below the detection threshold within the neuronal populations examined.

Because oxidative stress is strongly implicated in aging and neurodegenerative disease, further investigation of these pathways may provide insight into mechanisms underlying neuronal vulnerability and resilience.

---

## Skills Demonstrated

### Bioinformatics

* Single-cell RNA sequencing analysis
* Transcriptomic data interpretation
* Gene expression profiling
* Biological data visualization

### Computational Biology

* CeNGEN dataset analysis
* Neurobiology-focused data exploration
* Oxidative stress pathway investigation

### Data Science

* Exploratory data analysis
* Scientific communication
* Data visualization
* Biological hypothesis generation

---

## Future Directions

* Expand analysis to additional oxidative stress and aging-associated genes.
* Investigate differential expression across developmental stages.
* Perform pathway enrichment analyses.
* Examine neuron-specific signatures associated with neurodegeneration.
* Compare stress-response pathways across multiple neuronal subclasses.

---

## Author

**Autumn Southern, M.S. Biotechnology**

Interests: Bioinformatics, Aging Biology, Neurodegeneration, Transcriptomics, Genomics, and Computational Biology.
