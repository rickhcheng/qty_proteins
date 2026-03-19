This repository intends to provide reproducibility for the research manuscript: **Structural
bioinformatic studies of eight integral transmembrane NADPH oxidases and their AlphaFold 3
predicted QTY analogs with reduced hydrophobicity**. It includes a folder containing the
QTY-designed FASTA sequences for the 8 proteins in the NADPH Oxidase family examined in the
study. Additionally, the raw AlphaFold 3 output data and structure files for the proteins
are also included in alphafold3_output.zip.

The QTY code was applied to 8 transmembrane NADPH oxidase family proteins in order to reduce
their hydrophobicities. The native protein sequences for the studied NOX enzymes NOX1, NOX2,
NOX3, NOX4, NOX5, DUOX1, DUOXA1, and CYBA were obtained from [UniProt](https://www.uniprot.org).
Then, the QTY code was applied to the native sequences using the
[Protein Solubilizing Server](https://pss.sjtu.edu.cn/) to generate reduced hydrophobicity
variants. We submitted these new edited sequences to the
[AlphaFold 3 server](https://alphafoldserver.com) to generate the predicted structure.
QTY protein analog structures are predicted using the AlphaFold 3 Server v3.0.1. Each
prediction is run in the monomer mode, using the server’s default MSA generation and recycle
settings. Each prediction is run with one random seed:

* NOX1 = 740489916;
* NOX2 = 153345029;
* NOX3 = 1088284846;
* NOX4 = 2115711105;
* NOX5 = 1970948703;
* DUOX1 = 1666590488;
* DUOXA1 = 393896960;
* CYBA = 1060114576.

Structure templates are enabled, and no additional user-defined parameters are applied.
