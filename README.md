# Wasp_acidification
version of WASP with an AMP algorithm that includes an acidification target. 

For details of the entire model see: Goodwin P (2016) How historic simulation–observation discrepancy affects future warming projections in a very large model ensemble. Clim Dyn 47:2219–2233. https://doi.org/10.1007/s00382-015-2960-z

To set targets, find where Target1 and Target2 are defined and change accordingly

To set strict/lenient/weighted/temp only/pH only, find Multiple_Targets_option and change according to the commented out description above. 

To set the weighting of pH versus warming pathways (for a weighted scenario), find the variables pH_weight and temp_weight and change accordingly (these should add up to 1)
