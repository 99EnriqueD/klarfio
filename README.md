# klarflio
Minimalist python library to read and write Klarf v1.8 files. <br/>
This module is a pure python module, there are no dependencies.<br/>
The idea is that once the data is loaded, you can copy the defects data into a numpy array or a pandas dataframe.<br/>

The data of the klarf file is held in a nested dictionnary that follows closely the structure of the klarf file itself.

I plan on adding a few helper functions to simplify the access to the defect data.

Note : This code is based on the one klarf v1.8 I had on hand. I don't have more files to test with.
