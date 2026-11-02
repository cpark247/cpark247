### Hi, I'm Changkyu Park 👋

CFD engineer working on **turbulent and gas–liquid flows**: from solver code in OpenFOAM, through validation against DNS and experiments, to design recommendations for industry.
Doctoral researcher at Ruhr University Bochum (Dr.-Ing. expected early 2027) · M.Sc. & B.Sc. Aerospace Engineering, TU Delft.

---

#### Projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/cpark247/diffuser-gas-accumulation"><img src="assets/paper.png" alt="Two-phase LES of gas accumulation"></a><br>
<b><a href="https://github.com/cpark247/diffuser-gas-accumulation">diffuser-gas-accumulation</a></b> · <i>doctoral research, paper</i><br>
3D two-phase LES (Euler–Euler + population balance) of a diverging channel, validated against experiments: can surface structures passively reduce gas accumulation?
</td>
<td width="50%" valign="top">
<a href="https://github.com/cpark247/virtual-hole-method"><img src="assets/virtual-hole.png" alt="Virtual Hole Method"></a><br>
<b><a href="https://github.com/cpark247/virtual-hole-method">virtual-hole-method</a></b> · <i>industry project</i><br>
Flushing holes in pump impeller blades simulated without new CAD or mesh: coupled cyclicACMI face sets with a handbook-based (Idelchik) pressure jump. Captures gas flushing and head recovery in two-phase flow; cut design iterations from weeks to minutes and was adopted by the industrial partners.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/cpark247/turbulence-validation-OF9"><img src="assets/validation.png" alt="Turbulence model validation"></a><br>
<b><a href="https://github.com/cpark247/turbulence-validation-OF9">turbulence-validation-OF9</a></b> · <i>preliminary doctoral work</i><br>
Can a modified SST-SAS model resolve turbulence-driven secondary flow without spoiling the mean flow? Six variants against k-ω SST, RSM-SSG, WALE LES and DNS/experiment on channel, square-duct and diffuser flows, with run cost. The answer was no, so LES was chosen.
</td>
<td width="50%" valign="top">
<a href="https://github.com/cpark247/openfoam9-multiphase-les-extensions"><img src="assets/library.png" alt="OpenFOAM extensions"></a><br>
<b><a href="https://github.com/cpark247/openfoam9-multiphase-les-extensions">openfoam9-multiphase-les-extensions</a></b> · <i>code behind the doctoral work</i><br>
C++ solvers, models and utilities for OpenFOAM v9: multiphase solver family for LES/SAS with population balance, extended SST/SAS models, run-time turbulence statistics.
</td>
</tr>
</table>

#### Selected results
- **Virtual Hole Method** (industry project): models holes in pump impeller blades through a boundary condition instead of geometry, cutting design iteration cycles from weeks to minutes; adopted by industry partners.
- **Multi-stage HPC workflow** on SLURM clusters that saved more than 10 million core-hours.
- Led the simulation work package of a publicly funded research project with industrial pump manufacturers.

#### Publication
C. Park, M. Mansour, D. Thévenin, R. Skoda. *Passive Mitigation of Gas Accumulation by Surface Structures in Diverging Flow Channels: A Three-Dimensional Two-Phase Flow Simulation Study.* [SSRN preprint, 2026](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7649860)

#### Tools
OpenFOAM (C++ development) · ANSYS Fluent · Python (NumPy, SciPy, pandas, PyVista) · MATLAB · Linux / SLURM HPC · Git · ICEM CFD, Pointwise · LaTeX / pgfplots

#### Contact
[LinkedIn](https://www.linkedin.com/in/changkyupark/) · changkyu.park247@gmail.com
