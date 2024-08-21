# bits-to-binders-resources
Resources for the BioML Challenge 2024: Bits to Binders


## Table of Contents:
- [Protein Design](#protein-design)
  - [Protein Structure Prediction](#protein-structure-prediction)
  - [Inverse Folding](#inverse-folding)
  - [Generative Models](#generative-models)
  - [Encoder Models](#language-models)
  - [Other Useful Tools](#other-useful-tools)
  - [Relevant Literature](#relevant-literature)
  - [Miscellaneous](#miscellaneous)
- [Biology](#biology)
  - [CAR-T Literature](#car-t-literature)
  - [CD20 Literature](#cd20-literature)
- [Compute Resources](#compute-resources)
  - [TACC](#tacc)
  - [Other](#other-compute)

## Protein Design
Here is a compilation of many tools used by the UT Austin BioML Society. This is not a comprehensive list so we are likely missing some great tools. For a comprehensive list, check out [this great repository!](https://github.com/Peldom/papers_for_protein_design_using_DL?tab=readme-ov-file)


### Protein Structure Prediction
- AlphaFold2 / ColabFold [[paper]](https://www.nature.com/articles/s41586-021-03819-2) [[code]](https://github.com/google-deepmind/alphafold) [[colab]](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb)
- ESMFold [[paper]](https://www.science.org/doi/10.1126/science.ade2574) [[code]](https://github.com/facebookresearch/esm) [[server]](https://esmatlas.com/resources?action=fold)
- RoseTTAFold [[paper]](https://www.science.org/doi/10.1126/science.abj8754) [[code]](https://github.com/RosettaCommons/RoseTTAFold)
- RoseTTAFoldAllAtom [[paper]](https://www.science.org/doi/10.1126/science.adl2528) [[code]](https://github.com/baker-laboratory/RoseTTAFold-All-Atom)
- UMol [[paper]](https://www.nature.com/articles/s41467-024-48837-6) [[code]](https://github.com/patrickbryant1/Umol)
- AlphaFold2-RAVE [[paper]](https://arxiv.org/abs/2404.07102) [[code]](https://github.com/tiwarylab/alphafold2rave)

### Inverse Folding
- ProteinMPNN [[paper]](https://www.science.org/doi/10.1126/science.add2187) [[repo]](https://github.com/dauparas/ProteinMPNN)
- LigandMPNN [[paper]](https://www.biorxiv.org/content/10.1101/2023.12.22.573103v1) [[repo]](https://github.com/dauparas/LigandMPNN)
- ESM-IF1 [[paper]](https://www.biorxiv.org/content/10.1101/2022.04.10.487779v1) [[repo]](https://github.com/facebookresearch/esm) [[colab]](https://colab.research.google.com/github/facebookresearch/esm/blob/main/examples/inverse_folding/notebook.ipynb)

### Generative Models
- RFDiffusion [[paper]](https://www.nature.com/articles/s41586-023-06415-8) [[code]](https://github.com/RosettaCommons/RFdiffusion) [[colab]](https://colab.research.google.com/github/sokrypton/ColabDesign/blob/v1.1.1/rf/examples/diffusion.ipynb)
- RFDiffusionAllAtom [[paper]](https://www.science.org/doi/10.1126/science.adl2528) [[code]](https://github.com/baker-laboratory/rf_diffusion_all_atom)
- Protpardelle [paper](https://www.pnas.org/doi/10.1073/pnas.2311500121) [code](https://github.com/ProteinDesignLab/protpardelle)
- Chroma [paper](https://www.nature.com/articles/s41586-023-06728-8) [code](https://github.com/generatebio/chroma)
- ProGen [[paper]](https://www.nature.com/articles/s41587-022-01618-2) [[code]](https://github.com/salesforce/progen)
- Framediff [[paper]](https://arxiv.org/abs/2302.02277) [[code]](https://github.com/jasonkyuyim/se3_diffusion)
- Genie [[paper]](https://arxiv.org/abs/2301.12485) [[code]](https://github.com/aqlaboratory/genie)
- FoldFlow [[paper]](https://arxiv.org/abs/2310.02391) [[code]](https://github.com/DreamFold/FoldFlow)
- FrameFlow [[paper]](https://arxiv.org/abs/2310.05297) [[code]](https://github.com/microsoft/protein-frame-flow)
- Proteus [[paper]](https://www.biorxiv.org/content/10.1101/2024.02.10.579791v1) [[code]](https://github.com/Wangchentong/Proteus)
- Multiflow [[paper]](https://arxiv.org/abs/2402.04997) [[code]](https://github.com/jasonkyuyim/multiflow?tab=readme-ov-file)
- PepFlow [[paper]](https://www.nature.com/articles/s42256-024-00860-4) [[code]](https://github.com/physicshinzui/pepflow)

### Language Models
- ESM-2 [[paper]](https://www.science.org/doi/10.1126/science.ade2574) [[code]](https://github.com/facebookresearch/esm)
- SaProt [[paper]](https://www.biorxiv.org/content/10.1101/2023.10.01.560349v1) [[code]](https://github.com/westlake-repl/SaProt)
- Prost-T5 [[paper]](https://www.biorxiv.org/content/10.1101/2023.07.23.550085v1) [[code]](https://github.com/mheinzinger/ProstT5)
- ProtBERT [paper](https://academic.oup.com/bioinformatics/article/38/8/2102/6502274) [huggingface](https://huggingface.co/Rostlab/prot_bert)
- ProtTrans [paper](https://pubmed.ncbi.nlm.nih.gov/34232869/) [code](https://github.com/agemagician/ProtTrans)


### Other Useful Tools
- FoldSeek [[paper]](https://www.nature.com/articles/s41587-023-01773-0) [[code]](https://github.com/steineggerlab/foldseek) [[server]](https://search.foldseek.com/search)
- MMseqs2 [[paper]](https://www.nature.com/articles/nbt.3988) [[code]](https://github.com/soedinglab/MMseqs2)
- MutCompute [[paper]](https://www.biorxiv.org/content/10.1101/833905v1.full) [[server]](https://mutcompute.com/)

### Relevant Literature
- [Improving de novo protein binder design with deep learning](https://www.nature.com/articles/s41467-023-38328-5), Bennett et al., 2023
- [Improving Protein Expression, Stability, and Function with ProteinMPNN](https://pubs.acs.org/doi/10.1021/jacs.3c10941), Sumida et al., 2024

### Miscellaneous
- Lecture on Protein Structure Prediction from the BioML Society [[video]](https://www.youtube.com/watch?v=IIZ-bDPR2QA) [[slides]](https://docs.google.com/presentation/d/1LfeUVg0lhv3aztZKTssbWSOiScpze2_6QSqNoT76tPQ/edit?usp=sharing)
- Lecture on Protein Design from the BioML Society [[video]](https://www.youtube.com/watch?v=b00hCibYJ8U) [[slides]](https://docs.google.com/presentation/d/1gekGeREeUzbPq6tnCT3VKg60Rp0OSjF9ZZFUjR25F4Q/edit?usp=sharing)


## Biology
### CAR-T Literature
- [CAR T cell immunotherapy for human cancer](https://www.science.org/doi/full/10.1126/science.aar6711?casa_token=SziCZW0VnSAAAAAA%3AWueMwGrpKrCFBFVE-6h6hXszln1bTrIBEquo8KRGAWd3eK388Uix_uSgH8dpM-oPDEiIGCRIvWtQ), June et al., 2018
- [Recent advances and discoveries in the mechanisms and functions of CAR T cells](https://www.nature.com/articles/s41568-020-00323-z), Larson et al., 2021
- [CAR-T design: Elements and their synergistic function](https://www.sciencedirect.com/science/article/pii/S2352396420303078?ref=cra_js_challenge&fr=RR-1), Jayaraman et al., 2020
### CD20 Literature
- [The Development of a Recombinant scFv Monoclonal Antibody Targeting Canine CD20 for Use in Comparative Medicine](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4760772/), Jain et al., 2016
- [CD20 as a target for therapy](https://www.termedia.pl/-Review-paper-CD20-as-a-target-for-therapy,10,9455,1,1.html), Winiarska et al., 2007
- [Mechanisms of action of CD20 antibodies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3512181/), Boross et al., 2012
- [Rituximab (monoclonal anti-CD20 antibody): mechanisms of action and resistance](https://www.nature.com/articles/1206939), Smith 2003

## Compute Resources

### TACC
 - [Vista Supercomputer](https://docs.tacc.utexas.edu/hpc/vista/)
 - [Containers on TACC](https://containers-at-tacc.readthedocs.io/en/latest/index.html)
 - [Login](https://tacc.utexas.edu/portal/login)
 - [Create account](https://accounts.tacc.utexas.edu/register)

### Other Compute
- [Synthia](https://app.synthialabs.com/) - LLM that uses protein design tools
- [Tools suggested by Adaptyv Bio](https://design.adaptyvbio.com/tools)


