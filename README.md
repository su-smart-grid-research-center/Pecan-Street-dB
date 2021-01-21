# Pecan-Street-dB
## Overview
Pecan Street is a non-profit research organization located in Austin, Texas. The organization was cultivated as a result of an NSF grant, setup by faculty from UT Austin. The mission of Pecan Street is: "Pecan Street's mission is to accelerate the transition to clean, low-carbon energy and integrated water management through innovative technology and policy. Our research, data, and technology expertise give researchers, entrepreneurs, policymakers, and impact investors the insight they need to change the world." Pecan Street has single and multi family homes in Texas, New York and some other locations in the US. These houses have been built and maintained to enable the collection of granular electricity consumtion, production and distribution within each house. More information can be found here: https://www.pecanstreet.org/

## Database @ SU
The Smart Grid Research Center has a limited license for the academic and research use of electricity usage data. This data is stored in a database.

### Data management
The data portal provided by Pecan Street provides access to limited views of various data sets: https://www.pecanstreet.org/dataport/. The SU Smart Grid Research Center has an established relationship with Pecan Street. The data from multiple locations has historically been sent to the university through the mail and then uploaded to the university's local dB instance. For more on this please see the subsequent sections.

#### 1. Data Pre-upload process
Before fetching the data, get access to the SU shared G:\ drive. Specifically, access may need to be granted to both G:\IST\SGRC and G:\IST-Filer\research-data\Datasets\Pecan Street. Upon retrieval of the Pecan Street data, stored on a drive, the data must be de-compressed and sent to G:\IST-Filer\research-data\Datasets\Pecan Street\PecanStreetFlashDriveData\Decompressed, and it's a good idea to store the compressed files in G:\IST-Filer\research-data\Datasets\Pecan Street\PecanStreetFlashDriveData\Compressed. The data is compressed in the g-zip format and can be extracted using an application such as 7-zip, which is usually pre-installed on SU lab computers.
#### 2. Data upload process
After extracting the compressed files onto an SU Lab VM or other machine that has Microsoft SQL Server Management Studio. Access to the PecanStreet instance will need to be granted. A sign-on can be created by someone with master access, the process for which can be found in this repo. Alternatively, a message requesting access from student or faculty to ischoolit@ot.syr.edu should work if all else fails. For uploading a file, please see the documentation in this repo.
#### 3. Data management
There are plenty of ways to retrieve the data from the database, either exported as a flat file, as a sql/grid object file, or read in through a direct connection to the database. Please see some of the .sql query files or .ipynb files to see different approaches and please see some of the different guides for exporting data.

### Projects
Please view miscellaneous repos which belong to https://github.com/su-smart-grid-research-center/ or https://github.com/Pecan-Street to see some other examples of managing and/or exploring the data.

## Help
### For assistance, email, message, etc.:
#### For SU SGRC git org management: pjpriole@syr.edu, https://github.com/pjsandwich
#### For Pecan Street data: smock@pecanstreet.org, dataport@pecanstreet.org, https://www.pecanstreet.org/dataport/, https://github.com/Pecan-Street, https://github.com/SMock123
#### For SU Pecan Street dB: ischoolit@ot.syr.edu, radresch@syr.edu
