# LES-emulator-04configFiles

This repository holds configuration files that are needed to produce results of Ahola et al 2021 manuscript.

[locationsMounted.yaml](locationsMounted.yaml) holds all the necessary location that are needed to produce the results.
- **trainingSimulationRootFolder** is the location of LES runs that holds subdirectories          
  - "case_emulator_DESIGN_v3.0.0_LES_ECLAIR_branch_ECLAIRv2.0.cray.fast_LVL3_night"
  - "case_emulator_DESIGN_v3.1.0_LES_ECLAIR_branch_ECLAIRv2.0.cray.fast_LVL3_day"
  - "case_emulator_DESIGN_v3.2_LES_ECLAIR_branch_ECLAIRv2.0.cray.fast_LVL4_night"
  - "case_emulator_DESIGN_v3.3_LES_ECLAIR_branch_ECLAIRv2.0.cray.fast_LVL4_day"
- **postProsDataRootFolder** is the location where you want to store parameterisation results
- **figureFolder** is the location where figures will be saved
- **configFile** is the location of [phase02.yaml](phase02.yaml)

[phase02.yaml](phase02.yaml) holds the hyperparameters that are used when creating parameterisations.
