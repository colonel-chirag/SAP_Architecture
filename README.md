# SAP_Architecture
Detailed description and interview question related to SAP (System , application and programming for data pre-processing) architecture .
1. What is SAP?
SAP(System, Application, and Products in Data Processing) is the leading ERP(Enterprise Resource Planning) software package that is useful in efficiently managing the resources of a company. SAP is pronounced as individual letters(S-A-P), not as a word (“SAP”).

SAP combines different departments altogether and collects their data in a unified way to help manage all coordination and workflow. The SAP Software portfolio provides edge-to-edge solutions and covers the majority of business requirements of its clients, whether it is an operational, human resources, financial, or e-commerce concern.

2. What is ERP(Enterprise Resource Planning)?
ERP(Enterprise Resource Planning) is a software or an integrated computer-based system that is effectively used by a business for planning and managing daily activities such as manufacturing, supply chain, financials, services, and other processes. It ensures smooth information flow and manages workflows within different departments in a company or an enterprise. In the beginning, the main purpose of ERP was to plan and manage core business such as production and financial market. Now it is useful in integrating information across the entire organization.
SAP was one of the first companies to provide industry-leading ERP solutions and develop standard software for business solutions purpose. Microsoft Dynamics, JD Edwards, Siebel, PeopleSoft, Baan are other examples of ERP available in the market.
ERP software consists of all core business areas such as production, procurement, finance, marketing, sales, materials management, human resources(HR), etc. The below figure represents the business area covered by ERP.

3. Why does the SAP used for?
SAP helps organizations and companies of all sizes and enables the industries to profitably run their businesses, continuously receiving the modifications, and growing sustainably.
The company will develop SAP software solutions that can be used by larger corporations, mid-sized companies, and also by smaller businesses. Each business process can be mapped and designed with the help of standard applications, platforms, industry solutions, and technologies. The SAP software will collect and process the data on a single platform, data can be related to raw material purchasing, production, customer satisfaction, etc.
SAP solutions can be used from the cloud or can be installed “on-premise” at a user’s place, helping companies for analysing and design the entire value chain efficiently.
In addition, SAP solutions are useful in the creation of forecasts, such as how revenue is going to develop in the next half-year or when a machine needs repairing.
Also, SAP helps customers to link operational data flawlessly on business processes with experimental data on emotional factors like customer feedback or purchase experience. This allows companies to understand and respond to the customers in a better way.

4. What is NetWeaver? what is the advantage of using NetWeaver?
NetWeaver is an integrated technology platform that allows running various products from mySAP suite on a single instance called SAP Web Application Server(SAP WEBAs).

The advantage of NetWeaver usage is you will be able to access SAP data using the web(HTTP protocol) or even from a mobile device. This will save the costs involved in training clients on SAP Client-side GUI.

5. What are Metadata, Master data, and Transaction data?
Meta Data: Meta Data represents data about Data. It provides information about the structure of data, database table objects, etc. For example, ABAP Dictionary will provide information about the data within RDBMS.
Master Data: Master Data is comprised of whatever an organization does and how it is differently defined over business units or competitors. It helps to establish a 360-degree business view.
It consists of key business information such as Customer information, Materials, Employee, etc. This is similar to reference data. For example, if a customer orders 5 units of your product, rather than 5 times asking the customer for shipping address, it can be referenced from the Customer Master Data.
Transaction Data: Transaction data consists of data related to day-to-day transactions. For example, the daily production details related to material, getting of materials, daily transactions, etc.

6. Differentiate between OLAP and Data Mining.
OLAP(Online Analytical Processing)	Data Mining
OLAP is a reporting tool used for understanding the database schema, dimensions, and composition facts(values and attributes).	Data mining is an analytic process that is useful for data analysis for finding out consistent patterns.
It is used to analyze past data.	It is used for future prediction.
It deals with detailed transaction-level data.	It deals with data summary.
A top-down data analysis approach is used where insight is obtained by analyzing the big picture.	A bottom-up data analysis approach is used where insights are obtained by analyzing data.

7. What are pooled tables in SAP?
A pooled table is a special type of table that is present in the SAP ABAP(Advanced Business Application Programming) dictionary that is used to store control data. The pooled table is an SAP proprietary creation. It has a many-to-one relationship with tables within the SAP database. This implies that, for a provided pooled table in the database, the SAP data dictionary can have multiple smaller tables. SAP will make use of pooled tables to integrate and hold a huge number of small tables. This will help in reducing the space and resources required at the database level. SAP will mainly use pooled tables for system data maintenance.

