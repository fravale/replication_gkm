# replication_gkm

Replication Package of "Kernel-based Time-Varying IV estimation:handle with care"
by Riccardo (Jack) Lucchetti and Francesco Valentini.

Software Requirements:
- gretl 2022c or later (http://gretl.sourceforge.net/)
- "ketvals" package can be installed by "File/Function packages/On server.../ketvals" (version 0.93 or above)

Folders:

application_figures_and_table1/  --> Figures and Table 1 replication

simulations/  --> simulations replication




Scripts:

application_figures_and_table1/lucchetti_valentini_replication_figures.inp --> this file generates the figures included in the manuscript.
NOTE: user must select the Figure number at the beginning of the script.

application_figures_and_table1/lucchetti_valentini_replication_figures_extra.inp --> extras for the previous script
NOTE: do not run separately.

application_figures_and_table1/comparison_sim.inp --> replicates Figure F3
NOTE: do not run separately.

application_figures_and_table1/comparison_pc.inp --> replicates Figure F4
NOTE: do not run separately.

application_figures_and_table1/lucchetti_valentini_replication_table1.inp --> replicates Table 1

simulations/tv-iv-simula_hausman_r_less_than_p.inp --> it replicates Table B1.

simulations/tv-iv-simula_paper.inp --> it replicates Tables from C2 to C7.

simulations/tv-iv-simula_hausman_paper.inp --> it replicates Table C8.

simulations/tv-iv-simula_global_hausman_paper.inp --> it replicates Table C9.
