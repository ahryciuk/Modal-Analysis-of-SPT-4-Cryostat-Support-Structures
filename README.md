# Modal-Analysis-of-SPT-4-Cryostat-Support-Structures
Modal analysis of 300 Kelvin to 4 Kelvin G10 supports and the 4 Kelvin to 100 milliKelvin Titanium focal plane supports

## My Role:
- Led design and validation efforts
- Defined design criteria with input from the Optics team (physical layout, materials, weight distribution, etc)
- Built finite element analysis pipeline to evaluate possible design choices

## Design Notes and Constraints:
- Telescope drive frequencies are <15 Hz
- 99 millimeters of space between vacuum window and first lens
- same area/length ratio between all design choices
- 11 kg per optics tubes (7 total) with offset center of mass (5 kg detector module mounted on back)

## Summary of Results:
- Hybrid G10 tab and bipod design limits thermal stress from differential thermal contraction and maintains good resonant frequency (19 Hz)
- Titanium hexapod design has the highest resonant frequency of focal plane supports (144 Hz)

### G10 Supports (all of these mode shapes are in flexure)
| Strut Shape | Base Frequency (Hz) |
|:------:|:-------------:|
| Tab | 6.8 |
| Bipod | 16.6 |
| Cylinder | 20.3 |

### Titanium Supports (all of these mode shapes are in flexure)
| Strut Shape | Base Frequency (Hz) |
|:------:|:-------------:|
| Triangular | 72 |
| "X" | 96 |
| Hexapod | 144 |
| Truss | 89 |
| Hexapod (carbon fiber) | 82 |


## Files:
- Finite Element Analyses: /analysis_docs/
- Final Design Renders: /final_subassembly_renders/