8. What is BEx in SAP?
BEx(Business Explorer) is a tool provided by an SAP SE software company that supports for entry of data in BW(Business Warehouse) Integrated Planning and the creation of planning applications.
BEx permits the end-user to locate reports, execute the query, analyze the information, and view the reports. If an employee has authorization access, he can evaluate current or historical data at different levels of detail and from various perspectives; both on the Web, in Microsoft Excel, and the portal.
BEx has the components like BEx Map, BEx analyzer, and BEx Web. The queries present in the workbook can be saved to their corresponding roles within the BEx browser.
BEx Information Broadcasting will help to distribute the created objects with Business Explorer via e-mail, either as document files with historical data that are previously calculated or as a link with live data. You are allowed to publish this content to the portal (in collaboration rooms or Knowledge Management folders).

9. What is AWB? What are the functions of AWB?
AWB(Administrator Workbench) is a tool useful in controlling, maintaining, and monitoring each and every process that is in link with staging and processing of data in SAP business information warehousing. Also, it can be used to create, modify and customize all types of metadata objects of Business Warehouse.

Administration Workbench(AWB) functions in SAP BW are:

Modeling: It is used for creating and maintaining metadata objects related to the staging and processing of data within SAP Business Warehouse(SAP BW). These objects will be displayed in a tree structure format, in which the objects are ordered based on hierarchical criteria. You can make use of the context menu for accessing the relevant maintenance dialogs for every object in the object tree. You need to choose transaction RSA1 for accessing the Modeling functions area.
Monitoring: It is helpful in monitoring and controlling the process of data loading and additional data process in SAP BW.
Reporting Agent: With the help of this reporting agent tool you will be able to schedule and execute the reporting functions in the background.
Transport Connection: This function area is useful for transferring the newly created or modified objects that are present in BW systems. For example, transporting objects from the development server to the testing server and then to production systems.
Documents: This function area is used for inserting, searching, creating links for one or more documents according to the needed format, languages, and versions for SAP BW objects.
Business Content: It provides preconfigured data models based on metadata. We can say that business content is a collection of SAP-defined objects available in the delivery version.
Translation: You can perform translation of texts for SAP BW objects.
Metadata Repository: In the metadata repository of HTML, SAP BW metadata objects and related links to other objects are centrally managed together with the help of an integrated metadata repository browser.
![Screenshot_2022-06-23_23-26-39](https://user-images.githubusercontent.com/59536110/175368257-09a00d03-5a6e-4587-bf01-ce54e5f520c6.png) 

11. What is SAP R/3?
SAP R/3 is a 3rd generation set of extremely integrated software modules. It is one of the major products in SAP, where R represents RealTime and the number 3 represents three-tier application architecture.
It is an organization-wide information system that is mainly designed for coordinating all the resources, information, and activities required to complete common business processes such as human resource management, billing, order fulfilment, and production planning.
It can be used by any organization however different it is in its operations, or anywhere in the world.
SAP R/3 has three main layers. They are:
Presentation Layer: It consists of the software components that are made of SAPgui(graphical user interface). This layer is responsible for sending the user’s input to the application server, and for receiving the data for display from it.
Application Layer: It consists of single or multiple application servers and a message server. The message server transmits the request from one application server to another application server within the system. Also, it holds application server groups related information and the current load balancing within them. It will make use of this information for assigning a suitable server when a user logs onto the system.
Database Layer: It contains a central database system that has all of the data in the R/3 System. SAP has developed its own database named HANA, but it is compatible with many databases like Oracle.




![SAP_R3_has_three_main_layers](https://user-images.githubusercontent.com/59536110/175364790-89f44c1f-5c2d-4cad-b594-b1c1495f6756.png)

12. What is SAP PI/PO(Process Integration/Process Orchestration)?
SAP PI/PO is a tool that permits you for integrating the solutions from SAP systems to other SAP or non-SAP systems. Using this, data between various systems can be easily synchronized. For example, consider that the SAP ERP system is used by you, and you want to integrate it with the CRM system. It can be done using PI, which allows the user to easily perform the integrations, with the help of a standard tool that permits you to maintain various connections in a single place.
Using SAP PI/PO, synchronizing data to a warehouse system is also possible. For example, consider the case where you wish to send all the orders related information like how they are used, which of them are being produced, and when they need to be shipped.
Work becomes easier and more trouble-free with the help of SAP PI/PO. Because developers and organizations are having a single tool that can be used for various integrations varieties, instead of using multiple divergent tools for smaller tasks.
13. Define LUW(Logical Unit of Work).
An LUW(Logical Unit of Work) is a series of database operations that should be either completely executed(followed by commit) or not at all(followed by rollback).
It helps to guarantee the integrity of the database. The database is said to be in a correct state when an LUW has been successfully concluded. However, if any error occurs within an LUW, all the modifications made to the database from the beginning of the LUW will be canceled and the database will be returned to the previous state as before the LUW started. For example, in financial accounting, while transferring some amount of money, you must deduct that amount from account A and it must be added to account B. Before and after the transfer process, the data must be consistent, but in between these two steps, data can be inconsistent. If the amount transfer by LUW becomes successful, then the amount will be deducted from account A and added into account B. If any error occurs in between database must be returned to its previous state before LUW started.
An LUW will begin:
Each time when you start a transaction.
When the changes made to the database using the previous LUW has been confirmed(database commit).
When the changes made to the database using the previous LUW has been canceled(database rollback).
An LUW will end:
When the changes made to the database has been confirmed(database commit).
When the changes made to the database has been canceled(database rollback).
14. What are variables in SAP?
Variables are query parameters that are set in the definition of parameter query and values will be assigned only after the query has been entered into the workbooks.
There are various types of variables that can be used in different applications. Some commonly used variables are text, formulas, replacement path, user entry/default type, hierarchies, hierarchy nodes, characteristics variable, processing types, etc.
15. What are the two types of services used for dealing with communication in SAP?
The two types of services used to deal with communication:

Gateway Service: This service permits communication between SAP R/3 and external applications using the CPI-C protocol.
Message Service: This service is used by the application servers for exchanging short internal messages.
16. Explain the standard stages of the SAP Payment Run?
The standard stages of SAP on SAP Payment Run execution will include:

Entering of parameters: It will include entering company codes, methods of payments, vendor accounts, etc.
Proposal Scheduling: The system offers a list of invoices to be paid
Payment booking: It includes booking of the actual payment into the ledger
Printing of Payment forms: It includes payment forms printing.
17. What is BDC(Batch Data Communication)? How many methods of BDC are present?
BDC(Batch Data Communication) is used for data transfer from the Non-SAP system to the SAP R/3 system. A huge amount of data can be added into the database of the sap tables instead of manual entry of the data. Use SHDB(transaction code used for transaction recording in SAP) transaction for recording and the cursor movement. This cursor movement is noticeable by the SAP software and according to our excel or flat file, the data will be sent or stored in the proper position.

There are 3 methods you can use for transferring the data. The methods of BDC are:

Batch Input Session Method: This method is mainly used in ABAP programming when no other method exists. The online transaction process is simulated and the data transfer will be done in the way it is done online. A batch input session will be created using SHDB that has all the data and screens and then processed. If you have made any changes to the screen then you need to add these screens to the program, otherwise, the BDC will be failed.
Direct Input Method: In this method, the input file data will be transferred directly to the SAP database. The involvement of screens is not required. This method will make use of function modules to complete the task.
Call Transaction Method: It does asynchronous processing of data and transfers only a small amount of data. Here, data will be automatically updated and it is having faster processing. If you are using this method, errors must be handled explicitly.

![bdc](https://user-images.githubusercontent.com/59536110/175597014-dc313313-60da-42b9-ab13-ba6fb1936395.png)

![Screenshot_2022-06-24_22-09-56](https://user-images.githubusercontent.com/59536110/175599576-f8ebf5be-e9cd-4dbb-9fbd-7559a9870f05.png)

19. Explain the significance of ODS(Operational Data Store) in BIW(Business Warehouse Information).
An ODS(Operational Data Store) Object supports consolidated and debugged transaction data storage on a document level. It defines a combined dataset from single or multiple InfoSources. Analysis of this dataset can be done with an InfoSet Query or BEx Query. We can update the ODS Object data with a delta update into InfoCubes and other ODS Objects that belongs to the same system or across other systems. The data in ODS Objects will be stored in transparent, flat database tables.

20. Explain about SAP services.
Some of the SAP services are:

SAP Application Management Services: It includes development of application, implementation, integration, testing, monitoring, help desk services, maintenance and support(technical and functional), backup and recovery.
SAP Platform Modernization: The modernization approach will convert SAP into a dynamic, agile, and capable digital core ready to fit into frequently changing market conditions and requirements of the customers.
SAP S/4 HANA Migration and Transition Services: Integrated business planning and strategies of digital transition for S/4 HANA migrations will be provided. Our aim is to migrate the useful features while implementing technology that supports the current and future requirements of a business.
SAP S/4 HANA Implementation Services: It allows businesses to fulfill the digital economy-related demands.
SAP Technology Platform & Infrastructure Services: This service will make sure that your ERP platforms are robust and secure, whether it is an existing SAP platform or part of S/4 HANA or cloud migration/implementation.
SAP Interview Questions for Experienced
21. What is code pushdown in SAP?
Code pushdown means transferring data-intense calculations to the database layer. ALL calculations will not be pushed into the database, only required calculations will be considered. For example, if you wish to do the calculation for finding the amount of all positions of invoices, it is not mandatory to select all positions of those invoices and perform the calculation of sum using a loop. By using an aggregation function(SUM()) on the database you can easily do this.

22. What is SAP S/4HANA?
SAP S/4HANA(SAP Business Suite 4 SAP HANA) is an ERP software package based on the SAP HANA(in-memory database) and it permits companies for doing ERP transactions and analyzing the business data in real-time. S/4HANA can be easily used and administered during complex problem solving and handling a huge quantity of data than its predecessors. It is provided in on-premises, cloud and hybrid deployment models along with SAP is forcing its customers for opting the cloud. SAP S/4HANA is used by organizations mainly for integrating and managing business functions like sales, finance, procurement, human resources, service, and manufacturing in real-time.

![Screenshot_2022-06-24_22-14-06](https://user-images.githubusercontent.com/59536110/175603769-403ad860-b205-4dd8-8d86-7c003d0a859f.png)
24. List the different SAP modules.
The different Modules available in SAP are:

FI (Financial Accounting)
CO (Controlling)
EC (Enterprise Controlling)
TR(Treasury)
MM (Materials Management)
PP (Production Planning)
IM (Investment Management)
QM (Quality Management)
EAM (Enterprise Asset Management)
HR (Human Resource)
SD (Sales and Distribution)
BW (Business Warehousing)
Apart from this, there are various other industry-specific solutions provided by the SAP.

25. Explain about SAP portal.
SAP Enterprise Portal(SAP EP) provides users with web-based, role-specific, and also provides secure access to all the services, information, and applications in SAP environments. Employees require only a desktop and a Web Browser, and can start with work immediately after authentication in the portal has been completed. It contains the NetWeaver components Portal, Collaboration, and Knowledge Management. Pre-defined content is also provided by the SAP. Currently, the portfolio is having more than 100 business packages, which can be shipped in many languages.
The major advantage of using this portal is that you are allowed to use multiple JSP(Java Server Pages) pages at a time. Here you can have separate views and each view can be a JSP page or a web page that supports interaction with the J2EE server so that multiple works can be handled on the same page.
It can also be used with platform-independent applications. You can execute and implement it for maintaining many applications like Microsoft outlook etc.
26. Explain about SAP launchpad.
SAP launchpad simplifies access to business applications with a personalized as well as role-based launchpad site. This service will allow an organization for establishing a central point of access to SAP(Example: SAP S/4HANA), custom-built, third-party applications, etc., both on the on-premise and the cloud.

The SAP Launchpad service provides the following features:

Application Integration: It provides a central point of access for tasks and applications, with limitless integration to different UI technologies and third-party applications.
Intuitive and Engaging User Experience: It gives a personalized and role-based launchpad along with a content structure(flexible)that follows the SAP Fiori 3 design guidelines.
Integrations: It has an integration with central SAP BTP(Business Technology Platform) services like inbox and cloud identity services.
Extensibility: It is considered an extensible framework for customizations with the help of shell plugins and custom branding.
27. How can we create an OLAP(Online Analytical Processing) connection in CMC(Central Management Console)?
From SAP BO 4.0(SAP Business Objects 4.0) onwards it is allowed to connect BEx query through BICS(Business Intelligence Consumer Services) connection which is also called OLAP connection. With the help of CMC(Central Management Console) or IDT(Information Design Tool), it is possible to create and save the OLAP connection. This OLAP connection can be created for connection with the Multi-provider, BI(Business Intelligence) server, InfoCube, and BEx query. If the connection is specific for a particular Cube, Query, or Multi-provider then the connection will be created in query or cube base. Otherwise, the connection will be created on the BI server using which connection to any BEx query is possible. The advantage of Connection creation on the BI server is only a single OLAP connection is required for all BO reports.

Steps for creating OLAP connection to connect with BI server:

Login to CMC with the right of Administrator authorization and go for the OLAP Connection option.
Then select the option new connection.
Enter the details of the BI server as given in the below screenshot.


