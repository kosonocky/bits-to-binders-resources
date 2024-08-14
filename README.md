# bits-to-binders-resources
Resources for the BioML Challenge 2024: Bits to Binders


## Table of Contents:
- [Protein Design](#protein-design)
  - [Protein Structure Prediction](#protein-structure-prediction)
  - [Inverse Folding](#inverse-folding)
  - [Generative Models](#generative-models)
  - [Encoder Models](#encoder-models)
  - [Other Useful Tools](#other-useful-tools)
  - [Relevant Literature](#relevant-literature)
- [Biology](#biology)
  - [CAR-T Literature](#car-t-literature)
  - [CD20 Literature](#cd20-literature)


## Protein Design
Here is a compilation of many tools used by the UT Austin BioML Society. This is not a comprehensive list so we are likely missing some great tools. For a comprehensive list, check out [this great repository!](https://github.com/Peldom/papers_for_protein_design_using_DL?tab=readme-ov-file)


### Protein Structure Prediction
- AlphaFold2 / ColabFold [[paper]](https://www.nature.com/articles/s41586-021-03819-2) [[code]](https://github.com/google-deepmind/alphafold) [[colab]](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb)
- AlphaFold3 [[paper]](https://www.nature.com/articles/s41586-024-07487-w) [[server]](https://alphafoldserver.com/about)
- ESMFold [[paper]](https://www.science.org/doi/10.1126/science.ade2574) [[code]](https://github.com/facebookresearch/esm) [[server]](https://esmatlas.com/resources?action=fold)
- RoseTTAFold [[paper]](https://www.science.org/doi/10.1126/science.abj8754) [[code]](https://github.com/RosettaCommons/RoseTTAFold)
- RoseTTAFoldAllAtom [[paper]](https://www.science.org/doi/10.1126/science.adl2528) [[code]](https://github.com/baker-laboratory/RoseTTAFold-All-Atom)

### Inverse Folding
- ProteinMPNN [[paper]](https://www.science.org/doi/10.1126/science.add2187) [[repo]](https://github.com/dauparas/ProteinMPNN)
- LigandMPNN [[paper]](https://www.biorxiv.org/content/10.1101/2023.12.22.573103v1) [[repo]](https://github.com/dauparas/LigandMPNN)
- ESM-IF1 [[paper]](https://www.biorxiv.org/content/10.1101/2022.04.10.487779v1) [[repo]](https://github.com/facebookresearch/esm) [[colab]](https://colab.research.google.com/github/facebookresearch/esm/blob/main/examples/inverse_folding/notebook.ipynb)

### Generative Models
- RFDiffusion [[paper]](https://www.nature.com/articles/s41586-023-06415-8) [[code]](https://github.com/RosettaCommons/RFdiffusion) [[colab]](https://colab.research.google.com/github/sokrypton/ColabDesign/blob/v1.1.1/rf/examples/diffusion.ipynb)
- RFDiffusionAllAtom [[paper]](https://www.science.org/doi/10.1126/science.adl2528) [[code]](https://github.com/baker-laboratory/rf_diffusion_all_atom)
- ProGen [[paper]](https://www.nature.com/articles/s41587-022-01618-2) [[code]](https://github.com/salesforce/progen)
- ESM-3 [[paper]](https://www.biorxiv.org/content/10.1101/2024.07.01.600583v1) [[code]](https://github.com/evolutionaryscale/esm)

### Encoder Models
- ESM-2 [[paper]](https://www.science.org/doi/10.1126/science.ade2574) [[code]](https://github.com/facebookresearch/esm)
- SaProt [[paper]](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v1) [[code]](https://github.com/westlake-repl/SaProt)
- Prost-T5 [[paper]](https://www.biorxiv.org/content/10.1101/2023.07.23.550085v1) [[code]](https://github.com/mheinzinger/ProstT5)


### Other Useful Tools
- FoldSeek [[paper]](https://www.nature.com/articles/s41587-023-01773-0) [[code]](https://github.com/steineggerlab/foldseek) [[server]](https://search.foldseek.com/search)
- MMseqs2 [[paper]](https://www.nature.com/articles/nbt.3988) [[code]](https://github.com/soedinglab/MMseqs2)
- MutCompute [[paper]](https://www.biorxiv.org/content/10.1101/833905v1.full) [[server]](https://mutcompute.com/)

### Relevant Literature
- [Improving de novo protein binder design with deep learning, Bennett et al., 2023](https://www.nature.com/articles/s41467-023-38328-5)
- [Improving Protein Expression, Stability, and Function with ProteinMPNN, Sumida et al., 2024](https://pubs.acs.org/doi/10.1021/jacs.3c10941)

### Miscellaneous
- [Tools suggested by Adaptyv Bio](https://design.adaptyvbio.com/tools)
- Lecture on Protein Structure Prediction from the BioML Society [video](https://www.youtube.com/watch?v=IIZ-bDPR2QA) [slides](https://docs.google.com/presentation/d/1LfeUVg0lhv3aztZKTssbWSOiScpze2_6QSqNoT76tPQ/edit?usp=sharing)
- Lecture on Protein Design from the BioML Society [[video]](https://www.youtube.com/watch?v=b00hCibYJ8U) [[slides]](https://docs.google.com/presentation/d/1gekGeREeUzbPq6tnCT3VKg60Rp0OSjF9ZZFUjR25F4Q/edit?usp=sharing)


## Biology

### CAR-T Literature
- [CAR T cell immunotherapy for human cancer, June et al., 2018](https://www.science.org/doi/full/10.1126/science.aar6711?casa_token=SziCZW0VnSAAAAAA%3AWueMwGrpKrCFBFVE-6h6hXszln1bTrIBEquo8KRGAWd3eK388Uix_uSgH8dpM-oPDEiIGCRIvWtQ)
- [Recent advances and discoveries in the mechanisms and functions of CAR T cells, Larson et al., 2021](https://www.nature.com/articles/s41568-020-00323-z)
- [CAR-T design: Elements and their synergistic function, Jayaraman et al., 2020](https://www.sciencedirect.com/science/article/pii/S2352396420303078?ref=cra_js_challenge&fr=RR-1)
### CD20 (target) Literature
- [The Development of a Recombinant scFv Monoclonal Antibody Targeting Canine CD20 for Use in Comparative Medicine, Jain et al., 2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4760772/)
- [CD20 as a target for therapy, Winiarska et al., 2007](https://www.termedia.pl/-Review-paper-CD20-as-a-target-for-therapy,10,9455,1,1.html)
- [Mechanisms of action of CD20 antibodies, Boross et al., 2012](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3512181/)
- [Rituximab (monoclonal anti-CD20 antibody): mechanisms of action and resistance, Smith 2003](https://www.nature.com/articles/1206939)

### CD19 (not the target, but somewhat relevant)
- [CD19: a biomarker for B cell development, lymphoma diagnosis and therapy, Wang et al., 2012](https://link.springer.com/article/10.1186/2162-3619-1-36)
- [CAR therapy: the CD19 paradigm, Sadelain 2015](https://www.jci.org/articles/view/80010)
