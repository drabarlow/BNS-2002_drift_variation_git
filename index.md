---
title       : "Drift and Variation"
subtitle    : "BNS-2002: Genes, Development, and Evolution"
author      : Dr Axel Barlow
job         : "email: a.barlow@bangor.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : LA_Full_colour_reversed.svg
biglogo     : A1_FullColour.svg
assets      : {assets: ../../assets}
license     : by-nc-sa

---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Molecular Ecology and Evolution at Bangor (MEEB)

- 3rd year module "Molecular ecology and evolution"
- https://www.bangor.ac.uk/meeb

<img src="./assets/img/meeb_logo_NEW_no_text.jpg" width="100%" style="display: block; margin: auto;" />

---

## Axel Barlow research group

- Population genomics, Paleogenomics, Conservation genomics
- Dissertation and MSc projects

<img src="./assets/img/extinct_animals.png" width="80%" style="display: block; margin: auto;" />

<img src="./assets/img/sp4-6.png" width="80%" style="display: block; margin: auto;" />

---

## Lecture schedule

1. **Drift and variation (Evolution: Chapter 6)**
2. Conservation genetics (Evolution: Chapter 6)
3. Phylogeny 1 (Evolution: Chapter 16)
4. Phylogeny 2 (Evolution: Chapter 16)

--- &twocol

## Literature

*** =left

**Course textbook**

Futuyma & Kirkpatrick. Evolution (5th Edition)

*Available as E-book from library*

**Other papers indicated in lectures**

*** =right

<img src="./assets/img/511TDdibxIL._AC_UF1000,1000_QL80_.jpg" width="80%" style="display: block; margin: auto;" />

--- .segue .dark 

## Key concepts

--- &twocol

## Modern synthesis

*** =left

<img src="./assets/img/Charles_Darwin_by_Julia_Margaret_Cameron_2.jpg" width="80%" style="display: block; margin: auto;" />

*** =right

<img src="./assets/img/800px-Gregor_Mendel_2.jpg" width="75%" />

---

## Population genetics

Provides the mathematical framework of how selection acts on genetic variation resulting in adaptation

*"Nothing in biology makes sense, except in the light of evolution"* (Dobzhansky 1973)

*"Nothing in evolution makes sense, except in the light of population genetics"* (Lynch 2007)


--- &twocol

## Genetic locus (plural loci)

*** =left

- Working definition: "a single position on a chromosome"
- Examples: SNP, gene, exon, mitochondrial DNA

**In diploid species**

- Individuals (mostly) have 2 copies of each locus: 1 from mum, 1 from dad
- *Except* some haploid loci (e.g. Y chr, mtDNA)

*** =right

<img src="./assets/img/Gene_Loci_and_Alleles.png" width="75%" style="display: block; margin: auto 0 auto auto;" />

--- &twocol bg:white

## Alleles

*** =left

- An **Allele** is a particular genetic variant of a locus
- An individual is **heterozygous** at a locus when it has different alleles
- **Homozygous** is 2 copies of same allele
- We can also measure **allele frequencies**

**For example**

- Frequency A and B is 50% (or 0.5)
- Frequencies always sum to 100% (or 1)
- Selection on A increases its frequency

*** =right

<img src="assets/fig/unnamed-chunk-8-1.png" width="90%" style="display: block; margin: auto;" />

--- &thirds

## Neutral evolution

*** =left

- Darwin thought about evolution in terms of natural selection
- What if there is no selection?
- Motoo Kimura: Neutral theory of molecular evolution, 1968
- Loci evolve by genetic drift
- Drift is determined by the population size
- Basis of population genetics and phylogenetics
- "Null hypothesis" of molecular evolution

*** =right

<img src="./assets/img/Motoo_Kimura.jpg" width="90%" style="display: block; margin: auto;" />

--- &twocol


## How much of the genome is selectivel neutral?

**Human as an example**

*** =left

- Protein coding sequences = 2%
- Functional 10-20%
- Synonymous mutations
- Introns
- Neutral alleles
- **Selection is rare**

*** =right

<img src="./assets/img/494467_1_En_1_Fig1_HTML.png" width="100%" />

--- .segue .dark 

## Genetic drift

---

## Definition

- Allele frequencies will change from one generation to the next due to chance events
- includes survival, reproduction, and inheritance.

### This is Genetic drift

- The change occurs at random. 
- It does not involve one allele being favoured over another. That is selection (different process)
- Drift affects all loci in the genome
- Drift affects all populations of all species

---

<img src="./assets/img/hedgehog-crossing-street-in-front-of-an-oncoming-car.webp" width="100%" style="display: block; margin: auto;" />

---

