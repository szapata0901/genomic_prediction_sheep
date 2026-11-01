# Genomic prediction in Texel sheep: EBV vs GEBV

Texel breeders have decades of pedigree and performance records, but only a small part of the flock is genotyped. This folder shows what happens when SNP data is added to that information: how much do the breeding values change, and for whom?

## What was done

Breeding values were predicted in two ways for the same Texel population:

- **EBV**, the traditional estimate, from pedigree and performance records only.
- **GEBV**, the genomic estimate from a single-step approach that combines the pedigree with SNP genotypes.

Then the two were compared, animal by animal. The question is not just which one is "better", but where genomic information changes the ranking and by how much.

## The data

A Texel population with 910 genotyped animals, 27 autosomes and a pedigree of about 19,600 animals.

## What you will find here

This folder is a working space, not a polished package. In it you will see:

- **Plots** comparing EBV and GEBV, such as how well they agree and how the ranking of animals shifts.
- **Tables** with the breeding values, from each of the two approaches.
- **Intermediate files** from the analysis, which are there mostly for traceability.

The goal is that you can browse it and get a feel for what genomic prediction adds in a real flock, without having to run anything.

## What to keep in mind

With under a thousand genotyped animals, the comparison is a good first look, not a final verdict. The pedigree carries a lot of the information in this population, which is why a single-step approach is a natural fit.

This is part of the SelectaGen toolkit, developed as a commercial project, so the code is not public. If you work with sheep or other livestock and want to try it on your own data, feel free to get in touch.
