# Study Notes

## Embedded SiGe S/D in pMOS

SiGe Source/Drain can impose compressive stress on a pMOS channel. In the simulated structure, increasing Ge fraction increases the magnitude of channel compressive stress and improves drive-related metrics, but leakage can also rise.

## Fin Recess Depth

FR is the additional Source/Drain fin recess depth used before filling the recessed region with SiGe.

A deeper recess brings the stressor geometry closer to the channel and can improve stress transfer, but excessive recess also changes the electrostatics around the fin and can weaken short-channel control.

## Stress Transfer Efficiency

The project uses STE to separate the amount of nominal stress input from the fraction effectively appearing in the channel.

STE = |channel stress| / nominal Ge-based stress

The final numerator is the ChFin volume-averaged longitudinal stress.

## Why SS, DIBL, and Ioff Are Kept Separate

- SSlin: gate electrostatic control in the subthreshold region
- DIBL: drain-induced barrier lowering / short-channel behavior
- Ioff_norm: leakage cost
- gmSat and IdSat_norm: drive-performance response

The project avoids collapsing these different physical effects into one score.

## Engineering Interpretation

The useful process window is not the point with maximum stress. It is the region where additional stress-transfer gain begins to saturate before leakage and electrostatic penalties accelerate.
