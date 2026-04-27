# Data Description
There are three different datasets I am using to address the feasibility of an index insur-
ance product before looking at efficacy:
• The historical crab fisheries closures for California spreadsheet. It contains vital
closure information such as the impacted species, reason for closure, and the coun-
ties affected with latitude measurements. Data is collected based on closure events
executed by the California Department of Public Health. This dataset will be used
in our exploratory data analysis phase where we will overlay fishery management
zones with the crab closure data.
• The California Department of Public Health’s data on domoic acid levels in Dun-
geness Crab sampled from collection sites along the coast. They sample individual
Dungeness Crab viscera and check if parts per million (ppm) for domoic acid lev-
els exceeds FDA action level at greater than 30 ppm. Data is collected weekly at
different collection sites with five sets of individual sample results per site. They
also include what percentage of the samples exceed the action level for ppm. This
data is valuable with the historical fishery closure data because we can establish
thresholds for when financial losses are likely to occur based on domoic acid levels
in crab viscera collected at the time and location of a closure.
• The C-HARM historical forecast data. This is modeled data based on remote
sensing, observational, and bloom probability data. The variables include latitude,
longitude, the probability of the algae genus Pseudo-nitzschia exceeding 10,000
cells/L, the probability of domoic acid exceeding 10 picograms/cell, chlorophyll-a
concentration estimates, and water reflectance at 555 nm and 488 nm wavelengths.
This probabilistic data is valuable for our parametric insurance indices because we
need to aggregate pseudo-abundance and toxins over a specific geographic region
to better establish a predictable risk model for parametric insurance.
# Roles and Responsibilities
I am responsible for data acquisition and formatting, data analysis, access control, and project preservation. 
My professor will oversee my project as the primary funder, and thus will be responsible for
the quality control side of the project as I provide project updates and receive feedback
for improvements. Labmate A is a point of contact for questions regarding data analysis
and data organization. 
# Data Standards and Metadata
My work belongs to my professor’s lab, and thus any
new data analysis or research developments will in essence belong to Oregon State
University. I have no other formal data management requirements due to the nature of my
data being open source with a free-use license.
# Storage and Security
Current data is stored on OSU CEOAS servers.
# Access and Data Sharing
Data analysis will only be available for my professor's lab and the aforementioned CEOAS server. Data used for the project
are operated under a free use license. 
# Archiving and Preservation
There should be three copies in different locations. Namely, the R script for pulling data from the NOAA Coastwatch ERDDAP servers should be downloaded on the CEOAS server under a different sub-folder, in addition to a folder on my personal laptop and ideally a USB
flash drive. The backup process would have to be updated manually, as there is no
accessible automation method for transferring the file on my personal laptop to the CEOAS
server and the USB drive instantaneously without user interference. For this project I am
using RStudio for the production of R code, and execution is completed on the terminal
for the CEOAS server using Command Line. All saves and transfer of files is also
completed with these programs. For a USB flash drive, I’d be operating within the
Windows File Explorer for file update and transfer. The CEOAS as a shared network drive is
backed up, and is probably the safest place for the data to reside. We are currently not
using a cloud system for the data, and we have no plans to use a cloud system with the
contingency plan in place.

