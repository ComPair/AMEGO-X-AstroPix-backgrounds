# AMEGO-X-AstroPix-backgrounds
.tra files for AMEGO-X background simulations

1 hour of space simulations, AMEGO-X configuration with AstroPix tracker (250 μm pixel size).

The `main` branch has been updated to use **realistic** readout settings: Only hits above the trigger threshold are read out. 

If you would like to access the older simulations where we assumed that the entire instrument would be read out if the trigger conditions are met, check out the tag `optimistic_readout`. The (prompt) **trapped hadronic** and **trapped leptonic** background files are retained there only for historical reasons. These two components contribute mainly during the SAA passage when the detector is expected to be off, and thus **do not contribute to the overall background rates**. They are simulated because they do contribute to the **activation** background. They have been removed from the summary file `TotalBackground.tra.gz`. 
