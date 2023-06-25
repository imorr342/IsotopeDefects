# IsotopeDefects
Data files for the manuscript:
https://doi.org/10.48550/arXiv.2305.05781

'Ef_Diff_Configurations':

This folder contains the VASP OUTCAR files for the neutral charge formation energy calculations done for both Pa and Pr defects in different configurations. This includes calculations for substitutional as well as vacancy containing (1 to 4) defect configurations. Additionally, reference calculations for pristine diamond are also here. Lastly, the OUTCAR files are named according to the defect type and functional used. 

'Ef_Charged': 

This folder contains the VASP OUTCAR files for the charged formation energy calculations done for PaV2 and PrV2. It also includes the pristine folder for reference. In contrast to the 'Ef_Diff_Configurations' folder, these calculations were only carried out using one functional, HSE06, so the OUTCAR files are just named based on which charge state they're for. 

'ZPL': 

This folder contains the ground and excited states for the optical transitions of interest. The ZPL was calculated by taking the difference between the total energy for the ground and excited states. Within the two subfolders, the files are the OUTCAR files for the energy calculations. These were done with the HSE06 functional and are labeled according to the defect (either PaV2 or PrV2) and the charge state (neg2 = -2 and neg1 = -1 charge state, respectively). Additionally, the excited states are also labeled with the spin channel and how many bands higher the highest occupied spin of said channel moves up. For example, 'down2' refers to the highest occupied spin down electron moving up 2 bands. Similarly, 'up1' corresponds to the highest occupied spin up moving up 1 band.  

'E_field':

This folder contains the OUTCAR files for PBE energy calculations when an external electric field is applied for both the -1 and -2 charge states of PaV2. This is what was used to calculate the estimate for the internal effective electric field. In particular, the ZPL was calculated at various levels of electric field strength, then the difference was taken for each with the ZPL at zero field. The difference in ZPL was then plotted and fitted to get the values reported in the manuscript. 

Remaining files not in any folder: 

These are the OUTCAR files which contain the hyperfine, electric field gradient, and zero field splitting tensor parameters. They are variously labeled for which defect (PrV2 or PaV2) and which charge state (neg1 or neg2) they refer to. Additionally, the hyperfine label means they contain the hyperfine and electric field gradient tensors while the ZFS label mean they contain the zero field splitting tensor parameters.  
