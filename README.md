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
