# Custom data analysis for NTA 

Nanoparticle Tracking Analysis (NTA) is a method of high-throughput characterization of nanoparticle sizes in liquid samples. The diameters of particles are determined from time series (diffusive trajectories), which are recorded en masse. See [my paper](https://arxiv.org/pdf/1701.09001.pdf) for full explanations and context. The goal of this script is to access raw trajectory data (.csv files outputted by NanoSight analyzer) and perform custom analysis of trajectories, taking into accout the possible anomality of diffusion, drift, trajectories' lengths etc., as well as testing the performance of a few different diffusion models to improve particle size prediction. The results were also compared to Atomic Force Microscopy measurements to assess the performance. GitHub is not very Mathematica friendly, so in `NTA_analysis_code.pdf` you can find human-readable version, while `NTA_analysis_code.nb` is the actual notebook.

<p align='center'> <img src=techniques.png height=400> <img src=beads_hist.png height=400></p>
<p align='center'>  <img src=MSDexamples.png height=300>  <img src=Vexamples.png height=300></p>p
