# Copyright (c) 2020 Akishi Matsugatani, Seishiro Ono, Yusuke Nomura, Haruki Watanabe

======================================


Here, qeirreps/reference is the directory which stores some output files of QE, qe2respack, and qeirreps as examples.

See also qeirreps/example to confirm and test the input files.


======================================

# Contents

Bi_nonsoc:
Calculation for bismuth without spin-orbit coupling

Bi_soc:
Calculation for bismuth with spin-orbit coupling

Si_nonsoc:
Calculation for silicon without spin-orbit coupling

Si_soc:
Calculation for silicon with spin-orbit coupling

NaCdAs_nonsoc:
Calculation for NaCdAs without spin-orbit coupling

NaCdAs_soc:
Calculation for NaCdAs with spin-orbit coupling

PbPt3_nonsoc:
Calculation for PbPt3 without spin-orbit coupling

PbPt3_soc:
Calculation for PbPt3 with spin-orbit coupling


======================================

# About materials

The samples for four types of materials are available here.

Brief explanation for each material is as follows.
See "https://materialsproject.org/" and the DFT input files to confirm the structure data.

Bi:
symmetry group: R-3m (#166), symmorphic
One of the candidates for a higher-order topological insulator.
With the spin-orbit coupling, the symmetry-based indicator is calculated from the inversion parities of Bloch wave functions.
Z4 index can be evaluated by using the function of qeirreps: z4 = 2.

Si:
symmetry group: Fd-3m (#227), non-symmorphic
A trivial semiconductor.
With the spin-orbit coupling, the symmetry-based indicator is calculated from the inversion parities of Bloch wave functions.
Z4 index can be evaluated by using the function of qeirreps: z4 = 0.

NaCdAs:
symmetry group: Pnma (#62), non-symmorphic
One of the candidates for a topological insulator.
With the spin-orbit coupling, the symmetry-based indicator is calculated from the inversion parities of Bloch wave functions.
Z4 index can be evaluated by using the function of qeirreps: z4 = 1.

PbPt3:
symmetry group: Pm-3m (#221), symmorphic
One of the candidates for a topological semimetal.
The symmetry-based indicator is related to the inversion, rotoinversion, and mirror symmetry.
Z4 and Z8 indices can be evaluated from the result of qeirreps: (z4, z8) = (3,6).
REMARK: This Z4 index is different from those of bismuth, silicon, and NaCdAs.


======================================


See each reference directory for detailed information about output files.


======================================
