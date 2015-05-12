## Implementation

Once a government has assessed their capabilities to launch and sustain an open data initiative, the technical details of implementation are left to be detailed. They can be divided into two categories regarding a government’s technical ecosystem and their data management and procedures. 

### Technical Ecosystem and Skills 

A city’s technical ecosystem refers to their current available infrastructure and data sources. Skills refer to the city’s personnel and their capacity to implement a usable and effective open data site. These particular technical considerations are mostly specific to the ArcGIS Platform and consider what is necessary and what is possible when establishing an ArcGIS Open Data site. 

**ArcGIS Platform**

ArcGIS Open Data is a capability of ArcGIS Online, where ArcGIS Online organizations can enable open data and create their own site for free. Governments can use ArcGIS Open Data to easily provide their users with a consistent experience to access, discover, explore, and download their authoritative data. Administrators can host their data on ArcGIS for Server, on ArcGIS Online, or elsewhere. 

If a city has an ArcGIS Online subscription already, they are ready to start publishing their data. Administrators wishing to house their data on their own server must have ArcGIS for Server 10.x — the more recent, the better. Data from Server must be registered in ArcGIS Online and organized in open data groups to be added to an open data site. 

**Multiple Sources**

An ArcGIS Open Data site can contain data from multiple sources and APIs and present it in a consistent interface. Administrators can use [Koop](https://github.com/esri/koop) to pull in data from multiple sources, such as CKAN and Socrata. Koop will transform your data into a feature service, which can then be included in an ArcGIS Open Data site and is available in multiple open formats. 

If a government would like to pull in data from outside the platform, they must deploy their own instance of Koop. 

**Multiple Services**

Many different types of data can be shared in ArcGIS Open Data: map services, feature services, image services, and more. ArcGIS for Server has a common API across all these services, and Koop provides an option to bring other data into the ecosystem. Users can access all different kinds of data through the same interface and can download them all in the same open formats, regardless of the data type upon upload or registering. 

**Design**

Designers are free to fully customize their homepage with their own HTML and CSS. This allows sites to be fully branded to an organization to meet any necessary design guidelines. However, having an dedicated experienced designer is not needed to establish an authoritative site — administrators can use the WYSIWIG editor to drag and drop text and image widgets to configure the homepage.

Designing the homepage may take some time to reach a consistent web experience across governmental sites and their open data site. It is important to create an authoritative site that guides users to find the data they are looking for. 

### Data Management, Procedures, and Availability 

There are several ways governments can organize their departments and employees to optimize workflows for publishing open data. Cities can have federated sites with data from multiple departments, and can control how personnel publish data through user roles. When doing so, it’s important to control for data quality and to ensure that the most impactful datasets are made available to the user community. 

**Departmental Federation and User Roles**

A government with an ArcGIS Online subscription can create as many ArcGIS Open Data sites as they’d like — there can be one central site, as well as individual sites for different departments, themes, or special events. Departments can manage their own data on their own site, and data can be federated from these groups into a common site. Establishing a workflow of staging groups and staging sites can help ensure quality assurance of the data. 

Employees within an organization can have different user roles and different access to certain groups. This can help in a federated workflow where everyone across all departments can submit data to staging group that is not open data enabled. A select few open data admins can monitor this group to ensure the datasets are ready for publication: they have complete metadata, properly sanitized, etc. Once approved, open data admins can add that dataset to an open data-enabled group to add to the ArcGIS Open Data site. 

**Quality Datasets**

Ensuring high quality data is crucial when curating data for publication — data should go through a quality assurance process so users get access to the best data possible. This process is part of the policies and workflows for data publication established within a city and should account for complete titles, descriptions, licensing, and other appropriate metadata. 

Lots of data is coming from the GIS department that is optimized for GIS software and used by people with high degrees of knowledge and familiarity with the data. Part of the process is making this data accessible to the end user — including field aliases and attribute descriptions makes the data easier to understand. When possible, it is best to collect and produce data with the intent to publicly distribute. 

**Impactful Datasets**

If publishing data incrementally, the data being initially published should be data that is most useful for the user. Publishing high impact data that is already available within the GIS department is a great way to start and generate utility. Data that sees high use can be determined by the department — may include parcels, crime data, census data, building footprints, and addresses. 

When deciding which datasets to publish, personnel may consider what data is most often requested through FOI — this is likely data that will see a lot of use once they’re open. Personnel should also communicate with their user base to find out what kind of data they are seeking.