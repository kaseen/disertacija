# PhD Dissertation - Singidunum University (2026)

## Design of a Distributed E-Commerce Platform on a Public Blockchain Network Based on Computational Effort Optimization for Reducing User Transaction Fees

## Overview
This repository contains the complete LaTeX source of my doctoral dissertation, along with the accompanying research materials and the presentation delivered during the dissertation defence.

### Research Areas and Keywords
Electronic Commerce, Distributed Systems, Blockchain Technology, Ethereum, Smart Contracts, Decentralized Applications (dApps), Non-Fungible Tokens (NFTs), Content-Based Addressing.

## Citation
If you use this work in your research, please cite it as follows:

```bibtex
@phdthesis{tasic2026blockchain,
  author      = {Tasi{\'c}, Vuka{\v{s}}in S.},
  title       = {Design of a Distributed E-Commerce Platform on a Public Blockchain Network Based on Computational Effort Optimization for Reducing User Transaction Fees},
  school      = {Singidunum University},
  address     = {Belgrade, Serbia},
  year        = {2026},
  type        = {Doctoral Dissertation},
  note        = {Original title: Unapre{\dj}enje distribuirane platforme za e-trgovinu na javnoj blockchain mre{\v{z}}i u cilju minimizacije ra{\v{c}}unarskog napora prilikom izvr{\v{s}}avanja transakcija},
  url         = {https://singipedia.singidunum.ac.rs/izdanje/44789-unapredjenje-distribuirane-platforme-za-e-trgovinu-na-javnoj-blockchain-mrezi-u-cilju-minimizacije-racunarskog-napora-prilikom-izvrsavanja-transakcija}
}
```

## Related Publication
During my doctoral studies, I served as the corresponding author of the following research paper: published in *IEEE Access*. 

**The Cost-Effective Management of Multiple E-Coupons on Public Ethereum-Based Chains Using NFT Standard With Implicit Ownership**

The paper is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). A copy of the publication is also included in this repository.

To cite this publication:
```bibtex
@article{tasic2024cost,
  title       = {The Cost-Effective Management of Multiple E-Coupons on Public Ethereum-Based Chains Using NFT Standard With Implicit Ownership},
  author      = {Tasic, Vukasin S and Tasic, Irena and Veinovic, Mladen},
  journal     = {IEEE Access},
  volume      = {12},
  pages       = {149889--149902},
  year        = {2024},
  publisher   = {IEEE}
}
```

## Dissertation Defence
The dissertation defence recording is hosted on IPFS.

**Content Identifier (CID):**

```text
bafybeigdg3lsrpsgeijpaa4xm2sylp2pqnolyb4w55ovtb3jnmd5hdt3yu
```

**Watch the defence:**
[Open the defence recording in your browser](https://bafybeigdg3lsrpsgeijpaa4xm2sylp2pqnolyb4w55ovtb3jnmd5hdt3yu.ipfs.inbrowser.link/)

## Building the Dissertation

The dissertation is written in LaTeX and compiled using the [blang/docker:ubuntu](https://github.com/blang/latex-docker) Docker image. 

The following commands were used to generate the final dissertation PDF:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Building the Dissertation

The presentation is also written in LaTeX and compiled using the same Docker image.
```bash
pdflatex presentation.tex
```

*Note*: During compilation, LaTeX prompts for user input due to a bug in the source. Press Enter once to continue the compilation.

## Statistics

- **Total time invested:** 420 hours (dissertation) + 30 hours (defence presentation)
- **Language:** Serbian
- **Degree awarded:** Doctor of Philosophy (PhD)
- **Institution:** Singidunum University
- **Year:** 2026

## License
This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).