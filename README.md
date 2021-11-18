# Abrasion-Ablation Monte Carlo for Colliders or AAMCC

Abrasion-Ablation Monte Carlo for Colliders (AAMCC) is Monte-Carlo model specially desined to describe spectator matter production in a wide range 
of colliding nuclei and energy of the collision on the event-by-event basis

## Main assumtions of AAMCC
 
 - Nucleus-nucleus collisions are simulated by means of the Glauber Monte Carlo model. Non-participated nucleons form spectator matter (prefragment).
 - Excitation energy of prefragment is calculated as follows: 
  - in peripheral collisions with less then ~15% of removed nucleons the particle-hole model is used 2) (Ericson formula);
  - otherwise a parabolic ALADIN approximation 3) is applied with parameters tuned to data obtained in nuclear emulsions.
- Decays of prefragments are simulated as follows:
  - pre-equilibrium decays modelled with MST-clustering algorithm;
  - Fermi break-up model from Geant4 v9.2 4);
  - Weisskopf-Ewing evaporation model from Geant4 v10.4 4).
