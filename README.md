# seven_svn

abcd_sevenzhou123456
Users Request Access to Powerbroker Group
After the Powerbroker group is created, members of the project team who need to switch user to the project team’s service account for each EAP Hortonworks environment should submit a Linux SRPA request in VSM to be to be added to a pre-approved privileged access group.  In the SRPA request, specify the name of the PB group created in the previous section of this document.  The BDS team has provided a document with instructions for submitting the SRPA request.
Table of Contents
Overview	3
Create Service Account	4
Create LDAP Group	5
Add Service Account and LDAP Group to the Cluster	7
Hortonworks Configuration	8
Create Powerbroker Group	9
Users Request Access to Powerbroker Group	10
NCS Requests	11
SSH/SCP Access	12
Appendix A – Enable Unix ID	12

 
Overview
As new projects get approved and funded to come on board the Enterprise Analytics Platform (EAP), the project team will need to follow the steps outlined in this document to obtain access to the servers in each of the 3 Hortonworks clusters (POC/DEV, ITG and PRO) for the EAP.  Each project team will create a service account, an LDAP group, and a Powerbroker Group for each environment and will follow steps to add the service account and LDAP group to the nodes of the clusters.  For some projects, NCS requests may also be needed for connections to remote systems.
The DEV environment setup should be initiated immediately at project kick-off.  The ITG and PRO setup can be initiated prior to the migration to those environments.
A member of the Enterprise Analytics Platform Engineering team is generally assigned to each project to facilitate the setup of the new project team’s access and security.  The platform team can be reached using this distribution list: globalit-coe-sdm-engineering@hpe.com.  
