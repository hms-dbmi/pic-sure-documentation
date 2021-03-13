# pic-sure-documentation
## PIC-SURE
**The PIC-SURE v2 API is a meta-api used to host any number of resources exposed through a unified set of generalized operations. The following document explains how to get started with PIC-SURE and the common endpoints you can use to query any resource registered with PIC-SURE.**  
PIC-SURE Repos:
- [PIC-SURE API](https://github.com/hms-dbmi/pic-sure): This is the repository for version 2+ of the PIC-SURE API.
- [PIC-SURE Wiki](https://github.com/hms-dbmi/pic-sure/wiki): This is the wiki page for version 2+ of the PIC-SURE API.
- [Biodatacatalyst PIC-SURE](https://github.com/hms-dbmi/biodatacatalyst-pic-sure): This is the repository for the biodatacatalyst environment of PIC-SURE.
- [PIC-SURE-ALL-IN-ONE](https://github.com/hms-dbmi/pic-sure-all-in-one): This is the repository for PIC-SURE-ALL-IN-ONE. 

<br>
Additional PIC-SURE Links: </br>

- [PIC-SURE v2 API Reference Document](https://docs.google.com/document/d/176CWrIoozihbng1A7Y9nSjhcen-ILFlO3rNRg73V_G8/edit?usp=sharing): This google document contains important reference information about the PIC-SURE v2 API.

- [PIC-SURE FENCE Integration Document](https://docs.google.com/document/d/1fZfx5sgZCfd-2KP3_W60xfCRJaQjgmvKbEQiu-zNHqc/edit?usp=sharing): This document contains information concerning the Fence authentication and authorization service.

- [DCPPC Presentation on PIC-SURE as a meta-API](https://docs.google.com/presentation/d/1IDdoaV_9Bsy4ANqODiStpOICEGtCyvRQibrvLbInBJ4/edit?usp=sharing)

- [Avillachlab-Jenkins Repository](https://github.com/hms-dbmi/avillachlab-jenkins): A link to the Avillachlab-Jenkins repository.

- [Avillachlab-Jenkins Dev Release Control](https://github.com/hms-dbmi/avillachlab-jenkins-dev-release-control): A repository for Avillachlab-Jenkins development release control.

</br>

## PIC-SURE User Interface
**The PIC-SURE User Interface acts as a visual aid for running normal queries of resources through PIC-SURE.**  

PIC-SURE User Interface Repos:
- [PIC-SURE HPDS UI](https://github.com/hms-dbmi/pic-sure-hpds-ui): The main HPDS UI repository.

Additional PIC-SURE User Interface Links:

[PIC-SURE UI Flow](https://docs.google.com/drawings/d/1RdODBD9ofrweUSbFllEo_0xYaAX0B7RGBf9FcoltnGs/edit?usp=sharing): Links to a google drawing of the PIC-SURE UI flow.

## PIC-SURE Auth Micro-App (PSAMA)

**The PSAMA component of the PIC-SURE ecosystem authorizes and authenticates all actions taken within PIC-SURE.**  

PSAMA Repos:
- [PIC-SURE Auth MicroApp Repository](https://github.com/hms-dbmi/pic-sure-auth-microapp)

Additional PSAMA Links:
- [PSAMA Core Logic](https://github.com/hms-dbmi/pic-sure-auth-microapp/tree/master/pic-sure-auth-services/src/main/java/edu/harvard/hms/dbmi/avillach/auth): This is where the core of the PSAMA application is stored in GitHub

- [Token Introspection Process in PSAMA](https://docs.google.com/document/d/1UPKw8L-TMt4r0eOKSK8j9v0hBGDMp5EtQKjqJhxXsrE/edit?usp=sharing): This google document goes over the details of the token introspection process.


## High Performance Data Store (HPDS)

**HPDS is a datastore designed to work with the PIC-SURE meta-API. It grants researchers fast, dependable access to static datasets and the ability to produce statistics ready dataframes filtered on any variable they choose at any time.**  
HPDS Repos:
- [PIC-SURE HPDS](https://github.com/hms-dbmi/pic-sure-hpds): The main HPDS repository.
- [PIC-SURE HPDS Python Client](https://github.com/hms-dbmi/pic-sure-python-adapter-hpds): Python client library to run queries against a PIC-SURE High Performance Data Store (HPDS) resource.
- [PIC-SURE HPDS R Client](https://github.com/hms-dbmi/pic-sure-r-adapter-hpds): R client library to run queries against a PIC-SURE High Performance Data Store (HPDS) resource.
- [PIC-SURE HPDS UI](https://github.com/hms-dbmi/pic-sure-hpds-ui): The main HPDS UI repository.
- [HPDS Annotation](https://github.com/bch-gnome/hpds_annotation): This repository describes steps to prepare and annotate VCF files for loading into HPDS. </br>
Additional HPDS Links:
- [Loading HPDS Data for PL-Biobank](https://docs.google.com/document/d/1ssrzx__h4EmbHMlwZ9afQvwXxZ9KvNYPx51mqXcFIGw/edit?usp=sharing): Details how to do an ETL of genotype and phenotype data into HPDS.
- [pic-sure-hpds-phenotype-load-example](https://github.com/hms-dbmi/pic-sure-hpds-phenotype-load-example): A HPDS phenotype-load-example.
- [pic-sure-hpds-genotype-load-example](https://github.com/hms-dbmi/pic-sure-hpds-genotype-load-example): An HPDS genotype load example.
- [Access-to-Data-using-PIC-SURE-API](https://github.com/hms-dbmi/Access-to-Data-using-PIC-SURE-API): Provides data access for users of PIC-SURE-All-In-One.

## Client Libraries
The following are the collected client libraries for the entire PIC-SURE project.

- [R Client Library](https://github.com/hms-dbmi/pic-sure-r-client)
- [Python Client Library](https://github.com/hms-dbmi/pic-sure-python-client)

## ETL 
The following are instructions to load data into HPDS. It contains all the scripts necessary to create the new table, generate mapping data, and extract  data for HPDS to load.

- [i2b2 ACT to HPDS](https://github.com/hms-dbmi/i2b2ACTtoHPDS/tree/master/Latest)
