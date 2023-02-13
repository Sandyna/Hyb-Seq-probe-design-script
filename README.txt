This script was created for further adjustments of probes created by the Sondovac script (https://github.com/V-Z/sondovac/)
The outputs of Sondovač were aligned with LAST to prioritize sequences that are present in both genera. 
This script (the Probe Picker) uses a list of all possible probes as input, a list of probes we want in the result no matter what (if available), a list of probes we do not want in the result no matter what (if available), 
a target number of base pairs we're trying to get in the end and a threshold after which it should change approach from taking the probes in order of length to trying to hit the target number of base pairs as close as possible without 
exceeding it. 
The scrip keep_and_remove_probes_picker.py is to help with creating lists of probes to keep or to remove from the result no matter what. 
These scripts were developed as a part of a bachelor's thesis (https://github.com/Sandyna/bachelor_thesis) and v1.0 is as it was submitted to the thesis. 
