# Title ***CEREUS: Cyberinfrastructure for Environmental Research & Education in Unoccupied Systems***

# Proposal Abstract: 

*Include a 200-word abstract of your proposal, ensure that you include: what it is you are proposing and the external funding opportunity(ies) targeted. This information will be copied into a text box in the system. Special characters are discouraged.*

Analyzing "big data" produced by small unoccupied aerial systems (sUAS) is complicated by the requirement of sufficient data storage space for initial data products (imagery and lidar scans), as well as processed data outputs. When coupled with machine learning model training these data sets become the prohibitive on existing university web-based solutions (i.e. Google Drive, Box, etc). We propose to purchase four rack mount data storage servers and one processing server, to be housed within UITS providing an additional 1.X Petabytes (PB). The proposed data management system in combination with our new flagship High Performance Computer (HPC) demonstrate the state commitment to research using sUAS data and machine learning. As a result, we increase our competitiveness in external funding proposals from the following sources: National Science Foundation (NSF), United States Department of Agriculture (USDA) NIFA-FACT, Department of Engery (DOE) ARPA-E, Department of Interior (DOI), and non-governmental organizations and private foundations. Resources are for use by faculty, students, and staff who are currently or planning to collect and process sUAS data and to conduct related geospatial research.

# Keywords/Key phrases: 

drones, small Unmanned Aerial Systems, Data Management System, lidar, Geographic Information Systems (GIS)

# Cover Sheet: 

The following information will be copied into text boxes within the system.

# Project Narrative (2-pages)

*i. Description of the proposed equipment, including added capacity to UA’s existing equipment*

Four rack mount AMD servers configured with XX hard disks totalling XXX TB, one X-core processor, and XX GB RAM per unit. The proposed data storage adds X.X petabytes (PB) of cloud optimized disk space to the UITS campus computing network. Data hosted by the system will exist in the Science DMZ, with high speed networked upload speed to the UITS High Performance Computing (HPC) Cluster. Storage will be shared across campus resources and researchers who have existing HPC accounts and by the UA Library.

One 96-core AMD server with XX TB solid state storage and XXX GB RAM. This server has the same configuration as the new 2020 UA HPC. The processing server will be provisioned for hosting dedicated services -- mastering and monitoring researcher's sUAS processing jobs on the HPC system without preemption. It will also feature an interactive, browser based, virtual desktop for these jobs. This "On Demand" feature already exists on the UA HPC service but is limited  the new feature will allow researchers to launch  teach cloud and distributed computing courses in sUAS image processing and machine learning, which also leverage the UA HPC resource.

UITS currently host XX.X PB of research and public data for the UA research community. These data also include the 3.5 PB CyVerse Data Store. 

The proposed CEREUS storage and processing servers provide three unmet needs: (1) they increases the available 'scratch' space for researchers who work with large quantities of sUAS data, (2) they provide a modern data processing service for UA researchers to link with existing historical geospatial data hosted by the UA Library, (3) offer support for educational programs working with sUAS and distributed computing on cloud and HPC. UA HPC data storage are temporary, and allow researchers to stage data on the HPC system for a short period of time (<100 days). The UA HPC has a limit of 1 TB per user on their scratch system. For new science projects, such as those using machine learning, high throughput phenotyping in precision agriculture, and sUAS data processing for point cloud and 3D modelling efforts, the available scratch space is too small.

The additional storage space provided by CEREUS is intended for (a) holding new data collected by researchers working with sUAS and (b) for holding associated datasets which are used in data fusion procedures (i.e. aerial lidar, terrestrial lidar, aerial orthophotography, and earth observing system (EOS) satellite imagery) machine learning, analyses. 

Currently, there are multiple sUAS groups currently active at the University which include: the Arizona Experiment Station at Yuma Ag Center, Maricopa Ag Center, Santa Rita Experimental Range, and Walnut Gulch Experimental Watershed. Data include visible light (Red Green Blue [RGB]), multi-spectral (Near-InfraRed [NIR]), hyperspectral, and far infrared (heat).

Existing lidar data from 2005-2019 for the state of Arizona exceed 20 TB of original data. These data are hosted in part by the Library, but they are not accessible by researchers who are interested in working with them on the UA HPC system or on the CyVerse infrastructure, which is hosted by UA. State level lidar data are expected to become available in the next two years as the United State Geological Survey's 3D Elevation Program (3DEP) completes its contracting work 

Data storage servers within the UITS HPC center for hosting GIS data collected by remote sensing platforms. The Arizona Geographic Information Council (AGIC) are in the preliminary phase of setting up a geospatial data clearing house for hosting state level GIS databases, historical imagery, and state level lidar data through the AZGEO Clearinghouse.

*ii. Relationship to other existing core facilities or shared equipment resources*

UITS HPC center offers 1 TB of free scratch storage per user on their system. This is enough for small projects, and for uploading -> processing -> transfering -> deleting of larger datasets. 

Currently, there is no hosted storage available for researcher generated data, such as those from sUAS working in landscape dynamics and ecology, rangeland management, or precision agriculture.

CyVerse is a national resource, available to NSF funded researchers and only offers 100 GB of storage to registered users. While our proposed system will be federated with the CyVerse data store, it will be reserved for UA staff and researchers. By federating the storage using the iRODS system, users will be able to move their large data stored on our servers to the CyVerse cloud and data science work bench for large, distributed computation.  

*iii. Description of how the equipment will be operated and maintained*

