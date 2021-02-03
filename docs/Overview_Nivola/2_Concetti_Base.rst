.. _Concetti_Base:


**Basic concepts**
******************

**Availability zones**
======================

These are the geographical areas where the data centres of public cloud service providers reside. Corporate customers choose one or more Availability Zones for their services according to their business needs. Availability Zones are availability zones made up of independent, isolated infrastructures hosted within the CSI Piemonte data centres. When creating their services, it is possible to choose the Availability Zone according to specific geographic distribution needs while maintaining high reliability.


.. image:: img/Availability-zones.png

.. _struttura_Organizzativa:

**The organisational structure**
================================

Within Nivola it will be possible to model an organisational structure on three levels so as to allow the allocation of responsibilities and management of services according to a precise hierarchy. In the Account, the infrastructure will be set up to meet the necessary technological and security requirements. The Division is entrusted with the task of controlling the consumption of the resources of the Accounts, which it will be able to create autonomously. The top of the structure is the Organisation, which will have a complete vision of the use of the platform, with the possibility of adapting it to the Divisions and Accounts.



The organisational structure is the hierarchical subdivision that allows customisation of services, access or settings for different groups of users or devices. In the Nivola platform the organisational structure is divided into 3 levels:

-  **Organisation**: it is hierarchically the highest organisational entity and may coincide with the name of the client e.g. "Regione Piemonte", "Csi Piemonte" and so on. In the platform, resources are available to various organisations, which are however logically completely separate and independent;;

-  **Division**: : is the second organisational level. An organisation may have several divisions. The concept of Division therefore represents a logical subdivision of the Organisation, and may therefore reflect a territorial, organisational or business type division; furthermore, each Division controls the resources and consumption of each Account within the Division";

-  **Account**: is the last organisational level and depends on the Division. A Division contains one or more Accounts. The Account is the organisational level within which the user can create, control and manage their services. "It is possible to create multiple accounts for the purpose of separating different projects, or to distinguish development environments from production environments, or to divide consumption reporting.


.. image:: img/struttura-org.png

Note that all resources and services can only be associated at Account level. It is not possible to associate services with Divisions or Organisations. The Account is therefore the container in which all user services are implemented and made available. The management of user resources will therefore take place at Account level with roles enabled to operate at this level.

.. image:: img/Org-ruoli.png

.. _utenti-ruoli:

**Users, Roles and Account**
============================

Several roles can be distinguished within the platform, which are related to the defined organisational structure. Each role can correspond to at least one user, and therefore at least one natural person performing that function. A person registered on the system can be associated with several roles even on different organisational structures. For example, a user may have different roles on accounts in different divisions.

To date, the following user roles are implemented within the system.

**Organisation Master**: this role represents users who can carry out administrative functions within the organisation, such as the creation of divisions and accounts within the organisation; it can also profile users to make them operational within its structure and possibly register users not yet present on the platform. The Organisation Master can monitor the costs and status of resources at all levels of his organisation (divisions and accounts) and view the related reports. However, he does not have access to the management functions (create/edit/delete) of the resources associated with the accounts of his organisation.

**Division Master**: this role represents users who can perform administrative functions within the Division, such as the creation of accounts within their division; they can also profile users to make them operational within their structure and possibly register users not yet present on the platform. The Organisation Master can monitor the costs and status of resources at all levels of his organisational structure (accounts) and view the related reports. However, he does not have access to the management functions (create/edit/delete) of the resources associated with the accounts of his division.

**Back Office Administrator**: user who, within the system, has privileges over BackOffice functions (registration of new Users, Accreditation, creation of organisational levels) and monitoring of costs and platform status. The BackOffice Administrator can profile users with roles at any level of the organisational structure. He can also access aggregated cost and consumption reports at any level. The role is usually associated to users of Csi Piemonte management and support groups.

**Account Master**: user who can manage all resources within the account, over which he therefore has maximum privileges. The Account Master can therefore create/delete/edit resources, he can also manage resources created by other users in the account. The account master can view and access cost and consumption reports for his account. The Account Master can register new users within his account and can profile or revoke users who have already been granted access.

**Account Viewer**: user who can view all resources within the Account, but does not have edit/delete privileges. The Account Viewer can therefore view the list of services active on the Account, and can view their details, but cannot activate new services or change their status. The Account Viewer can view and access reports of aggregate costs and consumption for the Account. The Account Viewer cannot register new users on the platform and cannot profile other users for access.

The phase of introducing a new user is as follows: a master, within the limits of the privileges of his hierarchical level, can accredit a user registered on the platform by assigning him a role, thereby granting him permissions to perform certain functions which will place the new user in a certain group.

The same operation can be carried out and delegated to the Backoffice operator.

To sum up:


-  An Organisation Master may :ref:`accredit or revoke users <Creare_Accreditare_Utente>` within its own divisions or accounts.

-  A Division Master may :ref:`accredit or revoke users <Creare_Accreditare_Utente>` within his own accounts and division.

-	An Account Master can  :ref:`accredit or revoke users <Creare_Accreditare_Utente>` within their account.

-  The Backoffice Administrator can :ref:`accredit or revoke users <Creare_Accreditare_Utente>` at any level of the hierarchical structure



