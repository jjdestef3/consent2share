<a name="3.5.0"></a>
# Consent2Share 3.5.0 (2017-11-09)

Consent2Share 3.5.0 is the sixth release of Consent2Share V3.
The work on Consent2Share V3 is based on Consent2Share V2. 

### Features

*  The user can select multiple providers as "FROM" or "TO" to share data by creating one consent.
*  The user is reminded of PII constraints with a notice of disclosure when working in the demo system.
*  The provider can view the segmented CCD document as an HTML page in a new window, in addition to download it as a XML document.
*  The IExHub API is implemented to support FHIR to update the patient profile and to get health data by Patient ID.
*  An Angular UI Component Library is created for Consent2Share Shared Components.
*  Values set data are synchronized with VSAC.
*  The UI link is decoupled from edge server configuration.
*  The log is aggregated and correlated across microservices.
*  Third-party libraries are upgraded to fix critical security issues.
*  CloudFoundry User Account and Authentication (UAA) Server is upgraded to version 4.6.0.

### Documentation Updates
README.md files in repositories are updated.

### NOTES:

Consent2Share 3.5.0 release includes:

* Consent2Share UI 0.8.0: [https://github.com/bhits/c2s-ui/releases/tag/0.8.0](https://github.com/bhits/c2s-ui/releases/tag/0.8.0)
* Consent2Share UI API 0.8.0: [https://github.com/bhits/c2s-ui-api/releases/tag/0.8.0](https://github.com/bhits/c2s-ui-api/releases/tag/0.8.0)
* Configuration Server 0.5.0: [https://github.com/bhits/config-server/releases/tag/0.5.0](https://github.com/bhits/config-server/releases/tag/0.5.0)
* Context Handler 2.5.0: [https://github.com/bhits/context-handler/releases/tag/2.5.0](https://github.com/bhits/context-handler/releases/tag/2.5.0)
* Discovery Server 0.13.0: [https://github.com/bhits/discovery-server/releases/tag/0.13.0](https://github.com/bhits/discovery-server/releases/tag/0.13.0)
* Document Validator API 1.2.0: [https://github.com/bhits/document-validator/releases/tag/1.2.0](https://github.com/bhits/document-validator/releases/tag/1.2.0)
* Document Segmentation Service 2.6.0: [https://github.com/bhits/dss/releases/tag/2.6.0](https://github.com/bhits/dss/releases/tag/2.6.0)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* Edge Server 0.21.0: [https://github.com/bhits/edge-server/releases/tag/0.21.0](https://github.com/bhits/edge-server/releases/tag/0.21.0)
* FHIR Integration Service 0.1.0: [https://github.com/bhits/fis/releases/tag/0.1.0](https://github.com/bhits/fis/releases/tag/0.1.0)
* IExHub PIX PDQ 0.3.0: [https://github.com/bhits/iexhub-pix-pdq/releases/tag/0.3.0](https://github.com/bhits/iexhub-pix-pdq/releases/tag/0.3.0)
* IExHub XDSB 0.3.0: [https://github.com/bhits/iexhub-xdsdb/releases/tag/0.3.0](https://github.com/bhits/iexhub-xdsb/releases/tag/0.3.0)
* HAPI FHIR 3.1.0-01 : [https://github.com/bhits/hapi-fhir/releases/tag/3.1.0-01](https://github.com/bhits/hapi-fhir/releases/tag/3.1.0-01)
* Master UI 0.3.0: [https://github.com/bhits/master-ui/releases/tag/0.3.0](https://github.com/bhits/master-ui/releases/tag/0.3.0)
* Master UI API 0.3.0: [https://github.com/bhits/master-ui-api/releases/tag/0.3.0](https://github.com/bhits/master-ui-api/releases/tag/0.3.0)
* Patient Consent Management Service 2.6.0: [https://github.com/bhits/pcm/releases/tag/2.6.0](https://github.com/bhits/pcm/releases/tag/2.6.0)
* Policy Enforcement Point 2.2.0: [https://github.com/bhits/pep/releases/tag/2.2.0](https://github.com/bhits/pep/releases/tag/2.2.0)
* Patient Health Record 2.3.0: [https://github.com/bhits/phr/releases/tag/2.3.0](https://github.com/bhits/phr/releases/tag/2.3.0)
* Provider Lookup Service 3.4.0: [https://github.com/bhits/pls/releases/tag/3.4.0](https://github.com/bhits/pls/releases/tag/3.4.0)
* Provider UI 0.5.0: [https://github.com/bhits/provider-ui/releases/tag/0.5.0](https://github.com/bhits/provider-ui/releases/tag/0.5.0)
* Provider UI API 0.5.0: [https://github.com/bhits/provider-ui-api/releases/tag/0.5.0](https://github.com/bhits/provider-ui-api/releases/tag/0.5.0)
* Staff UI 0.6.0: [https://github.com/bhits/staff-ui/releases/tag/0.6.0](https://github.com/bhits/staff-ui/releases/tag/0.6.0)
* Staff  API 0.6.0: [https://github.com/bhits/staff-ui-api/releases/tag/0.6.0](https://github.com/bhits/staff-ui-api/releases/tag/0.6.0)
* Try Policy 2.3.0: [https://github.com/bhits/try-policy/releases/tag/2.3.0](https://github.com/bhits/try-policy/releases/tag/2.3.0)
* CloudFoundry User Account and Authentication (UAA) Server 4.6.0-01: [https://github.com/bhits/uaa/releases/tag/4.6.0-01](https://github.com/bhits/uaa/releases/tag/4.6.0-01)
* User Management Service 0.6.0: [https://github.com/bhits/ums/releases/tag/0.6.0](https://github.com/bhits/ums/releases/tag/0.6.0)
* Value Set Service 0.7.0: [https://github.com/bhits/vss/releases/tag/0.7.0](https://github.com/bhits/vss/releases/tag/0.7.0)
* Common Libraries 1.18.0: [https://github.com/bhits/common-libraries/releases/tag/1.18.0](https://github.com/bhits/common-libraries/releases/tag/1.18.0)
* C2S NG Shared Component Libraries v0.1.0: [https://github.com/bhits/c2s-ng-shared/releases/tag/v0.1.0](https://github.com/bhits/c2s-ng-shared/releases/tag/v0.1.0)
* Configuration Data 3.4.0: [https://github.com/bhits/c2s-config-data/releases/tag/3.4.0](https://github.com/bhits/c2s-config-data/releases/tag/3.4.0)



<a name="3.4.0"></a>
# Consent2Share 3.4.0 (2017-09-18)

Consent2Share 3.4.0 is the Fifth release of Consent2Share V3.
The work on Consent2Share V3 is based on Consent2Share V2. 

The overarching goal for Consent2Share V3 is to build a FHIR-centric, componentized, and cloud-based (cloud native) application.

### Features

*  i18n (Internationalization) support is added for database lookup values.
*  Document segmentation service configuration support is improved to handle multiple document template configurations.
*  C-CDA R2.1 Care Plan document segmentation is added to the document segmentation service.
*  A Notification is given when the account is locked because of failed login attempts.
*  A patient can get health data from the HIE XDS.b repository.
*  The IExHub is separated into two Spring Boot services iexhub-xdsb and iexhub-pix-pdq, with clean and generated IHE Soap clients.
*  Apache PDFBox is used to generate PDF.
*  Fixed critical security vulnerabilities that were found in the static scan.  
*  Fixed bugs.


### Documentation Updates

The following documents have been updated:

* C2S Master User Guide
* C2S Provider User Guide
* C2S Staff User Guide
* C2S Patient User Guide
* C2S Deployment Guide
* C2S Development Guide

Also README.md files in repositories and Docker image descriptions are updated as well.

### NOTES:

Consent2Share 3.4.0 release includes:

* Consent2Share UI 0.6.0: [https://github.com/bhits-dev/c2s-ui/releases/tag/0.6.0](https://github.com/bhits-dev/c2s-ui/releases/tag/0.6.0)
* Consent2Share UI API 0.6.0: [https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.6.0](https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.6.0)
* Configuration Server 0.4.0: [https://github.com/bhits-dev/config-server/releases/tag/0.4.0](https://github.com/bhits-dev/config-server/releases/tag/0.4.0)
* Context Handler 2.3.0: [https://github.com/bhits-dev/context-handler/releases/tag/2.3.0](https://github.com/bhits-dev/context-handler/releases/tag/2.3.0)
* Discovery Server 0.12.0: [https://github.com/bhits-dev/discovery-server/releases/tag/0.12.0](https://github.com/bhits-dev/discovery-server/releases/tag/0.12.0)
* Document Validator API 1.1.0: [https://github.com/bhits-dev/document-validator/releases/tag/1.1.0](https://github.com/bhits-dev/document-validator/releases/tag/1.1.0)
* Document Segmentation Service 2.4.0: [https://github.com/bhits-dev/dss/releases/tag/2.4.0](https://github.com/bhits-dev/dss/releases/tag/2.4.0)
* Edge Server 0.20.0: [https://github.com/bhits-dev/edge-server/releases/tag/0.20.0](https://github.com/bhits-dev/edge-server/releases/tag/0.20.0)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* IExHub PIX PDQ 0.1.0: [https://github.com/bhits-dev/iexhub-pix-pdq/releases/tag/0.1.0](https://github.com/bhits-dev/iexhub-pix-pdq/releases/tag/0.1.0)
* IExHub XDSB 0.1.0: [https://github.com/bhits-dev/iexhub-xdsdb/releases/tag/0.1.0](https://github.com/bhits-dev/iexhub-xdsb/releases/tag/0.1.0)
* HAPI FHIR 2.3-01 : [https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01](https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01)
* Master UI 0.2.0: [https://github.com/bhits-dev/master-ui/releases/tag/0.2.0](https://github.com/bhits-dev/master-ui/releases/tag/0.2.0)
* Master UI API 0.2.0: [https://github.com/bhits-dev/master-ui-api/releases/tag/0.2.0](https://github.com/bhits-dev/master-ui-api/releases/tag/0.2.0)
* Patient Consent Management Service 2.4.0: [https://github.com/bhits-dev/pcm/releases/tag/2.4.0](https://github.com/bhits-dev/pcm/releases/tag/2.4.0)
* Policy Enforcement Point 2.1.0: [https://github.com/bhits-dev/pep/releases/tag/2.1.0](https://github.com/bhits-dev/pep/releases/tag/2.1.0)
* Patient Health Record 2.2.0: [https://github.com/bhits-dev/phr/releases/tag/2.2.0](https://github.com/bhits-dev/phr/releases/tag/2.2.0)
* Provider Lookup Service 3.3.0: [https://github.com/bhits-dev/pls/releases/tag/3.3.0](https://github.com/bhits-dev/pls/releases/tag/3.3.0)
* Provider UI 0.3.0: [https://github.com/bhits-dev/provider-ui/releases/tag/0.3.0](https://github.com/bhits-dev/provider-ui/releases/tag/0.3.0)
* Provider UI API 0.3.0: [https://github.com/bhits-dev/provider-ui-api/releases/tag/0.3.0](https://github.com/bhits-dev/provider-ui-api/releases/tag/0.3.0)
* Staff UI 0.4.0: [https://github.com/bhits-dev/staff-ui/releases/tag/0.4.0](https://github.com/bhits-dev/staff-ui/releases/tag/0.4.0)
* Staff  API 0.4.0: [https://github.com/bhits-dev/staff-ui-api/releases/tag/0.4.0](https://github.com/bhits-dev/staff-ui-api/releases/tag/0.4.0)
* Try Policy 2.2.0: [https://github.com/bhits-dev/try-policy/releases/tag/2.2.0](https://github.com/bhits-dev/try-policy/releases/tag/2.2.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-08: [https://github.com/bhits-dev/uaa/releases/tag/3.4.1-08](https://github.com/bhits-dev/uaa/releases/tag/3.4.1-08)
* User Management Service 0.4.0: [https://github.com/bhits-dev/ums/releases/tag/0.4.0](https://github.com/bhits-dev/ums/releases/tag/0.4.0)
* Value Set Service 0.5.0: [https://github.com/bhits-dev/vss/releases/tag/0.5.0](https://github.com/bhits-dev/vss/releases/tag/0.5.0)
* Common Libraries 1.16.0: [https://github.com/bhits-dev/common-libraries/releases/tag/1.16.0](https://github.com/bhits-dev/common-libraries/releases/tag/1.16.0)
* Configuration Data 3.4.0: [https://github.com/bhits-dev/c2s-config-data/releases/tag/3.4.0](https://github.com/bhits-dev/c2s-config-data/releases/tag/3.4.0)



<a name="3.3.0"></a>
# Consent2Share 3.3.0 (2017-08-07)

Consent2Share 3.3.0 is the Fourth release of Consent2Share V3.
The work on Consent2Share V3 is based on Consent2Share V2. 
Version 3 is still in progress and one more release will come over the next month.

The overarching goal for Consent2Share V3 is to build a FHIR-centric, componentized, and cloud-based (cloud native) application.

### Features

* Single login UI 
* Consent activity history
* Trying my policy sample document update
* Configurable patent search fields
* UI styling update
* Patient Registration/Update in HIE
* New PIX Client
* Update Patient profile (with  Avatar) 
* Try my policy for provider
* Multiple identifier support for patient 


### Documentation Updates

The following documents have been updated:

* C2S Deployment Guide
* C2S Provider User Guide
* C2S Patient User Guide

Also README.md files in repositories and Docker image descriptions are updated.

### NOTES:

Consent2Share 3.3.0 release includes:

* Consent2Share UI 0.5.0: [https://github.com/bhits-dev/c2s-ui/releases/tag/0.5.0](https://github.com/bhits-dev/c2s-ui/releases/tag/0.5.0)
* Consent2Share UI API 0.5.0: [https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.5.0](https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.5.0)
* Configuration Server 0.3.0: [https://github.com/bhits/config-server/releases/tag/0.3.0](https://github.com/bhits/config-server/releases/tag/0.3.0)
* Context Handler 2.2.0: [https://github.com/bhits-dev/context-handler/releases/tag/2.2.0](https://github.com/bhits-dev/context-handler/releases/tag/2.2.0)
* Discovery Server 0.11.0: [https://github.com/bhits/discovery-server/releases/tag/0.11.0](https://github.com/bhits/discovery-server/releases/tag/0.11.0)
* Document Validator API 1.0.0: [https://github.com/bhits/document-validator/releases/tag/1.0.0](https://github.com/bhits/document-validator/releases/tag/1.0.0)
* Document Segmentation Service 2.3.0: [https://github.com/bhits-dev/dss/releases/tag/2.3.0](https://github.com/bhits-dev/dss/releases/tag/2.3.0)
* Edge Server 0.19.0: [https://github.com/bhits-dev/edge-server/releases/tag/0.19.0](https://github.com/bhits-dev/edge-server/releases/tag/0.19.0)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* HAPI FHIR 2.3-01 : [https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01](https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01)
* Master UI 0.1.0: [https://github.com/bhits-dev/master-ui/releases/tag/0.1.0](https://github.com/bhits-dev/master-ui/releases/tag/0.1.0)
* Master UI API 0.1.0: [https://github.com/bhits-dev/master-ui-api/releases/tag/0.1.0](https://github.com/bhits-dev/master-ui-api/releases/tag/0.1.0)
* Patient Consent Management Service 2.3.0: [https://github.com/bhits-dev/pcm/releases/tag/2.3.0](https://github.com/bhits-dev/pcm/releases/tag/2.3.0)
* Policy Enforcement Point 2.0.0: [https://github.com/bhits-dev/pep/releases/tag/2.0.0](https://github.com/bhits-dev/pep/releases/tag/2.0.0)
* Patient Health Record 2.1.0: [https://github.com/bhits-dev/phr/releases/tag/2.1.0](https://github.com/bhits-dev/phr/releases/tag/2.1.0)
* Provider Lookup Service 3.2.0: [https://github.com/bhits-dev/pls/releases/tag/3.2.0](https://github.com/bhits-dev/pls/releases/tag/3.2.0)
* Provider UI 0.2.0: [https://github.com/bhits-dev/provider-ui/releases/tag/0.2.0](https://github.com/bhits-dev/provider-ui/releases/tag/0.2.0)
* Provider UI API 0.2.0: [https://github.com/bhits-dev/provider-ui-api/releases/tag/0.2.0](https://github.com/bhits-dev/provider-ui-api/releases/tag/0.2.0)
* Staff UI 0.3.0: [https://github.com/bhits-dev/staff-ui/releases/tag/0.3.0](https://github.com/bhits-dev/staff-ui/releases/tag/0.3.0)
* Staff  API 0.3.0: [https://github.com/bhits-dev/staff-ui-api/releases/tag/0.3.0](https://github.com/bhits-dev/staff-ui-api/releases/tag/0.3.0)
* Try Policy 2.1.0: [https://github.com/bhits-dev/try-policy/releases/tag/2.1.0](https://github.com/bhits-dev/try-policy/releases/tag/2.1.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-08: [https://github.com/bhits-dev/uaa/releases/tag/3.4.1-08](https://github.com/bhits-dev/uaa/releases/tag/3.4.1-08)
* User Management Service 0.3.0: [https://github.com/bhits-dev/ums/releases/tag/0.3.0](https://github.com/bhits-dev/ums/releases/tag/0.3.0)
* Value Set Service 0.4.0: [https://github.com/bhits-dev/vss/releases/tag/0.4.0](https://github.com/bhits-dev/vss/releases/tag/0.4.0)
* Common Libraries 1.13.0: [https://github.com/bhits-dev/common-libraries/releases/tag/1.13.0](https://github.com/bhits-dev/common-libraries/releases/tag/1.13.0)
* Configuration Data 3.3.0: [https://github.com/bhits-dev/c2s-config-data/releases/tag/3.3.0](https://github.com/bhits-dev/c2s-config-data/releases/tag/3.3.0)


<a name="3.2.0"></a>
# Consent2Share 3.2.0 (2017-06-27)

Consent2Share 3.2.0 is the Third release of Consent2Share V3.
The work on Consent2Share V3 is based on Consent2Share V2. 
Version 3 is still in progress and more releases will come over the next 3 months.

The overarching goal for Consent2Share V3 is to build a FHIR-centric, componentized, and cloud-based (cloud native) application.

### Features

* EHR integration push model
    - Provider manages patient, provider creates consent for patient to sign, provider segment C-CDA for downloading.
* Try My Policy Feature.
* Auditing upate.
* Update document validator.

### Documentation Updates

The following documents have been updated:

* Consent2Share Deployment Guide
* Consent2Share Provider User Guide
* Consent2Share Patient User Guide

Also README.md files in repositories and Docker image descriptions are updated.

### NOTES:

Consent2Share 3.2.0 release includes:

* Consent2Share UI 0.4.0: [https://github.com/bhits-dev/c2s-ui/releases/tag/0.4.0](https://github.com/bhits-dev/c2s-ui/releases/tag/0.4.0)
* Consent2Share UI API 0.4.0: [https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.4.0](https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.4.0)
* Configuration Server 0.3.0: [https://github.com/bhits/config-server/releases/tag/0.3.0](https://github.com/bhits/config-server/releases/tag/0.3.0)
* Context Handler 2.1.0: [https://github.com/bhits-dev/context-handler/releases/tag/2.1.0](https://github.com/bhits-dev/context-handler/releases/tag/2.1.0)
* Discovery Server 0.11.0: [https://github.com/bhits/discovery-server/releases/tag/0.11.0](https://github.com/bhits/discovery-server/releases/tag/0.11.0)
* Document Validator API 1.0.0: [https://github.com/bhits/document-validator/releases/tag/1.0.0](https://github.com/bhits/document-validator/releases/tag/1.0.0)
* Document Segmentation Service 2.2.0: [https://github.com/bhits-dev/dss/releases/tag/2.2.0](https://github.com/bhits-dev/dss/releases/tag/2.2.0)
* Edge Server 0.18.0: [https://github.com/bhits-dev/edge-server/releases/tag/0.18.0](https://github.com/bhits-dev/edge-server/releases/tag/0.18.0)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* HAPI FHIR 2.3-01 : [https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01](https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01)
* Patient Consent Management Service 2.2.0: [https://github.com/bhits-dev/pcm/releases/tag/2.2.0](https://github.com/bhits-dev/pcm/releases/tag/2.2.0)
* Policy Enforcement Point 2.0.0: [https://github.com/bhits-dev/pep/releases/tag/2.0.0](https://github.com/bhits-dev/pep/releases/tag/2.0.0)
* Patient Health Record 2.0.0: [https://github.com/bhits-dev/phr/releases/tag/2.0.0](https://github.com/bhits-dev/phr/releases/tag/2.0.0)
* Provider Lookup Service 3.1.0: [https://github.com/bhits-dev/pls/releases/tag/3.1.0](https://github.com/bhits-dev/pls/releases/tag/3.1.0)
* Provider UI 0.1.0: [https://github.com/bhits-dev/provider-ui/releases/tag/0.1.0](https://github.com/bhits-dev/provider-ui/releases/tag/0.1.0)
* Provider UI API 0.1.0: [https://github.com/bhits-dev/provider-ui-api/releases/tag/0.1.0](https://github.com/bhits-dev/provider-ui-api/releases/tag/0.1.0)
* Staff UI 0.2.0: [https://github.com/bhits-dev/staff-ui/releases/tag/0.2.0](https://github.com/bhits-dev/staff-ui/releases/tag/0.2.0)
* Staff  API 0.2.0: [https://github.com/bhits-dev/staff-ui-api/releases/tag/0.2.0](https://github.com/bhits-dev/staff-ui-api/releases/tag/0.2.0)
* Try Policy 2.0.0: [https://github.com/bhits-dev/try-policy/releases/tag/2.0.0](https://github.com/bhits-dev/try-policy/releases/tag/2.0.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-07: [https://github.com/bhits-dev/uaa/releases/tag/3.4.1-07](https://github.com/bhits-dev/uaa/releases/tag/3.4.1-07)
* User Management Service 0.2.0: [https://github.com/bhits-dev/ums/releases/tag/0.2.0](https://github.com/bhits-dev/ums/releases/tag/0.2.0)
* Value Set Service 0.4.0: [https://github.com/bhits-dev/vss/releases/tag/0.4.0](https://github.com/bhits-dev/vss/releases/tag/0.4.0)
* Common Libraries 1.12.0: [https://github.com/bhits-dev/common-libraries/releases/tag/1.12.0](https://github.com/bhits-dev/common-libraries/releases/tag/1.12.0)
* Configuration Data 3.2.0: [https://github.com/bhits-dev/c2s-config-data/releases/tag/3.2.0](https://github.com/bhits-dev/c2s-config-data/releases/tag/3.2.0)


<a name="3.1.0"></a>
# Consent2Share 3.1.0 (2017-05-09)

Consent2Share 3.1.0 is the second release of Consent2Share V3.
The work on Consent2Share V3 is based on Consent2Share V2. 
Version 3 is still in progress and more releases will come over the next 6 months.

The overarching goal for Consent2Share V3 is to build a FHIR-centric, componentized, and cloud-based (cloud native) application.

### Features

* Styled consent2share UI.
* Data segmentation with FHIR consent and share logic.
* Staff admin is able to register/manage patient user
* C2s-ui support i18n.

### Documentation Updates

The following documents have been updated:

* Consent2Share Deployment Guide
* Consent2Share Patient User Guide

Also README.md files in repositories and Docker image descriptions are updated.

### NOTES:

Consent2Share 3.1.0 release includes:

* Consent2Share UI 0.3.0: [https://github.com/bhits-dev/c2s-ui/releases/tag/0.3.0](https://github.com/bhits-dev/c2s-ui/releases/tag/0.1.0)
* Consent2Share UI API 0.3.0: [https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.3.0](https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.1.0)
* Configuration Server 0.3.0: [https://github.com/bhits/config-server/releases/tag/0.3.0](https://github.com/bhits/config-server/releases/tag/0.3.0)
* Context Handler 2.0.0: [https://github.com/bhits-dev/context-handler/releases/tag/2.0.0](https://github.com/bhits-dev/context-handler/releases/tag/2.0.0)
* Discovery Server 0.11.0: [https://github.com/bhits/discovery-server/releases/tag/0.11.0](https://github.com/bhits/discovery-server/releases/tag/0.11.0)
* Document Validator API 0.11.0: [https://github.com/bhits/document-validator/releases/tag/0.11.0](https://github.com/bhits/document-validator/releases/tag/0.11.0)
* Document Segmentation Service API 2.1.0: [https://github.com/bhits-dev/dss/releases/tag/2.1.0](https://github.com/bhits-dev/dss/releases/tag/2.1.0)
* Edge Server 0.17.0: [https://github.com/bhits-dev/edge-server/releases/tag/0.17.0](https://github.com/bhits-dev/edge-server/releases/tag/0.17.0)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* HAPI FHIR 2.3-01 : [https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01](https://github.com/bhits-dev/hapi-fhir/releases/tag/2.3-01)
* Patient Consent Management Service 2.1.0: [https://github.com/bhits-dev/pcm/releases/tag/2.1.0](https://github.com/bhits-dev/pcm/releases/tag/2.1.0)
* Policy Enforcement Point API 1.10.0: [https://github.com/bhits/pep-api/releases/tag/1.10.0](https://github.com/bhits/pep-api/releases/tag/1.10.0)
* Provider Lookup Service 3.0.0: [https://github.com/bhits-dev/pls/releases/tag/3.0.0](https://github.com/bhits-dev/pls/releases/tag/3.0.0)
* Staff UI 0.1.0: [https://github.com/bhits-dev/staff-ui/releases/tag/0.1.0](https://github.com/bhits-dev/staff-ui/releases/tag/0.1.0)
* Staff UI API 0.1.0: [https://github.com/bhits-dev/staff-ui-api/releases/tag/0.1.0](https://github.com/bhits-dev/staff-ui-api/releases/tag/0.1.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-06: [https://github.com/bhits-dev/uaa/releases/tag/3.4.1-06](https://github.com/bhits-dev/uaa/releases/tag/3.4.1-06)
* User Management Service 0.1.0: [https://github.com/bhits-dev/ums/releases/tag/0.1.0](https://github.com/bhits-dev/ums/releases/tag/0.1.0)
* Value Set Service 0.3.0: [https://github.com/bhits-dev/vss/releases/tag/0.3.0](https://github.com/bhits-dev/vss/releases/tag/0.3.0)
* Common Libraries 1.11.0: [https://github.com/bhits-dev/common-libraries/releases/tag/1.11.0](https://github.com/bhits-dev/common-libraries/releases/tag/1.11.0)
* Configuration Data 3.1.0: [https://github.com/bhits-dev/c2s-config-data/releases/tag/3.1.0](https://github.com/bhits-dev/c2s-config-data/releases/tag/3.1.0)


<a name="3.0.0"></a>
# Consent2Share 3.0.0 (2017-03-31)

Consent2Share 3.0.0 is the first release of Consent2Share V3.
The work on Consent2Share V3 is based on Consent2Share V2. 
Version 3 is still in progress and more releases will come over the next 6 months.

The overarching goal for Consent2Share V3 is to build a FHIR-centric, componentized, and cloud-based (cloud native) application.

### Features

* The patient user can login to a card-based, componentized UI.
* The patient user can add his or her providers by looking up providers using the card-based, componentized UI.
* The patient user can create, sign, revoke, and delete his or her consent using the card-based, componentized UI.
* When creating a consent, the patient user can chose “Share” instead of “Not Share”.
* The consent created by the patient user is stored in FHIR STU3 format in the FHIR server.
* The patient user UI is redesigned and rewritten in Angular.
* Core services are decoupled from the UIs by using backend for frontends (BFF) pattern.
* The domain for patient consent management is redesigned to focus only and focus well on consent.


### Documentation Updates

The following documents have been updated:

* Consent2Share Deployment Guide
* Consent2Share Patient User Guide

Also README.md files in repositories and Docker image descriptions are updated.

### NOTES:

Consent2Share 3.0.0 release includes:

* Consent2Share UI 0.1.0: [https://github.com/bhits-dev/c2s-ui/releases/tag/0.1.0](https://github.com/bhits-dev/c2s-ui/releases/tag/0.1.0)
* Consent2Share UI API 0.1.0: [https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.1.0](https://github.com/bhits-dev/c2s-ui-api/releases/tag/0.1.0)
* Configuration Server 0.3.0: [https://github.com/bhits-dev/config-server/releases/tag/0.3.0](https://github.com/bhits-dev/config-server/releases/tag/0.3.0)
* Discovery Server 0.11.0: [https://github.com/bhits-dev/discovery-server/releases/tag/0.11.0](https://github.com/bhits-dev/discovery-server/releases/tag/0.11.0)
* Edge Server 0.15.0: [https://github.com/bhits-dev/edge-server/releases/tag/0.15.0](https://github.com/bhits-dev/edge-server/releases/tag/0.15.0)
* Patient Consent Management Service 2.0.0: [https://github.com/bhits-dev/pcm/releases/tag/2.0.0](https://github.com/bhits-dev/pcm/releases/tag/2.0.0)
* Provider Lookup Service 3.0.0: [https://github.com/bhits-dev/pls/releases/tag/3.0.0](https://github.com/bhits-dev/pls/releases/tag/3.0.0)
* Value Set Service 0.2.0: [https://github.com/bhits-dev/vss/releases/tag/0.2.0](https://github.com/bhits-dev/vss/releases/tag/0.2.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-04: [https://github.com/bhits-dev/uaa/releases/tag/3.4.1-04](https://github.com/bhits-dev/uaa/releases/tag/3.4.1-04)
* Common Libraries 1.10.0: [https://github.com/bhits-dev/common-libraries/releases/tag/1.10.0](https://github.com/bhits-dev/common-libraries/releases/tag/1.10.0)
* Configuration Data 3.0.0: [https://github.com/bhits-dev/c2s-config-data/releases/tag/3.0.0](https://github.com/bhits-dev/c2s-config-data/releases/tag/3.0.0)


<a name="2.1.2"></a>
# Consent2Share 2.1.2 (2017-07-25)

### Features

Node.js released a [security update]( https://nodejs.org/en/blog/vulnerability/july-2017-security-releases/) on July 11, 2017. Node.js stated that updates are now available for all active Node.js release lines. These include the fix for the high severity vulnerability identified in a previous announcement, one additional lower priority Node.js vulnerability in the 4.x release line, as well as some lower priority fixes for Node.js dependencies across the current release lines. 

The following Consent2Share projects have been enhanced to accommodate the most recent LTS version of Node.js (6.11.1), which includes the security updates:

* **Patient Portal UI**
* **Admin Portal UI** 

Consent2Share V2.1.2 does not affect build artifacts such as JARs and Docker images which were made available during release V2.1.1. You can continue to use the latest Docker images from the Docker Hub. However, if you are currently coding, contributing to our code base, and building your own binary artifacts from the Consent2Share source code, make certain to use Consent2Share V2.1.2, which accommodates the Node.js 6.11.1 security update.


### NOTES:

Consent2Share 2.1.2 release includes:

* Admin Portal UI 0.20.1: [https://github.com/bhits/admin-portal-ui/releases/tag/0.20.1](https://github.com/bhits/admin-portal-ui/releases/tag/0.20.1)
* Patient Portal UI 0.26.1: [https://github.com/bhits/patient-portal-ui/releases/tag/0.26.1](https://github.com/bhits/patient-portal-ui/releases/tag/0.26.1)
* Patient User API 0.16.0: [https://github.com/bhits/patient-user-api/releases/tag/0.16.0](https://github.com/bhits/patient-user-api/releases/tag/0.16.0)
* Patient Consent Management API 1.24.0: [https://github.com/bhits/pcm-api/releases/tag/1.24.0](https://github.com/bhits/pcm-api/releases/tag/1.24.0)
* Patient Health Record API 1.24.0: [https://github.com/bhits/phr-api/releases/tag/1.24.0](https://github.com/bhits/phr-api/releases/tag/1.24.0)
* Try My Policy API 1.17.0: [https://github.com/bhits/try-policy-api/releases/tag/1.17.0](https://github.com/bhits/try-policy-api/releases/tag/1.17.0)
* Patient Registration API 1.19.0: [https://github.com/bhits/registration-api/releases/tag/1.19.0](https://github.com/bhits/registration-api/releases/tag/1.19.0)
* Provider Lookup Service API 2.1.0: [https://github.com/bhits/pls-api/releases/tag/2.1.0](https://github.com/bhits/pls-api/releases/tag/2.1.0)
* Policy Enforcement Point API 1.10.0: [https://github.com/bhits/pep-api/releases/tag/1.10.0](https://github.com/bhits/pep-api/releases/tag/1.10.0)
* Context Handler API 1.11.0: [https://github.com/bhits/context-handler/releases/tag/1.11.0](https://github.com/bhits/context-handler/releases/tag/1.11.0)
* Document Segmentation Service API 1.16.0: [https://github.com/bhits/dss-api/releases/tag/1.16.0](https://github.com/bhits/dss-api/releases/tag/1.16.0)
* Document Validator API 0.11.0: [https://github.com/bhits/document-validator/releases/tag/0.11.0](https://github.com/bhits/document-validator/releases/tag/0.11.0)
* Information Exchange Hub 0.6.0: [https://github.com/bhits/iexhub/releases/tag/0.6.0](https://github.com/bhits/iexhub/releases/tag/0.6.0)
* Information Exchange Hub Generated Code Library 1.0.0: [https://github.com/bhits/iexhub-generated/releases/tag/1.0.0](https://github.com/bhits/iexhub-generated/releases/tag/1.0.0)
* Edge Server 0.14.0: [https://github.com/bhits/edge-server/releases/tag/0.14.0](https://github.com/bhits/edge-server/releases/tag/0.14.0)
* Discovery Server 0.10.0: [https://github.com/bhits/discovery-server/releases/tag/0.10.0](https://github.com/bhits/discovery-server/releases/tag/0.10.0)
* Configuration Server 0.2.0: [https://github.com/bhits/config-server/releases/tag/0.2.0](https://github.com/bhits/config-server/releases/tag/0.2.0)
* Configuration Data 2.1.0: [https://github.com/bhits/c2s-config-data/releases/tag/2.1.0](https://github.com/bhits/c2s-config-data/releases/tag/2.1.0)
     - Note: After you checkout this repository from the tag mentioned above, use only the master branch. 
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-02: [https://github.com/bhits/uaa/releases/tag/3.4.1-02](https://github.com/bhits/uaa/releases/tag/3.4.1-02)
* Logback Audit 0.6.1: [https://github.com/bhits/logback-audit/releases/tag/v_0.6.1](https://github.com/bhits/logback-audit/releases/tag/v_0.6.1)
* Common Libraries 1.9.0: [https://github.com/bhits/common-libraries/releases/tag/1.9.0](https://github.com/bhits/common-libraries/releases/tag/1.9.0)
* Java Jar Runner 8u102-jre: [https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre](https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* Spring Boot Application Runner 1.10.0: [https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0](https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0)

<a name="2.1.1"></a>
# Consent2Share 2.1.1 (2017-03-22)

### Features

The following projects have been enhanced to support internationalization (i18n):

* **Patient Portal UI**
* **Admin Portal UI** 
* **Patient User API**
* **Patient Consent Management API**
* **Patient Health Record API**
* **Try My Policy API**


The supported languages in Consent2Share Release 2.1.1 are **English (en_US)** and **Spanish (es_ES)**. This work was done in collaboration with Adela Grando, Assistant Professor, Biomedical Informatics, **Arizona State University**, and her student Wentao Zhou.

### Documentation Updates

The following documents have been updated:

* Consent2Share Admin User Guide
* Consent2Share Patient User Guide

Also, the README.md files in the repositories for the APIs listed above and the latest tag in Docker image descriptions are updated as well.

### NOTES:

Consent2Share 2.1.1 release includes:

* Admin Portal UI 0.20.0: [https://github.com/bhits/admin-portal-ui/releases/tag/0.20.0](https://github.com/bhits/admin-portal-ui/releases/tag/0.20.0)
* Patient Portal UI 0.26.0: [https://github.com/bhits/patient-portal-ui/releases/tag/0.26.0](https://github.com/bhits/patient-portal-ui/releases/tag/0.26.0)
* Patient User API 0.16.0: [https://github.com/bhits/patient-user-api/releases/tag/0.16.0](https://github.com/bhits/patient-user-api/releases/tag/0.16.0)
* Patient Consent Management API 1.24.0: [https://github.com/bhits/pcm-api/releases/tag/1.24.0](https://github.com/bhits/pcm-api/releases/tag/1.24.0)
* Patient Health Record API 1.24.0: [https://github.com/bhits/phr-api/releases/tag/1.24.0](https://github.com/bhits/phr-api/releases/tag/1.24.0)
* Try My Policy API 1.17.0: [https://github.com/bhits/try-policy-api/releases/tag/1.17.0](https://github.com/bhits/try-policy-api/releases/tag/1.17.0)
* Patient Registration API 1.19.0: [https://github.com/bhits/registration-api/releases/tag/1.19.0](https://github.com/bhits/registration-api/releases/tag/1.19.0)
* Provider Lookup Service API 2.1.0: [https://github.com/bhits/pls-api/releases/tag/2.1.0](https://github.com/bhits/pls-api/releases/tag/2.1.0)
* Policy Enforcement Point API 1.10.0: [https://github.com/bhits/pep-api/releases/tag/1.10.0](https://github.com/bhits/pep-api/releases/tag/1.10.0)
* Context Handler API 1.11.0: [https://github.com/bhits/context-handler/releases/tag/1.11.0](https://github.com/bhits/context-handler/releases/tag/1.11.0)
* Document Segmentation Service API 1.16.0: [https://github.com/bhits/dss-api/releases/tag/1.16.0](https://github.com/bhits/dss-api/releases/tag/1.16.0)
* Document Validator API 0.11.0: [https://github.com/bhits/document-validator/releases/tag/0.11.0](https://github.com/bhits/document-validator/releases/tag/0.11.0)
* Information Exchange Hub 0.6.0: [https://github.com/bhits/iexhub/releases/tag/0.6.0](https://github.com/bhits/iexhub/releases/tag/0.6.0)
* Information Exchange Hub Generated Code Library 1.0.0: [https://github.com/bhits/iexhub-generated/releases/tag/1.0.0](https://github.com/bhits/iexhub-generated/releases/tag/1.0.0)
* Edge Server 0.14.0: [https://github.com/bhits/edge-server/releases/tag/0.14.0](https://github.com/bhits/edge-server/releases/tag/0.14.0)
* Discovery Server 0.10.0: [https://github.com/bhits/discovery-server/releases/tag/0.10.0](https://github.com/bhits/discovery-server/releases/tag/0.10.0)
* Configuration Server 0.2.0: [https://github.com/bhits/config-server/releases/tag/0.2.0](https://github.com/bhits/config-server/releases/tag/0.2.0)
* Configuration Data 2.1.0: [https://github.com/bhits/c2s-config-data/releases/tag/2.1.0](https://github.com/bhits/c2s-config-data/releases/tag/2.1.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-02: [https://github.com/bhits/uaa/releases/tag/3.4.1-02](https://github.com/bhits/uaa/releases/tag/3.4.1-02)
* Logback Audit 0.6.1: [https://github.com/bhits/logback-audit/releases/tag/v_0.6.1](https://github.com/bhits/logback-audit/releases/tag/v_0.6.1)
* Common Libraries 1.9.0: [https://github.com/bhits/common-libraries/releases/tag/1.9.0](https://github.com/bhits/common-libraries/releases/tag/1.9.0)
* Java Jar Runner 8u102-jre: [https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre](https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* Spring Boot Application Runner 1.10.0: [https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0](https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0)

 - Configuration Data 2.1.1
       - Clone the [master branch](https://github.com/bhits/c2s-config-data.git)
       - Reset the code to Release 2.1.1 commit
       - It will run only with **master** branch.
       
<a name="2.1.0"></a>
# Consent2Share 2.1.0 (2017-02-06)

### Features

* **Consent Management:** Supports FHIR Consent STU3 to publish to a FHIR server
* **Provider Lookup Service:** Rewritten to use Spring Boot for implementation, which is in line with other components’ implementation
* **Configuration Server:** Supports source-controlled configuration data for Spring Boot Microservices
* **UI:** Support writing Angular 2.0 style web component
* **Information Exchange Hub:**: Supports FHIR Consent STU3 as a FHIR server and support flexible configuration location for the application to run
* Easier Local Development setup by removing required Maven global settings
* Upgraded Spring Boot and Spring Cloud dependencies

### Documentation Updates

The following documents have been updated:

* Consent2Share Development Guide
* Consent2Share Deployment Guide
* Consent2Share Technical Blueprint

Also README.md files in repositories and Docker image descriptions are updated.

### NOTES:

Consent2Share 2.1.0 release includes:

* Patient Portal UI 0.24.0: [https://github.com/bhits/patient-portal-ui/releases/tag/0.24.0](https://github.com/bhits/patient-portal-ui/releases/tag/0.24.0)
* Admin Portal UI 0.18.0: [https://github.com/bhits/admin-portal-ui/releases/tag/0.18.0](https://github.com/bhits/admin-portal-ui/releases/tag/0.18.0)
* Patient Registration API 1.19.0: [https://github.com/bhits/registration-api/releases/tag/1.19.0](https://github.com/bhits/registration-api/releases/tag/1.19.0)
* Patient User API 0.15.0: [https://github.com/bhits/patient-user-api/releases/tag/0.15.0](https://github.com/bhits/patient-user-api/releases/tag/0.15.0)
* Patient Consent Management API 1.22.0: [https://github.com/bhits/pcm-api/releases/tag/1.22.0](https://github.com/bhits/pcm-api/releases/tag/1.22.0)
* Provider Lookup Service API 2.1.0: [https://github.com/bhits/pls-api/releases/tag/2.1.0](https://github.com/bhits/pls-api/releases/tag/2.1.0)
* Try My Policy API 1.16.0: [https://github.com/bhits/try-policy-api/releases/tag/1.16.0](https://github.com/bhits/try-policy-api/releases/tag/1.16.0)
* Patient Health Record API 1.22.0: [https://github.com/bhits/phr-api/releases/tag/1.22.0](https://github.com/bhits/phr-api/releases/tag/1.22.0)
* Policy Enforcement Point API 1.10.0: [https://github.com/bhits/pep-api/releases/tag/1.10.0](https://github.com/bhits/pep-api/releases/tag/1.10.0)
* Context Handler API 1.11.0: [https://github.com/bhits/context-handler/releases/tag/1.11.0](https://github.com/bhits/context-handler/releases/tag/1.11.0)
* Document Segmentation Service API 1.16.0: [https://github.com/bhits/dss-api/releases/tag/1.16.0](https://github.com/bhits/dss-api/releases/tag/1.16.0)
* Document Validator API 0.11.0: [https://github.com/bhits/document-validator/releases/tag/0.11.0](https://github.com/bhits/document-validator/releases/tag/0.11.0)
* Information Exchange Hub 0.6.0: [https://github.com/bhits/iexhub/releases/tag/0.6.0](https://github.com/bhits/iexhub/releases/tag/0.6.0)
* Information Exchange Hub Generated Code Library 1.0.0: [https://github.com/bhits/iexhub-generated/releases/tag/1.0.0](https://github.com/bhits/iexhub-generated/releases/tag/1.0.0)
* Edge Server 0.14.0: [https://github.com/bhits/edge-server/releases/tag/0.14.0](https://github.com/bhits/edge-server/releases/tag/0.14.0)
* Discovery Server 0.10.0: [https://github.com/bhits/discovery-server/releases/tag/0.10.0](https://github.com/bhits/discovery-server/releases/tag/0.10.0)
* Configuration Server 0.2.0: [https://github.com/bhits/config-server/releases/tag/0.2.0](https://github.com/bhits/config-server/releases/tag/0.2.0)
* Configuration Data 2.1.0: [https://github.com/bhits/c2s-config-data/releases/tag/2.1.0](https://github.com/bhits/c2s-config-data/releases/tag/2.1.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-02: [https://github.com/bhits/uaa/releases/tag/3.4.1-02](https://github.com/bhits/uaa/releases/tag/3.4.1-02)
* Logback Audit 0.6.1: [https://github.com/bhits/logback-audit/releases/tag/v_0.6.1](https://github.com/bhits/logback-audit/releases/tag/v_0.6.1)
* Common Libraries 1.9.0: [https://github.com/bhits/common-libraries/releases/tag/1.9.0](https://github.com/bhits/common-libraries/releases/tag/1.9.0)
* Java Jar Runner 8u102-jre: [https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre](https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* Spring Boot Application Runner 1.10.0: [https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0](https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0)
 
 - Configuration Data 2.1.0
       - Clone the [master branch](https://github.com/bhits/c2s-config-data.git)
       - Reset the code to Release 2.1.0 commit
       - It will run only with **master** branch.
       
<a name="2.0.0"></a>
# Consent2Share 2.0.0 (2016-10-31)

### Features

* **Patient Registration:** Collect patient demographic and register patient in Consent2Share and HIE (if connected)
* **Security:** Use OAuth 2.0 and OpenID Connect for authentication and authorization
* **Provider Management:** Allow patients to search, delete, and manage their providers
* **Consent Management:** Allow patients to create, sign, and revoke consent policies that determine the level of privacy applied to the patient’s health record when it is shared between providers
* **Try Policy:** : Allow patients to use the Try My Policy tool against a medical record in order to view the effects of their consent directive segmentation choices
* **Value Set Management:** Provide an API to determine sensitivity categories for medical record entries
* **Data Segmentation:** Handle the segmentation of patients’ sensitive health information according to their consent directive
* **View PHI:** Allow patients to view medical records and health information retrieved from an HIE (if connected)
* **Document Validation:** Provide an API to validate C32, C-CDA R1 and 2.1 documents based on schema and/or schematron rules

### NOTES:

Consent2Share 2.0.0 release includes:

* Patient Portal UI 0.20.0: [https://github.com/bhits/patient-portal-ui/releases/tag/0.20.0](https://github.com/bhits/patient-portal-ui/releases/tag/0.20.0)
* Admin Portal UI 0.13.0: [https://github.com/bhits/admin-portal-ui/releases/tag/0.13.0](https://github.com/bhits/admin-portal-ui/releases/tag/0.13.0)
* Patient Registration API 1.15.0: [https://github.com/bhits/registration-api/releases/tag/1.15.0](https://github.com/bhits/registration-api/releases/tag/1.15.0)
* Patient User API 0.12.0: [https://github.com/bhits/patient-user-api/releases/tag/0.12.0](https://github.com/bhits/patient-user-api/releases/tag/0.12.0)
* Patient Consent Management API 1.18.0: [https://github.com/bhits/pcm-api/releases/tag/1.18.0](https://github.com/bhits/pcm-api/releases/tag/1.18.0)
* Provider Lookup Service API 1.11.0: [https://github.com/bhits/pls-api/releases/tag/1.11.0](https://github.com/bhits/pls-api/releases/tag/1.11.0)
* Try My Policy API 1.13.0: [https://github.com/bhits/try-policy-api/releases/tag/1.13.0](https://github.com/bhits/try-policy-api/releases/tag/1.13.0)
* Patient Health Record API 1.19.0: [https://github.com/bhits/phr-api/releases/tag/1.19.0](https://github.com/bhits/phr-api/releases/tag/1.19.0)
* Policy Enforcement Point API 1.7.0: [https://github.com/bhits/pep-api/releases/tag/1.7.0](https://github.com/bhits/pep-api/releases/tag/1.7.0)
* Context Handler API 1.8.0: [https://github.com/bhits/context-handler/releases/tag/1.8.0](https://github.com/bhits/context-handler/releases/tag/1.8.0)
* Document Segmentation Service API 1.13.0: [https://github.com/bhits/dss-api/releases/tag/1.13.0](https://github.com/bhits/dss-api/releases/tag/1.13.0)
* Document Validator API 0.9.0: [https://github.com/bhits/document-validator/releases/tag/0.9.0](https://github.com/bhits/document-validator/releases/tag/0.9.0)
* Information Exchange Hub 0.3.0: [https://github.com/bhits/iexhub/releases/tag/0.3.0](https://github.com/bhits/iexhub/releases/tag/0.3.0)
* Edge Server 0.11.0: [https://github.com/bhits/edge-server/releases/tag/0.11.0](https://github.com/bhits/edge-server/releases/tag/0.11.0)
* Discovery Server 0.8.0: [https://github.com/bhits/discovery-server/releases/tag/0.8.0](https://github.com/bhits/discovery-server/releases/tag/0.8.0)
* CloudFoundry User Account and Authentication (UAA) Server 3.4.1-01: [https://github.com/bhits/uaa/releases/tag/3.4.1-01](https://github.com/bhits/uaa/releases/tag/3.4.1-01)
* Logback Audit 0.6.1: [https://github.com/bhits/logback-audit/releases/tag/v_0.6.1](https://github.com/bhits/logback-audit/releases/tag/v_0.6.1)
* Common Libraries 1.7.0: [https://github.com/bhits/common-libraries/releases/tag/1.7.0](https://github.com/bhits/common-libraries/releases/tag/1.7.0)
* Java Jar Runner 8u102-jre: [https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre](https://github.com/bhits/java-jar-runner/releases/tag/8u102-jre)
* Dockerized JBoss Drools Guvnor 5.5.0: [https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0](https://github.com/bhits/dockerized-drools-guvnor/releases/tag/5.5.0)
* Spring Boot Application Runner 1.10.0: [https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0](https://github.com/bhits/spring-boot-app-runner/releases/tag/1.10.0)


[//]: # (The followings are commented out full template for Release Notes, for each new release, using this)
[//]: # (template to fill out information and put the Release Notes at the top of this file.)
[//]: # (And also paste the new Release Notes as inline description when creating the new Github release)
[//]: # (in consent2share Github repository's release tab.)

[//]: # (<a name="x.x.x"></a>)
[//]: # (# x.x.x (yyyy-mm-dd)

[//]: # (### Features)

[//]: # (* **pcm-api:** provide what feature)
[//]: # (* **pls-api:** implement what feature)


[//]: # (### Bug Fixes)

[//]: # (* **pcm-api:** fix what)
[//]: # (* **pls-api:** fix what)


[//]: # (### Code Refactoring)

[//]: # (* **pcm-api:** remove what)
[//]: # (* **pcm-api:** refactor what)


[//]: # (### Documentation Updates)

[//]: # (* Updated Deployment Guide for…)


[//]: # (### BREAKING CHANGES)

[//]: # (* **pcm-api:** break change )
[//]: # (* **pcm-api:** refactor what)


[//]: # (### NOTES:)

[//]: # (Consent2Share x.x.x requires:)

[//]: # (* Patient Portal UI x.x.x: [release url](http://)
[//]: # (* Admin Portal UI x.x.x: [release url](http://)
