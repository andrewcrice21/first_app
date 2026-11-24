# Beam Designer Validation Cases

Run each case with the listed inputs after selecting the matching support type.
For all steel cases use E = 29000 ksi and W12x26 properties Sx = 33.4 in³,
I = 204 in⁴. Compare expected scalar values within 0.1%.

| Case | Inputs | Expected results |
|---|---|---|
| Simply supported uniform load | 20 ft; simply supported; W12x26; 1 kip/ft | R = 10 kip each; Mmax = 50.0 kip-ft at 10 ft; ymax = 0.609 in; bending PASS; deflection PASS |
| No load | 10 ft; simply supported; W12x26; no loads | R = 0 kip each; Vmax = 0 kip; Mmax = 0 kip-ft; ymax = 0 in; both PASS |
| Cantilever point load | 10 ft; cantilever; W12x26; 1 kip down at free end | Reaction = 1 kip; fixed moment = 10 kip-ft; Mmax = 10 kip-ft at fixed end; ymax ≈ 0.097 in at free end |
| Cantilever uniform load | 10 ft; cantilever; W12x26; 1 kip/ft | Reaction = 10 kip; fixed moment = 50 kip-ft; Mmax = 50 kip-ft at fixed end; ymax ≈ 0.364 in at free end |
| Combined downward point loads | 10 ft; simply supported; 5 kip down at 3 ft; 5 kip down at 7 ft; 0.5 kip/ft | R = 7.5 kip each; Mmax = 21.25 kip-ft near midspan |
| Upward point load | 10 ft; simply supported; 5 kip up at 5 ft | R = 2.5 kip downward each; Mmax = 25 kip-ft at 5 ft |
| Failing bending | 20 ft; simply supported; W12x26; 10 kip/ft | R = 100 kip each; Mmax = 500 kip-ft; fb,max ≈ 179.64 ksi; bending FAIL |
| Failing deflection | 20 ft; simply supported; W12x26; 15 kip/ft | ymax ≈ 9.09 in; limit = 8.0 in; deflection FAIL |
