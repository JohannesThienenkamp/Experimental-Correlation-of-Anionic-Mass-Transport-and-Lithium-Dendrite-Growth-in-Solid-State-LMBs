# Experimental-Correlation-of-Anionic-Mass-Transport-and-Lithium-Dendrite-Growth-in-Solid-State-LMBs
MATLab script to calculate anion drift velocities from 19F MRI profiles in LMBs

How to use the MATLab Code - Step-by-Step

- open MATLab Version R2021a
- open either MATLab script "Anion_Masstransport_protocol_Li_Li.m" in folder "Li_Li" or MATLab script "Anion_Masstransport_protocol_NMC622_Li.m" in folder "NMC622_Li"

Please note, that only for convenience reasons two individual MATLab scripts exist. Only the required Input Parameter "Enter number of Experiments" within the scripts which refers to the amount o acquired MRI spectra and thus to the total experimental time is different. As mentioned in the manuscript, the total experimental time was longer in case o NM622||Li since Sand's time has been reached later than in case of Li||Li. The required input parameter "Enter number of Experiments" is given for each data set in the individual MATLab script. Thus, please use MATLab script "Anion_Masstransport_protocol_Li_Li.m" only for data set "Li_Li" and "Anion_Masstransport_protocol_NMC622_Li.m"only for data set "NMC622_Li".

- run MATLab script "Anion_Masstransport_protocol_X.m". The X indicates the respective case.
- Select "Change Folder" as soon as an error message appears indicating that script "Anion_Masstransport_protocol_X.m" is not found in the current folder
- An "Input" prompt with given input paramaters specific for each data set appears. Please confirm the parameters by clicking on "ok".
- A second prompt appears: Navigate to the specific data folder and open the folder "Data" (don't be confused if the folder appears empty in the prompt. Proceed). Close the prompt by clicking on "Choose Folder".
- The data input prompt will be closed and the calculation starts as indicated by computed numbers in the "Command Window" of MATLab.
- Finally, the published "Anion Drift Velocity" Figure (part of Figure 3 of the manuscript) and a "Concentration Profile" Figure appear.

Thank you for using the MATLab code.

Johannes Helmut Thienenkamp

