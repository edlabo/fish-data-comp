# About fish-data-comp
Documents and processes for collating and comparing fish data fields across StreamNet/PSMFC data systems. Pre-identified potential fields with overlap includes: species, hatchery fish stock, wild/natural origin population name, hatchery facility name, location, age

# Contents
- /_crosswalks_/ contains CSV files for data fields and codes cross-walked between the 4 data systems listed under /_data-sys-docs_/
	- _fish-data-xwalk-fields.csv_ contains cross-walked fields from the 4 data systems for species, run, and rearing
	- _fish-data-xwalk-rear-codes.csv_ contains cross-walked rearing codes from the 4 data systems
	- _fish-data-xwalk-run-codes.csv_ contains cross-walked run codes from the 4 data systems
	- _fish-data-xwalk-species-codes.csv_ contains cross-walked species codes from the 4 data systems

- /_data-sys-docs_/ contains all documentation obtained from following data systems (including data exchange standards and content standards):
  - CAP-HLI: [CAP Fish HLIs (CAX)](https://www.streamnet.org/home/data-maps/fish-hlis/)
  - FMD: [Fish Monitoring Data](https://www.streamnet.org/home/data-maps/fish-data/)
  - PTAGIS: [Columbia Basin PIT Tag Information System](https://www.ptagis.org/)
  - RMIS: [Regional Mark Procesing Center](https://www.rmpc.org/data-selection/rmis-queries/)
  
- /_example-comp_/ contains an example of collated fields and codes for the 4 data systems above for species, run, and rearing type data.
	- _fish-data-comp-hatchery-codes.xlsx_ contains hatchery codes from all 4 data systems (this is incomplete; see notes column in the file)
	- _fish-data-comp-hatchery-fields.xlsx_ contains hatchery fields from all 4 data systems
	- _fish-data-comp-species-fields.xlsx_ contains species, run and rear fields from all 4 data systems
	- _fish-data-comp-species-codes.xlsx_ contains species, run and rear codes from all 4 data systems

- /_output_/ contains output files generated by the Python script (below)

- /_scripts_/ contains Python script used to combine PTAGIS validation codes from multiple Excel files into one CSV. This script should not need to be re-run but is included for process documentation.

- /_templates_/ contains template .xlsx files to copy and fill in for collating and comparing fields/codes and template .csv files to fill in for cross-walking fields/codes between data systems