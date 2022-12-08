---
layout: page
title: "ProteinDF software package"
description: ""
---

{% include JB/setup %}

[English](./index.html)
[Japanese](./index_j.html)

![ProteinDF logo](img/PDFLOGO.jpg "ProteinDF logo")

## Abount

ProteinDF はオープンソースの量子化学計算ソフトウェアパッケージです。

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

- [ProteinDF user manual](http://proteindf.github.io/ProteinDF_userman/ja/index.html)
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

- T. Hirano, F. Sato, “Theoretical study of the receptor-binding domain of spike protein of SARS-CoV-2 by canonical molecular orbital calculation”, AIP Conference Proceedings, 2611, 020005 (2022).
- 中岡亮太, 平野敏行, 佐藤文俊, “インターフェロン α2 の電子状態に基づく作用機序の研究”, 生産研究, 74, 153-159 (2022).
- 王 天宇, 平野敏行, 佐藤文俊, “正準分子軌道法による PETase の活性部位の触媒反応発生における役割に関する研究”, 生産研究, 74, 161-167 (2022).
- T. Hirano, F. Sato, “Interaction Energy Analysis Based on Canonical Kohn-Sham Molecular Orbitals Calculation of Protein”, AIP Conference Proceedings, 2343, 020007 (2021).
- 前田大陸, 平野敏行, 佐藤文俊, “正準分子軌道計算による光活動性黄色タンパク質の電子構造解析”, 生産研究, 73, 157-163 (2021).
- T. Hirano, F. Sato, "Interaction energy analysis based on canonical Kohn-Sham molecular orbital calculation of protein", DFT2020 (2020).
- 佐々木光, 平野敏行, 佐藤文俊, “インスリン様成長因子 1 とインスリンの電子構造の比較”, 生産研究, 72, 239-246 (2020).
- T. Hirano, F. Sato, “Recent progress of protein canonical molecular orbital calculation by the third generation density functional method”, AIP Conference Proceedings 2186, 030009 (2019).
- 江口晴輝, 平野敏行, 佐藤文俊, "タンパク質分子軌道の棄却法による雲状可視化法の研究", 生産研究, 71, 769-773, (2019).
- 平野敏行, 佐藤文俊, "グルコースオキシダーゼにおける活性中心まわりの電子状態", HPCI Research Report, 3, 11-16 (2018).
- 江口晴輝, 平野敏行, 佐藤文俊, "棄却法を用いたタンパク質分子軌道の雲状可視化法の研究", J. Comput. Chem., J., 17, 189-192 (2018).
- 平野敏行, 佐藤文俊, "大規模分子設計における電子状態計算法と期待", 放電研究, 61, 13-18 (2018).
- T. Hirano, F. Sato, "Study of High-Performance Canonical Molecular Orbitals Calculation for Proteins", AIP Conference Proceedings, 1906, 030019 (2017).
- 紀平昌吾, 平野敏行, 佐藤文俊, “量子化学計算によるオキシトシンの安定構造に関する研究”, 生産研究, 68, 219-223, (2016).
- 金泰煥, 平野敏行, 佐藤文俊, “カノニカル分子軌道計算に基づく線形回帰法を用いたタンパク質原子電荷の開発”, 生産研究, 68, 213-217, (2016).
- 吉田洵也, 平野敏行, 佐藤文俊, “QCLO 法によるグルコースオキシダーゼ活性中心の電子状態計算”, 生産研究, 67(3), 265-272 (2015).
- T. Hirano, F. Sato, “A third-generation density-functional-theory-based method for calculating canonical molecular orbitals of large molecules”, Phys. Chem. Chem. Phys., 16, 14496-14503 (2014).
- 樋口恒, 平野敏行, 佐藤文俊, “グリッドフリー交換相関計算法の実用化に向けた研究”, 生産研究, 66, 273 (2014).
- K. Chiba, T. Hirano, F. Sato, M. Okamoto, “Clarification of the role of protein in carbonmonoxy myoglobin by investigating electronic states”, Int. J. Quant. Chem., 113, 2345-2354, (2013).
- 下向智美，千葉貢治，松田潤一，平野敏行，佐藤文俊, “タンパク質の全電子波動関数と状態密度解析”, 可視化情報, 32, 132-137 (2013).
- T. Hirano, F. Sato, "Cholesky decomposition method for canonical molecular orbital calculations of proteins", 31th JSST Annual Conference proc., (2012).
- 黒田敬史, 平野敏行, 佐藤文俊, “[Ni-Fe]型及び[Ni-Fe-Se]型ヒドロケナーゼ活性部位の電子状態の研究”, 生産研究, 64, 345 (2012).
- 堀将人, 平野敏行, 佐藤文俊, “計算化学による RuBisCO カルボキシラーゼ反応の重要なステップと活性部位のアミノ酸残基の役割に関する研究”, 生産研究, 64, 351 (2012).
- T. Hirano, F. Sato, "Massively parallel computation strategies for canonical molecular orbital calculations of proteins", 30th JSST Annual Conference proc., (2011).
- Y. Tokita, S. Yamada, W. Luo, Y. Goto, N. Bouley-Ford, H. Nakajima, Y. Watanabe, "Protein photoconductors and photodiodes", Angew. Chem., 50, 11663-6 (2011)
- 石川健太郎, 平野敏行, 佐藤文俊, “タンパク質全電子計算におけるモデル化学に関する研究”, 生産研究, 62, 241, (2010).
- 平野敏行, 千葉貢治, 佐藤文俊, “タンパク質のための全電子密度汎関数法プログラム ProteinDF”, 日本シミュレーション学会論文誌, 4, 50-59 (2009).
- T. Hirano, F. Sato, "Recommendation of All-Electron Calculation in the Theoretical Study of Polypeptides", 46th Japanese peptide symp. proc., (2009).
- 湯川英宜, 平野敏行, 西村康幸, 佐藤文俊, “GPU によるタンパク質高精度静電ポテンシャル計算の高速化”, 生産研究, 61, 103 (2009).
- K. Chiba, T. Hirano, F. Sato, M. Okamoto, “A Density Functional Study on Reaction Center Models of Horse Carbonmonoxy Myoglobin – Effect of distal histidine to the electronic states -”, J. Comput. Chem. Jpn. (2008).
- Y. Tokita, J. Shimura, H. Nakajima, "Mechanism of Intramolecular Electron Transfer in the Photoexcited Zn-Substituted Cytochrome c: Theoretical and Experimental Perspective", J. Am. Chem. Soc., 130, 5302–5310 (2008).
- T. Inaba, N. Tsunekawa, T. Hirano, T. Yoshihiro, H, Kashiwagi, F. Sato, "Density functional calculation of the electronic structure on insulin hexamer", Chem. Phys. Lett., 434, 331-335 (2007).
- N. Nishino-Uemura, T. Hirano, F. Sato, “Study of the quasi-canonical localized orbital method based on protein structures”, J. Chem. Phys., 127, 184106 (2007).
- T. Inaba, S. Tahara, N. Nisikawa, H. Kashiwagi, F. Sato, "All-electron density functional calculation on insulin with quasi-canonical localized orbitals.", J. Comput. Chem., 26, 987-93 (2005).

If you know the other unlisted articles using the ProteinDF, please let me know.

## License

ProteinDF は GNU GPL v3 に基づいて配布されます。
ソースコードは Github から取得できます。

## バグ・要望

バグを発見された場合はご連絡ください。
また機能追加などのご要望もお知らせ下さい。
