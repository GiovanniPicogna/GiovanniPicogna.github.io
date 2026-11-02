---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the full CV (PDF)](/files/CV_Picogna.pdf)

Education
======
* B.S. in Astronomy, University of Padua, 2006
* M.S. in Astronomy, University of Padua, 2010
* Ph.D. in Science, Technologies and Space Measurements (Curriculum: Astronautics and Satellite-based Science), CISAS (University of Padua), 2014

Work experience
======
* June 2014 - March 2016: post-doc
  * University of Tübingen
  * I addressed the evolution of pebbles and small planetesimals in the protoplanetary nebula and their role in the buildup of giant planet’s core, by implementing a population of Lagrangian particles in two grid‐based hydro codes.
  * Supervisor: Wilhelm Kley

* April 2016 - current: research scientist (post-doc)
  * Ludwig Maximilian University of Munich
  * I lead the radiation-hydrodynamics modelling of the group: a coupled C/Fortran/Python chain linking MOCASSIN (photoionisation and dust radiative transfer) and PRIZMO (thermochemistry) to the PLUTO MHD solver, from the governing equations to validation and public release. Its model grids are used as input physics by external groups.
  * Co-developed autoencoder surrogates that reduce a chemical reaction network 10x and halve simulation time.
  * More than 100,000 CPU-hours per year of peer-reviewed allocation on national supercomputers (SuperMUC-NG and c2pap, LRZ; ForHLR, KIT).
  * Supervisor: Barbara Ercolano

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

* I supervised 4 PhD students and 6 Master students working in Barbara Ercolano’s group.
* I did tutorial classes for the lectures: "Planetary Atmospheres and the Search for Life", "The Formation and Evolution of Planets in Protoplanetary Discs", and "Essentials of Advanced Astrophysics".
* I co-supervised several bachelor and master students for their seminar classes.

Coding Skills
======
* Programming languages
  * Python
  * C/C++
  * FORTRAN
  * bash scripting
* Numerical codes
  * [PLUTO](http://plutocode.ph.unito.it/)
  * [MOCASSIN](https://mocassin.nebulousresearch.org/)
  * [FARGO/FARGO3D](https://fargo3d.bitbucket.io/)
  * [PHANTOM](https://phantomsph.github.io/)
  * [VINE](https://www.usm.uni-muenchen.de/people/mwetz/Overview.html)
  * [RADMC3D](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/)
* Libraries
  * MPI/OpenMP, SLURM
  * GSL, FFTW, HDF5
  * NumPy, SciPy, Astropy, Matplotlib, etc.
* Machine learning
  * PyTorch
  * Autoencoders, physics-informed neural networks (PINNs), surrogate and reduced-order models
* Software engineering
  * Git/GitHub, GitHub Actions (CI/CD), Docker, Python packaging
* LaTeX