<img src="./assets/img/family.svg" width="70%" style="display: block; margin: auto;" />

---

<img src="./assets/img/MacquarieIslandElephantSeal.JPG" width="90%" style="display: block; margin: auto;" />

---

## The process visually

<img src="./assets/img/drift.svg" width="75%" style="display: block; margin: auto;" />

---

## The process with chocolate

<img src="./assets/img/Plain-M&Ms-Pile.jpg" width="70%" style="display: block; margin: auto;" />

---

## Simulator

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

---

## Obs 1. Drift is unbiased

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

---

## Obs 2. Fluctuations are larger in small populations

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

--- &twocol

## Obs 2. Fluctuations are larger in small populations

*** =left

- This is a sampling effect:
- Small samples are less likely to reflect the starting frequencies.
- Consider flipping a coin 3x vs 3,000x
- Outcomes become more consistent when averaging over a larger number of random events
- Drift is **stronger** in small populations
- Drift is **weaker** in large populations

*** =right

<img src="./assets/img/Coin_Toss_(3635981474).jpg" width="80%" style="display: block; margin: auto;" />

---

## Obs 3. Drift causes populations to become different

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

--- &twocol

## Obs 3. Drift causes populations to become different

*** =left

<img src="./assets/img/Gallotia_stehlini_-Gran_Canaria,_Canary_Islands,_Spain-8.jpg" width="100%" style="display: block; margin: auto;" />

*Gallotia stehlini* Gran Canaria

*** =right

<img src="./assets/img/G_galloti.jpeg" width="100%" style="display: block; margin: auto;" />

*Gallotia galloti* Tenerife

---

## Obs 4. Drift causes a loss of variation

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

---

## Obs 4. Drift causes a loss of variation

- Genetic variation is continually lost
- Rate of loss determined by strength of drift
- Can be replaced by **mutation** or **gene flow**
- Example: isogenic lab mice: 20 generations of brother x sister mating

<img src="./assets/img/1280px-Scid_mouse.jpg" width="50%" style="display: block; margin: auto auto auto 0;" />

--- .segue .dark 

## Drift and selection

--- &thirds

## Drift and selection

*** =left

**(positive) Selection**

- One allele is favoured over another
- Depends on high big the fitness difference is (selection coefficient = *s*)

**Drift**

- Drift affects all loci in all populations of all species
- **Stronger** in small populations and **weaker** in large populations

**Both processes**

- Cause a reduction in diversity
- Cause populations to become different

*** =right

<img src="assets/fig/unnamed-chunk-20-1.png" width="100%" style="display: block; margin: auto;" />

---

## Selection and drift

<iframe src = 'https://heavywatal.github.io/driftr.js/'></iframe>

--- &twocol

## Selection more effective in large populations

*** =left

<img src="./assets/img/Drosophila_melanogaster_Proboscis.jpg" width="100%" style="display: block; margin: auto auto auto 0;" />

- *Drosophila melanogaster*
- population size ~1 million
- s = 0.00001 = adaptive evolution

*** =right

<img src="./assets/img/eschrichtius-robustus-01jpg.webp" width="100%" style="display: block; margin: auto auto auto 0;" />

- Grey whale
- population size 10,000
- s = 0.00001 = effectively neutral

---

## Detecting selection

- Harder than you might think
- Drift is null hypothesis
- Always operates
- Creates similar signal:
  - change in allele frequencies
  - loss of diversity
  - population divergence
- **Look for signal above the background level of drift**

--- &twocol

## Hooded and carrion crows

*** =left

<img src="./assets/img/Carrion-Crow-black-bird-portrait-of-head-and-looking-at-camera_1.jpg" width="80%" style="display: block; margin: auto auto auto 0;" />

<img src="./assets/img/Nebelkrähe_Corvus_cornix,_Belvedere,_Wien.jpg" width="80%" style="display: block; margin: auto auto auto 0;" />

*** =right

<img src="./assets/img/Distribution_of_carrion_and_hooded_crows_across_Europe.jpg" width="100%" style="display: block; margin: auto;" />

---

## Hooded and carrion crows

<embed src="./assets/img/1111crow410.full.pdf" width="100%" height="500" type="application/pdf" />

---

## Genetic drift summary

- Allele frequencies will change from one generation to the next due to chance events
- Such as survival, reproduction, and inheritance.
- Drift is unbiased, no allele is favoured
- Drift causes a loss of genetic variation (replaced by mutation or gene flow)
- Strength of drift is larger in small populations
- Drift causes populations to become different
- Selection share some features with drift, but alleles are favoured
- Selection is more effective when drift is weak
- We need to account for drift when testing for selection

--- &thankyou

## Next time:

**Conservation genetics**


