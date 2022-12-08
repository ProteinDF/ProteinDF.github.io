---
layout: page
title: "ProteinDF software package"
description: ""
---

{% include JB/setup %}

[English](./index.html)
[Japanese](./index_j.html)

![ProteinDF logo](img/PDFLOGO.jpg "ProteinDF logo")

## About

ProteinDF is a free and open source quantum chemistry calculation software package.

## News

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  {% endfor %}
</ul>

## GitHub Repository

### ProteinDF

[https://github.com/ProteinDF/ProteinDF](https://github.com/ProteinDF/ProteinDF)

### ProteinDF_bridge

[https://github.com/ProteinDF/ProteinDF_bridge](https://github.com/ProteinDF/ProteinDF_bridge)

### ProteinDF_pytools

[https://github.com/ProteinDF/ProteinDF_pytools](https://github.com/ProteinDF/ProteinDF_pytools)

### QCLObot

[https://github.com/ProteinDF/QCLObot](https://github.com/ProteinDF/QCLObot)

## manual

- [ProteinDF user manual](http://proteindf.github.io/ProteinDF_userman/en/index.html)
- [QCLObot user manual](http://proteindf.github.io/QCLObot/)

## Cite

### ProteinDF

- F. Sato, Y. Shigemitsu, I. Okazaki, S. Yahiro, M. Fukue, S. Kozuru, H. Kashiwagi, “Development of a new density functional program for all-electron calculation of proteins”, Int. J. Quant. Chem., 63, 245-246 (1997).
- I. Okazaki, F. Sato, T. Yoshihiro, T. Ueno, H. Kashiwagi, "Development of a restricted open shell Kohn–Sham program and its application to a model heme complex", THEOCHEM, 451, 109-119 (1998).
- T. Yoshihiro, F. Sato, H. Kashiwagi, "Distributed parallel processing by using the object-oriented technology in ProteinDF program for all-electron calculations on proteins", Chem. Phys. Lett., 346, 313–321 (2001).
- T. Inaba, F. Sato, "Development of parallel density functional program using distributed matrix to calculate all-electron canonical wavefunction of large molecules", J. Comput. Chem., 28, 984–995 (2007).
- T. Hirano, F. Sato, "A third-generation density-functional-theory-based method for calculating canonical molecular orbitals of large molecules", PCCP, 16, 14496-14503 (2014).

### QCLO

- H. Kashiwagi, H. Iwai, K. Tokieda, M. Era, T. Sumita, T. Yoshihiro, F. Sato, "Convergence process with quasi-canonical localized orbital in all-electron SCF calculation on proteins", Mol. Phys., 101, 81-86 (2003).
- N. Nishino-Uemura, T. Hirano, F. Sato, "Study of the quasicanonical localized orbital method based on protein structures", J. Chem. Phys., 127, 184106 (2007).

## References using the ProteinDF

- T.Hirano, F.Sato, “Theoretical study of the receptor-binding domain of spike protein of SARS-CoV-2 by canonical molecular orbital calculation”, AIP Conference Proceedings, 2611, 020005 (2022).
- R.Nakaoka, T.Hirano, F.Sato, “Study on mechanism of electronic states of Interferon alpha2”, Seisan Kenkyu, 74, 153-159 (2022).
- T.Wang, T.Hirano, F.Sato, “Study on the Role in the Catalytic Reaction Occurrence of the Active Site in PETase by Canonical Molecular Orbital Method", Seisan Kenkyu, 74, 161-167 (2022).
- T.Hirano, F.Sato, “Interaction Energy Analysis Based on Canonical Kohn-Sham Molecular Orbitals Calculation of Protein”, AIP Conference Proceedings, 2343, 020007 (2021).
- D.Maeda, T.Hirano, F.Sato, “Analysis of Electronic Structure of Photoactive Yellow Protein by Canonical Molecular Orbitals Calculation", Seisan Kenkyu, 73, 157-163 (2021).
- T.Hirano, F.Sato, "Interaction energy analysis based on canonical Kohn-Sham molecular orbital calculation of protein", DFT2020 (2020).
- H.Sasaki, T.Hirano, F.Sato, "Comparison of Electronic Structures between Insulin-like Growth Factor 1 and Insulin", Seisan Kenkyu, 72, 239-246 (2020).
- T.Hirano, F.Sato, “Recent progress of protein canonical molecular orbital calculation by the third generation density functional method”, AIP Conference Proceedings 2186, 030009 (2019).
- H.Eguchi, T.Hirano, F.Sato, "Study on the Cloud-like Visualization Technique of Protein Molecular Orbitals by the Rejection Method", Seisan Kenkyu, 71, 769-773, (2019).
- T.Hirano, F.Sato, "The electronic structure of the active site in the glucose oxidase", HPCI Research Report, 3, 11-16 (2018).
- H.Eguchi, T.Hirano, F.Sato, "Study on the Cloud-like Visualization Model of Protein Molecule Orbitals by the Rejection Method", J. Comput. Chem., J., 17, 189-192 (2018).
- T.Hirano, F.Sato, "Study of High-Performance Canonical Molecular Orbitals Calculation for Proteins", AIP Conference Proceedings, 1906, 030019 (2017).
- S.Kihira, T.Hirano, F.Sato, "Study on Stable Structures of Oxytocin by Full-Quantum Chemical Calculation", Seisan Kenkyu, 68, 219-223, (2016).
- T.Kim, T.Hirano, F.Sato, "Development of atomic charges for proteins by using the linear regression method based on canonical molecular orbital calculation", Seisan Kenkyu, 68, 213-217, (2016).
- J.Yoshida, T.Hirano, F.Sato, "Electronic state calculation of the active center of Glucose Oxidase by QCLO method", Seisan Kenkyu, 67(3), 265-272 (2015).
- T.Hirano, F.Sato, “A third-generation density-functional-theory-based method for calculating canonical molecular orbitals of large molecules”, Phys. Chem. Chem. Phys., 16, 14496-14503 (2014).
- H.Higuchi, T.Hirano, F.Sato, "Study of Practical Approach for Grid-free XC Computational Method", Seisan Kenkyu, 66, 273 (2014).
- K.Chiba, T.Hirano, F.Sato, M.Okamoto, “Clarification of the role of protein in carbonmonoxy myoglobin by investigating electronic states”, Int. J. Quant. Chem., 113, 2345-2354, (2013).
- T.Shimomukai, K.Chiba, J.Matsuda, T.Hirano, F.Sato, "All-Electron Wave Functions and the Density-of-States Analyses of Proteins", J. Vis. Soc. Jpn., 32, 132-137 (2013).
- T.Hirano, F.Sato, "Cholesky decomposition method for canonical molecular orbital calculations of proteins", 31th JSST Annual Conference proc., (2012).
- T.Kuroda, T.Hirano, F.Sato, "Study of the Electronic States of the ［Ni-Fe］ and ［Ni-Fe-Se］ Hydrogenase Active Center", Seisan Kenkyu, 64, 345 (2012).
- M.Hori, T.Hirano, F.Sato, "Computational Study of Key Steps of RuBisCO Carboxylase Reaction and Roles of Active-Site Residues", Seisan Kenkyu, 64, 351 (2012).
- T. Hirano, F. Sato, "Massively parallel computation strategies for canonical molecular orbital calculations of proteins", 30th JSST Annual Conference proc., (2011).
- Y.Tokita, S.Yamada, W.Luo, Y.Goto, N.Bouley-Ford, H.Nakajima, Y.Watanabe, "Protein photoconductors and photodiodes", Angew. Chem., 50, 11663-6 (2011)
- K.Ishikawa, T.HIRANO, F.SATO, "Study on Model Chemistry for All-Electron Calculation of Proteins", Seisan Kenkyu, 62, 241, (2010).
- T.Hirano, K.Chiba, F.Sato, "ProteinDF: An All-electron Density Functional Program Package for Proteins", Trans. Jpn. Soc. Sim. Tech., 4, 50-59 (2009).
- T.Hirano, F.Sato, "Recommendation of All-Electron Calculation in the Theoretical Study of Polypeptides", 46th Japanese peptide symp. proc., (2009).
- H.Yukawa, T.HIirano, Y.Nishimura, F.Sato, "High Performance Computing of Precise Electrostatic Potential on Proteins by GPU", Seisan Kenkyu, 61, 103 (2009).
- K.Chiba, T.Hirano, F.Sato, M.Okamoto, “A Density Functional Study on Reaction Center Models of Horse Carbonmonoxy Myoglobin – Effect of distal histidine to the electronic states -”, J. Comput. Chem. Jpn. (2008).
- Y.Tokita, J.Shimura, H.Nakajima, "Mechanism of Intramolecular Electron Transfer in the Photoexcited Zn-Substituted Cytochrome c: Theoretical and Experimental Perspective", J. Am. Chem. Soc., 130, 5302–5310 (2008).
- T.Inaba, N.Tsunekawa, T.Hirano, T.Yoshihiro, H.Kashiwagi, F.Sato, "Density functional calculation of the electronic structure on insulin hexamer", Chem. Phys. Lett., 434, 331-335 (2007).
- N.Nishino-Uemura, T.Hirano, F.Sato, “Study of the quasi-canonical localized orbital method based on protein structures”, J. Chem. Phys., 127, 184106 (2007).
- T.Inaba, S.Tahara, N.Nisikawa, H.Kashiwagi, F.Sato, "All-electron density functional calculation on insulin with quasi-canonical localized orbitals.", J. Comput. Chem., 26, 987-93 (2005).

If you know the other unlisted articles using the ProteinDF, please let me know.

## License

ProteinDF is licensed under the GNU GPL v3.
The source code can be found on the Github.

## Bugs

If you find any bugs, please let me know.
And if you have a suggestion for improvement, please let me know.
