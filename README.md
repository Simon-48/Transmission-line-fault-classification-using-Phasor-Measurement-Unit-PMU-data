# Transmission-line-fault-classification-using-Phasor-Measurement-Unit-PMU-data
## Ensemble learning based transmission line fault classification using Phasor Measurement Unit (PMU) data with explainable AI (XAI)

### Short circuit fault analysis has been performed to categorize faults in electrical transmission line.

### There are two categories of short circuit faults, such as

###    Symmetrical Faults (Three Phase Faults):

         -Line to line to line to ground (L-L-L-G)
         -Line to line to line (L-L-L)

###    Unsymmetrical Faults (Single  & Double Line Faults):

         -Line to ground (L-G)
         -Line to line (L-L)
         -Double line to ground (LL-G)

         
## Data Description

        -Ia, Ib, Ic:  Three-phase sinusoidal current.
        -Va, Vb, Vc:  Three-phase sinusoidal voltage.
        -Im, Iv:      Magnitude of the three phase sinusoidal current and voltage.
        -Fi, Fv:      Frequency (Hz) of three phase sinusoidal current and voltage.
        -Pai, Pav:    Phase angle (degree) of three phase sinusoidal current and voltage.

## Target Labels
         
         -NF:    Balanced signal flow, no direct contact between conductors and ground.
         -L-G:   A single line fault occurs when one conductor on a transmission line contacts the neutral conductor or drops to the ground.
         -LL:    Double line fault refers to a situation in which two conductors are short circuited.
         -LL-G:  A double line to ground fault occurs from a short circuit between two phase conductors and ground.
         -LLL:   A three phase short circuit fault defines a short circuit between three phase conductors.
         -LLL-G: A short circuit between three phase conductors and the ground is referred to as a three phase to ground fault.
