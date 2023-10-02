
# Backend feature requirements:

## 1. Spec a REST API for an SIR that connects to customer records via UUID

Please see:
/specAPI/update-sir-connect-customer-uuid-api-spec.json

Staff can attach a customer to an SIR by way of updating the SIR details with UUID



## 2. Application must also support the ability to track customer/users that are not in the existing db.
Please see:
/specAPI/create-customer-instance-api-spec.json

Staff can create a customer details instance which will programmtically generate a UUID. There is a "isKnown" key that accepts a Boolean value (checkbox in UI). 
If false, then this customer details instance is created as an anonymous tracking of details that can be updated when more information is available (name, further security instances, images...). 



## 3. What are the requirements for connecting the application into the FOLIO ecosystem natively?

Following the fundamental documentation guidelines:

Actively participate/query in forums (issue tracker, Slack chat..) [Reference the concise list](https://dev.folio.org/community/#collaboration-tools) 

Understand that the key server-side element is Okapi. It is the FOLIO middleware and API gateway. It is a server that is a single entry point into the system. 

Individual back-end modules are in separate repositories, named in the convention of "mod-*name*". 

[Reference the backend infrastructure repositories](https://dev.folio.org/source-code/map/#backend-infrastructure) 

Adhere to FOLIO Guidelines for Contributing Code
[see here](https://dev.folio.org/guidelines/contributing/)
-Note: For all FOLIO code repositories, they are trying to follow [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow). 

Consistently adhere to [Naming Conventions](https://dev.folio.org/guidelines/naming-conventions/) 


Understand the Build, test, and deployment infrastructure. 
[here](https://dev.folio.org/guides/automation/)

Remain familiar with the Development, design, and review processes
[here](https://dev.folio.org/guidelines/development-design-review/)


Join and participate in FOLIO Special Interest Groups as warranted by the needs of your team goals. [Here is one I am interested in, A11Y!](https://wiki.folio.org/display/A11Y) 