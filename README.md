<div align="center">

# Safouan Ziat, Ph.D.

### Computational Materials Scientist & Surface Physicist

*DFT · Machine-Learned Interatomic Potentials · Reaction Kinetics · Hands-on UHV STM/MBE*

📍 Nancy, France

<a href="https://www.linkedin.com/in/ziat-safouan-427826134/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:safouanziat@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://doi.org/10.1021/acs.jpclett.5c03805" target="_blank">
  <img src="https://img.shields.io/badge/J._Phys._Chem._Lett.-Publication-orange?style=for-the-badge" alt="J. Phys. Chem. Lett. publication" />
</a>

[Profile](#-profile) · [Currently](#-currently) · [Skills](#-skills) · [Projects](#-highlighted-repositories) · [Publications](#-selected-publications) · [Education](#-academic-background)

</div>

---

## 🔬 Profile

Ph.D. in Materials Science and Solid-State Physics (Université de Lorraine / CNRS – Institut Jean Lamour). I bridge **hands-on ultra-high vacuum (UHV) surface physics** with **first-principles electronic structure** and **equivariant machine-learning interatomic potentials**, from the STM tip to the supercomputer.

## 🌱 Currently

- ⚛️ Building autonomous **active-learning pipelines** (MACE + jobflow) that train MLIPs to DFT accuracy and extract kinetics (CI-NEB, BEP scaling) for single-atom catalysts.
- 💥 Developing an **autonomous defect-engineering pipeline** (ASE + LAMMPS) that simulates high-energy Ar/N bombardment of graphene to generate vacancy and N-doped defect sites for single-atom catalyst supports.
- 🧪 Studying **H₂ dissociation** on N-doped graphene-supported transition-metal single-atom catalysts.

---

## 🛠 Skills

<table>
  <tr>
    <td width="50%" valign="top">

**⚛️ Electronic Structure & DFT**

Periodic plane-wave and grid-based DFT (VASP, Quantum ESPRESSO, GPAW), spin polarization, adsorption energetics, CI-NEB transition-state search, and electronic descriptors (Bader charges, d-band center, COHP/ICOHP via LOBSTER).

</td>
    <td width="50%" valign="top">

**🤖 Machine Learning & MLIPs**

Training and fine-tuning of equivariant MLIPs (MACE, NequIP, SevenNet), on-the-fly active-learning molecular dynamics, compressed-sensing symbolic regression (SISSO), and classical/reactive MD with LAMMPS (AIREBO, ZBL, ReaxFF).

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

**🔭 UHV Surface Science**

Variable-temperature polar STM (4 K liquid He / ~90 K liquid N₂), thin-film growth by Molecular Beam Epitaxy (MBE), surface preparation (Ar<sup>+</sup> sputtering, annealing, defect engineering), and STM/LDOS image simulation from DFT configurations.

</td>
    <td width="50%" valign="top">

**🖥️ HPC & Automation**

End-to-end Python workflows (ASE, Pymatgen) for high-throughput screening, SLURM job handling, and convergence checks on Tier-1 supercomputers (GENCI, several million CPU hours).

</td>
  </tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/VASP-DFT-1b4d3e?style=for-the-badge" alt="VASP" />
  <img src="https://img.shields.io/badge/Quantum_ESPRESSO-DFT-003366?style=for-the-badge" alt="Quantum ESPRESSO" />
  <img src="https://img.shields.io/badge/GPAW-DFT-2b5b84?style=for-the-badge" alt="GPAW" />
  <img src="https://img.shields.io/badge/MACE-Equivariant_MLIP-8A2BE2?style=for-the-badge" alt="MACE" />
  <img src="https://img.shields.io/badge/ASE-Atomic_Simulation_Environment-00599C?style=for-the-badge" alt="ASE" />
  <img src="https://img.shields.io/badge/LAMMPS-Molecular_Dynamics-d14836?style=for-the-badge" alt="LAMMPS" />
  <img src="https://img.shields.io/badge/jobflow-Workflow_Orchestration-28a745?style=for-the-badge" alt="jobflow" />
  <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB Atlas" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/SQL-Queries-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/UHV_STM_%2F_MBE-Surface_Science-007acc?style=for-the-badge" alt="UHV STM / MBE" />
  <img src="https://img.shields.io/badge/Linux_%26_SLURM-HPC-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux and SLURM" />
</p>

---

## 🚀 Highlighted Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/safouanziat/MACE-ActiveLearning-SAC"><b>MACE-ActiveLearning-SAC</b></a><br><br>
      Autonomous active-learning pipeline (MACE + jobflow): MLIP training to DFT accuracy, automated CI-NEB and BEP scaling for H₂ dissociation on N-doped graphene-supported Pd single-atom catalysts.<br><br>
      <img src="https://img.shields.io/badge/MACE-8A2BE2" alt="MACE" /> <img src="https://img.shields.io/badge/jobflow-28a745" alt="jobflow" /> <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white" alt="MongoDB Atlas" /> <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite" />
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/safouanziat/Autonomous_Pipeline_SAC"><b>Autonomous_Pipeline_SAC</b></a><br><br>
      Multi-phase active-learning pipeline coupling GPAW (DFT) and MACE (MLIP) for high-throughput screening, CI-NEB kinetics and dynamic stability of Pt–N<sub>x</sub>C<sub>y</sub> single-atom catalysts.<br><br>
      <img src="https://img.shields.io/badge/GPAW-2b5b84" alt="GPAW" /> <img src="https://img.shields.io/badge/MACE-8A2BE2" alt="MACE" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <!-- TODO: wrap the title below in a link to the repository once it is public: <a href="https://github.com/safouanziat/REPO_NAME"> -->
      <b>Autonomous Defect Engineering (MD)</b><br><br>
      ASE + LAMMPS pipeline simulating high-energy particle bombardment on a 32×32 graphene supercell (2048 C atoms). Ar impacts (AIREBO + ZBL) and N impacts (ReaxFF with <code>qeq/reaxff</code>) over 20–80 eV and on-top / bridge sites: 28 scenarios generating vacancies, di-vacancies and N-doped defect sites for catalytic evaluation.<br><br>
      <img src="https://img.shields.io/badge/LAMMPS-MD-d14836" alt="LAMMPS" /> <img src="https://img.shields.io/badge/ASE-00599C" alt="ASE" /> <img src="https://img.shields.io/badge/ReaxFF-AIREBO%2FZBL-6f42c1" alt="ReaxFF, AIREBO, ZBL" />
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/safouanziat/Python_poisson"><b>Python_poisson</b></a><br><br>
      High-precision numerical integration of 1D Poisson equations using the Numerov method.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
    </td>
  </tr>
</table>

---

## 📚 Selected Publications

1. **S. Ziat**, F. Brix, A. Tsaturyan, B. Kierren, É. Gaudry, *"How N-Doping Promotes Hydrogen Dissociation at Graphene-Based Single-Atom Catalysts"*, **J. Phys. Chem. Lett.**, 2026.  
   [doi:10.1021/acs.jpclett.5c03805](https://doi.org/10.1021/acs.jpclett.5c03805)
2. Théo Bequet, Florian Brix, **Safouan Ziat**, Corentin Martinez, Laurent Piccolo, et al., *"The Tradeoff behind Optimal 3-Fold (C,N)-Coordinated Single-Atom Catalysts"*, **Nano Letters**, 2026.  
   [doi:10.1021/acs.nanolett.6c02777](https://doi.org/10.1021/acs.nanolett.6c02777)
3. U. Khan, J. A. Okolie, **S. Ziat**, *"Activated carbon as catalyst support and electrocatalyst for industrial chemical reactions"*, in *Activated Carbon: Progress and Applications*, Ch. 9, **Elsevier**, 2025.  
   [doi:10.1016/B978-0-443-13840-9.00009-3](https://doi.org/10.1016/B978-0-443-13840-9.00009-3)

---

## 🎓 Academic Background

| Period | Degree | Institution |
| :---: | :--- | :--- |
| 2022–2026 | **Ph.D. in Materials Science & Solid-State Physics**<br>*Thesis: DFT Study of H₂ Dissociation on Transition-Metal Single-Atom Catalysts Supported on N-Doped Graphene* | Université de Lorraine, CNRS – Institut Jean Lamour |
| 2021–2022 | **M.Sc. in Condensed Matter & Nanophysics** (With Honours) | University of Strasbourg, IPCMS |
| 2017–2019 | **M.Sc. in Advanced Materials & Renewable Energies** (With Honours) | Université Moulay Ismail, Meknès |

---

## 📊 GitHub Activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=safouanziat&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=safouanziat&layout=compact&hide_border=true" alt="Top languages" />
</p>
