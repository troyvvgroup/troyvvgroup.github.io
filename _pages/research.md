---
title: "Research"
layout: default
excerpt: "Research"
sitemap: false
permalink: /research/
---

# Research

## Bootstrap Embedding
![be_picture](../images/research/bootstrap_pic.png){: width="50%"}

Electron correlation is intrinsically local and this can be exploited by a variety of embedding methods. These embedding methods partition the system into small fragments that can each be manageably treated with high-accuracy theories, and use a cheaper theory for the interactions of the fragment with its surrounding bath. The largest errors lie at fragment edges where fragment-bath interactions are most strong. To overcome this, we have developed a fragment embedding scheme where the system is partitioned into overlapping fragments, each with an accurately described center and inaccurately described bath. We constrain the edge site of one fragment to match the same site on an overlapping fragment, where that site is in that fragment’s center. In this way, the calculation pulls itself up by its own bootstraps, giving this method the name Bootstrap Embedding.

Bootstrap Embedding has seen initial success in our group for lattice models and simple molecular systems. We have extended the success of Bootstrap Embedding to molecules where fragment centers can naturally be defined as atoms and the fragment edges as atoms bonded to the center. Current work in our group focuses on improving and applying Bootstrap Embedding in the context of real molecules in large basis sets.


## Quantum Dots
[//]: # "TODO: Add a cool diagram / picture"
Our group investigates the geometry - electronic structure relationships of nanocrystals, especially colloidal quantum dots, in the ground and excited states. Implementation of nanocrystals in photovoltaic and photoemissive devices is hampered by mid-gap electronic states known as trap states, which are often associated with surface defects. Our group has investigated the nature and origin of these trap states in II-VI and III-V semiconductor nanocrystals, finding differing behavior in the two classes of materials, new types of trap states not previously described in these nanocrystals, and specific trends related to site coordination number, species, geometry, and electrostatic environment which influence trap presence and depth. We have further investigated how trap states are affected by surface reconstruction and how they are influenced by the presence of an inorganic shell.

Through collaboration with experimental groups at MIT and further afield, we have leveraged our expertise in nanocrystal electronic structure to study the geometry and ligand binding preferences of lead halide perovskite nanoplatelets and the X-ray photoelectron spectra of InGaP mesas. Moreover, we have developed a super-resolution technique known as the Broad Yet Narrow Description (BYND) for accurately simulating entire absorption spectra of large material systems at a fraction of the traditional cost. BYND does this by optimizing a highly approximate TD-DFT spectrum obtained with the Small Matrix Approximation (SMA) to fit a high accuracy but low resolution short time signal obtained from real-time TD-DFT. Along a similar vein, current work focuses on utilizing a kernel ridge regression to learn guess Hamiltonian - converged Hamiltonian mappings for specific systems to extend ab-intio molecular dynamics (AIMD) simulations for large systems to far longer timescales.
Most DFT studies of nanocrystals ignore thermal and ensemble effects, which precludes direct comparison with experimental absorption and emission spectra. The conventional method to generate thermally averaged spectra is the Nuclear Ensemble Approach (NEA), which requires extensive sampling and is prohibitively expensive for QDs beyond the ultrasmall regime. To address this issue, our group proposes a less resource-intensive approach: the Harmonic Approximation (HA), which assumes the electronic potential energy surfaces of QDs to be harmonic, with excited states having the same curvature as the ground state. Absorption spectra for QDs computed with the equilibrium HA accurately capture thermal broadening and Urbach band tailing, at a fraction of the cost of the NEA method.

We are also interested in examining exciton-phonon coupling, using the Huang-Rhys (HR) factor metric. Our findings suggest that the degree and effectiveness of surface passivation has a sizeable effect on the magnitude of exciton-phonon coupling. Successful passivation strategies for nanocrystals should not only minimize the number of trap states, but also reduce the spatial overlap between excitons and phonons, thereby lowering the HR factors.

