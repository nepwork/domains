# covidsim.team

[covidsim.team]("https://www.covidsim.team") (cst) is a research team in the field of COVID. It has identified certain software services necessary to build and use.

## Risav Karna

@risavkarna is a developer who created and coordinates the following systems and Github organizations:

## cosys.work

cosys.work is a development platform that provides nep.work like collaborative systems. CoSys primarily consists of archetypes of collaboration systems that can be used within the CoPlanetary ecosystem.

CoSys provides cloud enterprise services like hierarchical document access and collaboration to cst.


## nep.work team

nep.work is a development team that works with covidsim.team, NAAMII, i-ikigai and Meraki. nep.work provides a customization support and the following systems for cst:

1. Modeling and Simulation AI Platform

   This is built using Apache Spark and relevant database management systems when used in combination with Apache Ignite or with Cosmos DB when using Microsoft Azure. This system on its own does not create any API endpoints for the end users or the client applications i.e. dashboards, apps etc. However this system can read and write to the user facing database and the persistence system automatically creates the relevant views and API endpoints for the client applications or API users. The platform is capable of handling various research workloads and underlying model structures. This platform will be used by 4 different work groups in covidsim.team. It can also seamlessly integrate external graph based modeling efforts once a proper annotation of the graphs are provided. For other kinds of modeling, custom connector plugins need to be written.

2. Custom Dashboard and Visualization UI

   This system is an application layer addition to cater to the specific data entry and visualization needs of the end users. This system follows the end to end principle in the sense that, once the central server serves the application/website static contents, all application specific features reside at the communication end nodes (e.g. user's computers or phones) rather than in any intermediary or central node (e.g. government's or nep.work's servers). This application specific feature set also includes a user side in-browser database and event system. Thus in a strict sense, the dashboard and the visualization UIs do not self-update or react to any changes a remote database or system but rather to the changes in the self-managed client-side in-browser database. The message propagation to and from the in-browser database to the central system is also controlled by dashboard itself. A new developer will be joining for this section of the UI as it is going to need the most frequent updates.

3. Data Entry, Batch Import and Export UI

   This system is essentially an add on to the system in previous section of dashboards and UIs. This allows for batch upload, review, import and export of structured data files. For large files the system uses the robust in-browser DB to central user facing DB communications instead of simple browser based multipart upload requests. This makes the system well suited for upload and download of large files even in rough network conditions typical in rural Nepal. A programmer from the research team will be joining the development team for creating the data pre-processing pipeline needed for this section.The new developer mentioned above will be supporting said programmer to port the algorithms to TypeScript/RxJs/Angular/Ionic native idioms and structure.

4. Offline Support & Background Updates

   The system is designed to be offline first from the ground up. Several components of the offline-first design pre-date the 'Progressive Web App' standards and technologies. However the end result of the usual PWA technologies and this system is essentially almost the same. The bi-directional database design has several advantages over the usual service worker based PWA systems, which are also included in our dashboards and apps.

5. Anonymization & Encryption Systems

   The identification data for any data entity - not just humans - is not just logically but also physically separated from the rest of the data about said data entity. nep.work works using a novel system where identification and de-identification are entangled but separated to provide inherent anonymization by design. This proprietary system builds upon the shoulder of previous giants who have prepared open-sourced industry standard encryption and related libraries. Integrating this into any new application is not trivial because there are many cross cutting concerns and integration points for a complete end to end encryption coverage. Format-preserving encryption is used for introducing datatype-agnostic encryption to legacy application frameworks without altering the current data formats. Page-integrated encryption is used to encrypt sensitive user data before it is sent over the wire, without impacting user's experience and application's responsiveness.

6. Authentication and Authorization Systems

   cst can utilize highly complex organizational hierarchies and authorization rules that were originally developed for use with nep.work's permissioned global blockchains. The IAM server is itself also (de)anonymization-aware and encryption-aware i.e. the Identity and Access Management services request the appropriate anonymization and encryption services as and when applicable. These systems have multiple industry standard features including OAuth 2.0, OIDC, social media login, single sign-on/sign-off, LDAP integration and multi-tenancy.

7. Data Audit & Change Review System

   cst has proposed to integrate data audit and review system into the centralized platform. This was originally developed as a highly abstract git-like sub-system when the CoPlanetary systems were first developed. cst does not need the entire git controlled virtual file system but it does require capabilities to see who read or changed the data and when these accesses happened. Even without the full git-like system, this particular feature requires a fundamental change in how database schemas are designed and how the persistence layer handles data operations. nep.work utilizes an immutable data store and change stream subscriptions to this possible.

8. Data API and Usage Monitoring

   This comprises of a meta-dashboard that has panels to monitor other dashboards, applications and users of the central system.

## coplanetary.work

coplanetary.work are cross planetary business process optimization services. This network is infinitely scalable.

## Modular Architecture

The system is composed of the following 4-8-16 divisions.

### Concepts (Econs, Covidonomics, Orgs)

Concept packages define the behavior of a certain system semantics. These definitions are both technical and human-friendly.

### Companies (Business, Startup, Enterprise)

A set of socioware systems with a financial and legal interface.

### Indviduals (Id, Groups, Labels)

A non-representation of a set of representation id generators that provide unique hyper-graphical addresses.

### Event Schedulers (Emails, Business Processes, Contracts)

A control system and dashboard for scheduling of events of all kinds including digital and virtual.

### Event Ontology (Categories, Temporality, AsyncAnarchy)

A recording system of all commonly known semiotic descriptors and algebraic structures.

### YAM & IAM

Identity and De-identity cards and keys generators produce key cards for identification and de-identification.
