## MOS Tunneling Mechanisms

As the thickness of gate dielectrics decreases in modern MOS devices, charge transport
through the dielectric becomes dominated by quantum mechanical tunneling processes.
Understanding these tunneling mechanisms is essential for analyzing leakage current and
device reliability.

The most commonly observed tunneling mechanisms in MOS capacitors with high-k
dielectrics are Fowler–Nordheim tunneling and Poole–Frenkel emission.

---

### 1. Fowler–Nordheim (FN) Tunneling

Fowler–Nordheim tunneling occurs at high electric fields when charge carriers tunnel
through a triangular potential barrier formed at the dielectric interface. This mechanism
is typically observed in thicker dielectric films under strong electric fields.

**Key characteristics:**
- Dominant at high electric fields
- Temperature independent
- Strongly dependent on oxide thickness
- Indicates good dielectric quality

The FN tunneling current density can be expressed as:

\[
J_{FN} \propto E^2 \exp\left(-\frac{B}{E}\right)
\]

where \(E\) is the applied electric field and \(B\) is a material-dependent constant.

A linear relationship between \(\ln(J/E^2)\) and \(1/E\) confirms Fowler–Nordheim tunneling.

---

### 2. Poole–Frenkel (PF) Emission

Poole–Frenkel emission is a bulk-limited conduction mechanism caused by the thermal
excitation of trapped charge carriers into the conduction band of the dielectric.
The applied electric field lowers the Coulombic potential barrier, enhancing carrier
emission.

**Key characteristics:**
- Dominant at low to moderate electric fields
- Temperature dependent
- Indicates presence of defect states or traps
- Common in high-k dielectric materials

The Poole–Frenkel current density follows:

\[
J_{PF} \propto E \exp\left(-\frac{q(\phi_t - \beta \sqrt{E})}{kT}\right)
\]

where \(\phi_t\) is the trap depth, \(E\) is the electric field, and \(\beta\) is the
Poole–Frenkel coefficient.

A linear relationship between \(\ln(J/E)\) and \(\sqrt{E}\) confirms PF emission.

---

### 3. Conduction Mechanism Identification

By analyzing I–V characteristics and fitting experimental data to FN and PF models, the
dominant conduction mechanism can be identified across different electric field regions.

In HfO₂-based MOS capacitors:
- Poole–Frenkel emission dominates at low electric fields due to trap-assisted conduction
- Fowler–Nordheim tunneling dominates at high electric fields, indicating field-driven
  tunneling through the dielectric

This transition provides valuable insight into dielectric quality, trap density, and
overall device performance.
