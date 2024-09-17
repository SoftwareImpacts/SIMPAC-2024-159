# QFLCS: Quantum Field Lens Coding Simulator  
Technical: [![On GitHub](https://img.shields.io/badge/GitHub-SoftwareImpacts-009688.svg?style=flat&amp;logo=github)](https://github.com/SoftwareImpacts/SIMPAC-2024-159)
[![Mendeley Badge](https://img.shields.io/badge/Mendeley%20Data-v.3+-red.svg)](https://data.mendeley.com/datasets/gf2s8jkdjf/3)
[![VSCode Badge](https://img.shields.io/badge/Code%20in%20VS%20Code-v.1.3-blue.svg?style=flat&amp;logo=vscode)](https://codeocean.com/capsule/6853712/tree/v2/code/root/lab/sim/QFLCC%20classifiers/QAI-LCode_QFLCC.py)
[![Code in Python v>3.1](https://img.shields.io/badge/Python-v.3+-3776AB.svg?style=flat&amp;logo=python&amp;logoColor=white)](https://codeocean.com/capsule/6853712/tree/v2/code/root/lab/sim/QFLCC%20classifiers/QDF-LCode_IBMQ-2024-codable.py)
[![Jupyter Lab](https://img.shields.io/badge/Jupyter-Lab-F37626.svg?style=flat&amp;logo=Jupyter)](https://codeocean.com/capsule/6853712/tree/v2/code/root/lab/sim/QFLCC%20classifiers/QDF-LCode_IBMQ-2024-raw-codable.ipynb)
[![Open in Code Ocean](https://codeocean.com/codeocean-assets/badge/open-in-code-ocean.svg)](https://codeocean.com/capsule/6853712/tree/v2)

Social: [![GitHub Profile](https://img.shields.io/badge/GitHub-phibal12%20profile%20+%20projects-009688.svg?style=flat&amp;logo=github)](https://github.com/phibal12)
[![Author's LinkedIn](https://img.shields.io/badge/LinkedIn-blue.svg?style=flat&amp;logo=linkedin&logoColor=white)](http://ca.linkedin.com/pub/philip-baback-alipour/b/b13/b35)

Academic: [![Author's ORCID](https://img.shields.io/badge/ORCID-0000--0003--1037--018X-A6CE39?logo=orcid)](https://orcid.org/0000-0003-1037-018X)

Legal: [![CC BY 4.0][cc-by-shield]][cc-by]
<hr/>

This repository contains the code for the QFLCS (Quantum Field Lens Coding Simulator) as part of its algorithm, QFLCA (Quantum Field Lens Coding Algorithm) project.
The project repositories are available at https://data.mendeley.com/datasets/gf2s8jkdjf/3 and https://doi.org/10.24433/CO.9905505.v2, which include the code, project website documentation, and demo video files.

<kbd> ![1D QDF circuit](1D-qdf-circuit.gif) </kbd> 

The QFLCS program analyzes the measurement outcome probability ($\cal P$) data from datasets generated by Quantum Double-field (QDF) Circuits. The datasets are compared between ES and GS states as a $\cal P$ indicator generated for measurement samples. Small dataset samples denote: 

|<kbd> ![QDF_Demo Line](QDF_demo_line.gif) </kbd>|
|:--:| 
|*QDF Heat Engine Sampling from the Oldest Postal Stamp and Simulating the I/O by QFLCS*|

- **a)** A particle pair’s energy state in a QDF (different GS states or sublevels of a GS, or see Sec. 3 of the published article), <br>
- **b)** a particle state in an SF, an ES relative to a GS from (a.), prior to its transform into a QDF, and, <br>
- **c)** the expected transformation of fields (ES $\longleftrightarrow$ GS) and their $⟨{\frak M}(\cal{P}, \psi_{ij})⟩$, as in Sec. 3 of the published article.

|<kbd> ![k-trans-QDF-P-measure-IN](k-trans-QDF-P-measure-IN.png) </kbd>|
|:--:| 
|*QDF Circuit Measured from a Sum (&nbsp;&Sigma;&nbsp;) of Single Field (SF) to QDF Transformations of Qbit-pairs*|

This repository's file structure is a sample mirror of the Mendeley repository file structure of v3+ at https://data.mendeley.com/datasets/gf2s8jkdjf/3, but with a much smaller file size for efficient download and use of the QFLCA project's code without the documentation (website) and demo video files. Certain small updates have been made in the main python file uploaded on Code Ocean for minor debugging purposes at https://doi.org/10.24433/CO.9905505.v2 or [Code Ocean](https://doi.org/10.24433/CO.9905505.v2). 

* QFLCA project's code without the documentation (website) and demo video files can be found under the <code></code/root/lab/sim/QFLCC classifiers></code> directory in <code></code/root/lab/sim/QFLCC classifiers/docs></code> and <code></code/root/lab/sim/QFLCC classifiers/site></code> folders at https://doi.org/10.24433/CO.9905505.v2 or [Code Ocean](https://doi.org/10.24433/CO.9905505.v2).
* The main file is <code></code/root/lab/sim/QFLCC classifiers/QAI-LCode_QFLCC></code> which imports and executes the <code></code/root/lab/sim/QFLCC classifiers/QDF-LCode_IBMQ-2024-codable></code> or <code>QDF-LCode_IBMQ-2024</code> code for the simulation under Win OS or Linux OS.

|<kbd> ![QInspire QDF_Circuit Experiment](<./root/lab/sim/QFLCC classifiers/QI_Exp_03.png>) </kbd>|
|:--:| 
|*QInspire QDF Circuit Experiment*|
|&#8597;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#8597;|
|<kbd> ![QInspire QDF_Circuit_Experiment Results](<./root/lab/sim/QFLCC classifiers/QI_Exp_03_H.png>) </kbd>|
|*QInspire QDF Circuit Experiment Results*|
|<kbd> ![IBM QDF_Circuit_Experiment](<./root/lab/sim/QFLCC classifiers/QDFCircuit_2023.png>) </kbd>|
|*IBM QDF Circuit Experiment*|
|${\color{orange}{In(}} {\color{red}{[\ QInspire\ ,\ IBMQ\ ]\ } }QDF\ Circuit\ {\color{orange}{)&nbsp;&#8594;&nbsp;}} {\color{orange}{QFLCS}} {\color{orange}{&nbsp;&#8594;&nbsp; Out(}}{ {\color{red}{[\ QInspire\ ,\ IBMQ\ ]\ }}  QDF\ Circuit\ Data\ }{\color{orange}{)&nbsp;&#8594;&nbsp; In(}}{\color{green}{QFLCC}}{\color{orange}{)&nbsp;&#8594;&nbsp; Out(&#8628;)}}$|
|<kbd> ![QDF_Circuit_Sim and Dataset Analysis](QDF_circuit_screenshot.jpg) </kbd>|
|${\color{red}{[\ QInspire\ ,\ IBMQ\ ]\ }} QDF\ Circuit\ Simulation\ and\ Dataset\ Analysis\ by\ QFLCS\ and\ QFLCC\$|

* We recommend downloading the entire <code><root/...></code> directory according to the folder structure and run <code>[QAI-LCode_QFLCC.py]</code> in VSC with python latest packages installed for Windows OS (the QDF game is developed for Windows OS, yet parts of the code for sound and display can be rewritten for Linux OS), e.g. <code>"winsound"</code> package as a compatible option. Other packages are needed to be installed or code rewritten for <code>"sound"</code> and <code>"display"</code> compatibility under other operating systems.
* The <code>[QAI-LCode_QFLCC.py]</code> file has a Pygame GUI and other packages suited for local machine runs, rather than running this file on the [Code Ocean](https://doi.org/10.24433/CO.9905505.v2) platform which could take hours to compile and run a compatible program/game with packages. 
However, the <code>[QDF-LCode_IBMQ-2024-codable.py]</code> can be run here as the core of the simulation program simulating the QDF circuit. 
A short presentation explaining these points are given in the <code></site/assets/video></code> directory as the <code>[QAI-COcean-Demo.mp4]</code> file from [Code Ocean](https://doi.org/10.24433/CO.9905505.v2).

|<kbd> <img src="Alice_Bob_Qauntum-Doubles.gif" style="border: 2px solid green" target="_blank" /> </kbd>|
|:--:| 
|*QDF Game Intro from the QFLCA/QFLCS program*|

* The User and Developer's documentation/manual/demo is found under the <code></code/root/lab/sim/QFLCC&nbsp;classifiers></code> directory, as <code><site-prints/...></code> and <code><site/...></code> contents.
* In each folder: <code><QFLCC classifiers/IBMQ>, <.../sim/QAI>, </QFLCC classifiers></code>, and <code><QI/...></code>, under <code></code/root/lab/sim></code>, <code>[Tips.txt]</code> and/or <code>[ReadMe.txt]</code> files exist to explain the contents of that directory. Also, under <code></code/root/lab></code> directory, a ReadMe file exists explaining the manual computation and presentation parts of the project.
  
|<kbd> ![QDF Game Scores Screenshot](QDF_game_screenshot.jpg) </kbd>|
|:--:| 
|*QDF Game Scores on Wins and Losses of the User/Gamer based on the Input Samples by the QFLCS*|

* Graphical Abstract files can be accessed from <code></code/root></code>.

# Visual Project Summary
The QFLCA project is going through stages of development resulting in software products, such as QFLCC and QFLCS programs. These products have been summarized in form of peer-reviewed published articles with their corresponding Graphical Abstracts representing this project.    

* The following figure is a downloadable High-Res Graphical Abstract of the published QFLCS article in Software Impacts, Elsevier BV, at: https://www.sciencedirect.com/science/article/pii/S2665963824000915
 
|<kbd> ![QFLCS Graphical Abstract (SIMPAC journal)](./root/SIMPAC_GAbstract.jpg) </kbd>|
|:--:| 
|*Graphical Abstract of QFLCS*|

* The following figure, is a downloadable High-Res Graphical Abstract of the published QFLCA article in Data in Brief, Elsevier BV, at: https://www.sciencedirect.com/science/article/pii/S2352340924007546

|<kbd> ![QFLCA Graphical Abstract (DIB journal)](./root/DIB_GAbstract.png) </kbd>|
|:--:| 
|*Graphical Abstract of QFLCA Dataset*|

* The following figure is a downloadable High-Res Graphical Abstract of the published QFLCA article in MethodsX, Elsevier BV, at: https://www.sciencedirect.com/science/article/pii/S221501612300136X

|<kbd> ![QFLCA Graphical Abstract (MethodsX journal)](./root/MethX_GAbstract.png) </kbd>|
|:--:| 
|*Graphical Abstract of QFLCA Model and Method*|

# Citation
If you find this repository useful in your research, please cite one or both of the following articles as: 
<hr />

- P. B. Alipour, T. A. Gulliver,
QF-LCA Dataset: Quantum Field Lens Coding Algorithm for System State Simulation and Strong Predictions, Data in Brief, Eslevier BV,
2024, 110789, ISSN 2352-3409, https://doi.org/10.1016/j.dib.2024.110789.

```
@article{110789, 
author = {Alipour, P.B. and Gulliver, T.A.},  
title = {QF-LCA Dataset: Quantum Field Lens Coding Algorithm for System State Simulation and Strong Predictions}, 
journal = {Data in Brief, Eslevier BV}, 
year = {2024}, 
artnum = {110789}, 
doi = {10.1016/j.dib.2024.110789}, 
url = {https://www.sciencedirect.com/science/article/pii/S2352340924007546} 
}
```

- P. B. Alipour, T. A. Gulliver,
QF-LCS: Quantum Field Lens Coding Simulator and Game Tool for Strong System State Predictions, Software Impacts, Eslevier BV,
2024, 100703, ISSN 2665-9638, https://doi.org/10.1016/j.simpa.2024.100703.

```
@article{100703, 
author = {Alipour, P.B. and Gulliver, T.A.}, 
title = {QF-LCS: Quantum Field Lens Coding Simulator and Game Tool for strong system state predictions}, 
journal = {Software Impacts, Eslevier BV}, 
pages = {100703}, 
year = {2024}, 
issn = {2665-9638}, 
doi = {doi.org/10.1016/j.simpa.2024.100703}, 
url = {https://www.sciencedirect.com/science/article/pii/S2665963824000915} 
}
```


<hr />

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
