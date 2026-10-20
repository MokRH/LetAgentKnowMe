# Research code (GitHub: https://github.com/MokRH)

## Linked from the CV
1. Metaheuristic-AVR (MATLAB): fractional-order PID tuning of an AVR system with SFA, MSFA, NLSFA, CMSFA. Accompanies paper 3 (MSFA).
2. Metaheuristic-BenchmarkFunction (MATLAB): MSFA and CMSFA compared with the Whale Optimization Algorithm on the 23 standard benchmark functions.

## Removed
- Metaheuristic-SystemID (Hammerstein identification, paper 4) is no longer available and was removed from the CV.

## Known issues to fix before relying on these links
- Both READMEs read like hand-off notes ("uploaded" files, second person). Rewrite as neutral documentation.
- AVR README says the uploaded SFA and NLSFA originals never improved the cost. Be ready to state which scripts produced the published numbers, and whether the current code reproduces them.
- AVR: SigmoidTest.m needs a Simulink model that is not included.
- BenchmarkFunction: README describes folders (algorithms/, benchmark/, results/) that do not match the flat file list; quick-start addpath lines break.
- BenchmarkFunction: MSFA/CMSFA compare absolute values, which is wrong for functions with a negative minimum (F8, F16, F19 to F23). Use J < Jbar and re-run.
- BenchmarkFunction: unequal budgets (601 evaluations vs 201 for WOA), WOA run with a single agent, bounds handled differently. No results table. Do not claim superiority over WOA until fixed (30+ runs, equal budgets, mean/SD/best/worst, Wilcoxon test).
- Both: no repository description, topics or licence confirmed.
- Profile: unpin and hide CH341-driver and HTTP-file-server (they only hold third-party executables). Pin the two research repositories.
