**Implementation**

**Technical ecosystem and skills**
* **ArcGIS Platform**: organizations that have an ArcGIS Online subscription already have access to ArcGIS Open Data to provide their users with a consistent experience to access, discover, explore, and download authoritative government data. Administrators wishing to house their data on their own server must have a supported version of ArcGIS for Server.
* **Multiple sources**: an open data site can contain data from multiple sources and APIs. Administrators can use [Koop](https://github.com/esri/koop) to pull in data from multiple sources. 
* **Multiple services**: many different types of data can be shared: map services, feature services, image services, and more. ArcGIS Server has a common API across all these services, and Koop provides an option to bring other data into the ecosystem
* **Design**: Users can have a consistent web experience across governmental sites and their open data site. However, having an experienced designer is not needed to establish an authoritative site. 

**Data management, procedures, and availability**
* **Departmental federation**: a government can have as many sites as they'd like. Departments can manage their own data and have their own site, and data can be federate from these groups into a common site. Establishing a workflow of staging groups and staging sites can help ensure quality assurance of the data. 
* **User roles**: employees within the organization can have different user roles and different access to certain groups. This can help in a federated workflow when everyone can submit data to staging, and a select few verify data quality before publishing.
* **Impactful datasets**: publishing high impact data that is already available is a great way to start: parcels, crime, census, building footprints, addresses 
* **Quality datasets**: ensure the data is high quality, complete with appropriate metadata and licensing 
