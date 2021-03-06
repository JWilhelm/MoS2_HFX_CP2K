# MoS2_HFX_CP2K

6x6 Supercell of MoS2 monolayer (xy-cell: a = 18.9 A, b = 18.9 A, angle = 120 °), periodic in XY plane, HFX truncation radius 9 A, all calculations are contained in this git repository

HFX total energy:

     cell height (z-dir)      PERIODIC XYZ         PERIODIC XY (code so far)     PERIODIC XY (fixed code)
          5 A                 -961.166166 H            -1018.127672 H            -907.292848 H
          6 A                 -951.733678 H             -953.965018 H            -895.385226 H
          7 A                 -943.593107 H             -943.616900 H            -895.407575 H
          8 A                 -935.281002 H             -935.280853 H            -895.420504 H
         10 A                 -898.016572 H             -898.016592 H            -895.421919 H
         12 A                 -895.446936 H             -895.446925 H            -895.421939 H
         14 A                 -895.422045 H             -895.422044 H            -895.421942 H
         16 A                 -895.421937 H             -895.421940 H            -895.421937 H
         18 A                 -895.421937 H             -895.421935 H            -895.421936 H
         20 A                 -895.421940 H             -895.421939 H            -895.421940 H

As it can be seen from the table, the HFX total energy converges much faster with the cell height using the new fixed code and "PERIODIC XY" (for example 10 A height already yields milli-Hartree accuracy) compared to the old code using "PERIODIC XY" or "PERIODIC XYZ".
