---
title: Projects
icon: fas fa-code-branch
order: 1
---





# Local comparison of protein pockets
## Method
Date: *2019-*<br>
The goal of this project is to develop a method capable of assessing local similarity between protein pockets.
Detection of such similarities can partly explain the binding of similar molecular partners (similarity principle) and can thus be exploited for drug design: polypharmacology, hits discovery and library design. We implemented a point cloud registration (PCR) method for pockets represented a cloud of points with pharmacophoric properties. Point Cloud registration is an image processing approach in Computer Vision to superimpose two clouds of points (e.g. different camera views of 3D scenes) where they match. In our biological objects, the challenges are to find *where the clouds match* as (i) this is not obvious to a human eye and (ii) we want to assess thousands of pockets, and then to find a discriminatory scoring function to quantify that similarity. <br>
The pricinples behind PCR algorithm (local descriptors, nearest neighbor search, random sample consensus, topological verifications) appears promising for the task, particularly for small pockets (subpockets) alignment to large pockets. While acknowledging potential limitations, we evaluated the method on retrospective datasets, while comparing to state-of-the art methods. <br>
Code: [https://github.com/kimeguida/ProCare](https://github.com/kimeguida/ProCare)
Publication: [https://doi.org/10.1021/acs.jmedchem.0c00422](https://doi.org/10.1021/acs.jmedchem.0c00422)

## Prospective applications in drug design
Feedback on the prospective performance of computational methods can help to improve them to solve real-world problems. This observation motivates me to pursue the following studies.

#### Secondary target prediction
Date: *2020-2021-*<br>
We compared the pocket at the trimeric interface of TNF-alpha (pro-inflammatory cytokine) to a database of druggable pockets and identified pocket clouds and protein residues similarity with HIV1-RT non-nucleoside pocket, driven by hydrophobic and some polar matches. Biophysical assays showed a dose-dependent interactions of 2 HIV-1 non-nucleoside inhibitors with TNF. Interestingly, these two proteins differ by their sequence, structure and functions, therefore the detected similarity was not obvious. Although resolved 3D structures are needed to confirm the binding site and further the study toward a target-based drug design project, these results already showed how we can use subpockets comparison for hits idea generation.
Data: [https://github.com/kimeguida/ProCare_TNF](https://github.com/kimeguida/ProCare_TNF)
Publication: [https://doi.org/10.1186/s13321-021-00567-3](https://doi.org/10.1186/s13321-021-00567-3)

#### Library design (proof-of-concept with CDK8)
Date: *2020-2022-*<br>
The objective of this project is to use fragments moieties in accessible protein-ligand complexes to design target-focused libraries of molecules, on the basis subpocket similarities. <br>

#### Library design for an antibacterial target
<br>

#### Library design for an orphan WD40 domain (LRRK2) - CACHE Challenge
 [CACHE Challenge](https://cache-challenge.org/competitions/challenge-1)) (*2022*) <br>


# Machine learning on protein pockets (*2021-2022*)

# Analysis of transmembrane proteins interactions (Collab. *2019-2022*)

<br>

# Optimization of a branch & bound algorithm for protein pockets alignment: comparative study (Collab. *2020-2021*) <br>
<br>

# Structure-based lead optimization (Collab. *2020-2021*)
<br>


