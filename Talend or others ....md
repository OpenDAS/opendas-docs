### What is Talend ? ###

Talend is an ETL (Extract-Transform-Load) allowing to manage the flow of incoming messages from ActiveMQ and then send them towards exit components and the other way around, with or without intervention on the structure, the value, or the data format. 

[ http://www.talend.com/ ]( http://www.talend.com/ )

* ETL advantages \:
    * Filter messages in entrance, modify data, and re-inject them towards an outgoing source.
    * Independence and portability of the solution by changing "graphically" components and organization of the data
    * Once the schema of the data and the rules of management defined, a Java binary can be exported, and installed on a server.

* Data sources \:
    * Data sources can be multiple, both in entrance and in exit.

### Other consumers ###

OpenDAS is a universal and generic Data Acquisition System. We have packaged many examples with Talend, but any JMS consumer can be used


    * Components supplied by Talend allow to connect to a large number of data sources.
     * SAP
     * Sage
     * OpenERP
     * Magento
     *  Prestashop
     * Salesforce
     * Excel
     * LDAP
     * SQL (Oracle, PostgreSQL, SQL Server...)
     * ... 