Servers will be maintained within UITS, by UITS staff under direction of co-PI Joyce. Data management Systems deployed on the hardware will be maintained by PI Swetnam and UITS staff. Training, documentation, and user support will under the direction of PI Swetnam, co-PI LeBauer, and by co-PI Carini. 

A hybrid cyberinfrastructure data management system which is operated within the UITS, researchers and instructors will be able to utilize the new HPC (available Q1 2020) for sUAS processing, airborne lidar analyses, gantrybased phenotyping, remotely sensed data analysis, machine learning, and 3D model creation. The service will be available to students (via online lessons leveraging web-based applications); graduate students and postdocs for research; and to faculty and staff for teaching, research, and proposal development. Container orchestration software will allow for additional dedicated storage, compute, or GPU nodes to be added to **CEREUS** in the future, or alternately for short-term hardware additions to balance computational loads to match demand, e.g. UA HPC, or CyVerse cloud. Data storage will be federated with CyVerse, as well as UA Libraries and UITS HPC. The machines will be deployed using Linux OS, Kubernetes, CyVerse SDK software, and container technology which will allow users to interface with common integrated development environments (i.e. Project Jupyter, RStudio-Server).

*iv. Identification and justification of at least one extramural funding opportunity. Give the grant/program title, funder name, submission deadline, and funders’ priorities.*

National Science Foundation research announcements which may be targed by the 

| Funding Agency | Program Title | Submission Deadline | Funder's Priorities |
|----------------|---------------|---------------------|---------------------|
| National Science Foundation | Harnessing the Data Revolution | | |
| National Science Foundation | | | |
| National Science Foundation | | | |
| National Science Foundation | | | |
| National Science Foundation | | | |
| United States Department of Agriculture | NIFA FACT | | precision agriculture |
| United States Department of Agriculture | Agricultural Research Service | | |
| United States Department of Agriculture | Forest Service | | |
| United States Department of Interior | National Park Service | | |
| United States Department of Interior | United States Geological Survey | | survey, landscape change |
| United States Department of Energy | ARPA-E | | biofuels, |
| National Oceans & Atmospheric Administration | | | | |
| United States Department of Defense |  | | |
| The Nature Conservancy | | | Landscape ecology, monitoring, restoration |
| Gordon and Betty Moore | | | |
| Zuckerberg Chan Foundation | | | |
| Sloan Foundation | | | |
| | | | |
| | | | |


# References Cited (1 page)

b. Supplemental Documents:
i. Table of users with their departmental and college affiliation; a minimum of three users is
required.

| Name | Title | Department | College | Research Application(s) |
|------|-------|------------|---------|-------------------------|
| David LeBauer | Director Data Science | AES | CALS | Precision Agriculture |
| Mitchel McClaran | Director AES | SNRE | CALS | Rangeland Management |
| Thomas Meixner | Director HAS | HAS | College of Science | Green Infrastructure | 
| Greg Baron-Gafford | Associate Professor | Geography | SBS | Landscape Ecology |
| William Kolby Smith | Assistant Professor | SNRE | CALS | Carbon Dynamics |  
| Wim van Leeuwen | Professor | SNRE | CALS | Remote Sensing |
| Jeffrey Gillan | PostDoctoral Researcher | SNRE | CALS | Rangeland Ecology | 
| Guillermo Ponce| PostDoctoral Researcher | SNRE | CALS | Rangeland Ecology | 
| Kiri Carini | | Library | |
| Kamel Didan | | | | 
| Paul Bremmer | ? | Yuma Ag Center | AES | Precision Agriculture |
| Rosa ?? | | | | | 
| Alison Thompson | Adjunct Professor | USDA-ARS, 
| Duke Pauli | Assistant Professor | Plant Sciencs | CALS | Precision Agriculture |
| | | | | |
| | | | | |
| | | | | |
| | | | | |


*ii. One-page business plan for the long-term sustainability of the equipment; note that awardees placing the equipment within UA core facilities will be expected to work with RII staff to establish internal and external usage rates.*

Equipment are insured by their vendor for the first XX months. The cost per TB of data decreases by approximately ## % every ## months. After the servers have gone beyond their service life they will be replaced by new servers

A user fee structure will be placed for data that researchers Cost per TB of data added to the system will be billed to UITS at a rate of $10 / TB / Month for the first three years of the project. 

The initial CEREUS data service will be configured to allow horizonontal scalability. Horizontal scalability means additional rack mounted servers can be added to the platform, and existing servers upgraded or replaced as time goes on. 

Future research proposals which plan to use CEREUS will need to provide in-kind support for the data storage on the system. Researchers who wish to publish their data sets will have the option to move their data to archival storage platforms hosted either by UA Library, CyVerse, or commercial cloud data providers (i.e. Amazon Web Services, Google Cloud Platform, Microsoft Azure)

One potential revenue resource is the Arizona State Cartographer's office 

Data storage will be federated with CyVerse and UA Library 

*iii. If the proposed equipment is being placed in a core facility, a letter of commitment from the facility manager is required. In addition, UA's Core Business Office must provide a letter indicating support of the proposed budget and business plan.*

*iv. A valid vendor quote, good through April 30, 2020, must be submitted.*

*2. Budget: EEF budgets must only be used for equipment or related equipment expenses.* 

No Internal Submission Deadline:
Wednesday, December 11, 2019
ADD TO CALENDAR
Administrator(s): Research Development Services (Owner)
Category: 3: Equipment Grants
Award Cycle: FY2020
