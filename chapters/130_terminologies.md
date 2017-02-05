## Terminologies 



Web Service:
: A service, that is accessible by electronic devices over the internet. This makes it almost 
effortless to use a service which otherwise would be out of reach. Interactions with a service 
usually happen through enriched websites or other web-compatible applications and interfaces.

Open Specification:
: A specification is a formal and very detailed way of describing a technology, its internals and 
behaviour from external perspectives. It provides guidance for implementations to ensure a minimum
level of interoperability. Structured in a formalized document it might become a *technical 
standard*. *Open* means here at first nothing but it's accessible for anyone without restrictions. 
When it comes to the intellectual value itself, that might be handled differently, for example with 
an enclosed license.

Big Data:
: A collective term and philosophy that involves collecting, aggregating and analyzing data about 
each and everything (e.g. personal data, sensor data, transactional data, meta data). As the amount 
of data has started to exceed the capabilities of standalone computers and storages, distributed 
storing and parallel computing have been utilized in these fields. In order to be able to find 
meaningful data so that in can back decision-making processes, technologies from the fields of 
*artificial intelligence* and *machine learning* (e.g. neural networks) have been adapted. 

Profile Data:
: A collection of data points reflecting an individual's inherent information and other basic 
predominantly static data points (no sets), which in conjunction uniquely relate to that individual.

Digital Footprint:
: Refers to data that is related to an individual. It is distinguished between an active footprint, 
which involves data and information about an individual who chose to share them publicly, and a 
passive footprint, which includes all data about an individual collected by third parties without 
the individual's knowledge.

Personal Data:
: Any data points or datasets that are created by or at least related to an individual, including 
her *digital footprint*.

Personal Data as a Service (PDaaS):
: A web service controlled, owned and maybe even hosted by an individual. It provides access to 
the data subject's personal data and offers maintainability as well as permission management for 
those data. It can be seen as her personal agent; sometimes also referred to as *the system*.

Data Subject:
: An individual who first and foremost is the owner of all of her personal data; sometimes referred 
to as *owner*.

[Operator]{#terminologies--operator}:
: A *data subject* that uses a *PDaaS* to control (and probably host) her personal data; sometimes 
referred to as *data controller*

[(Data) Consumer]{#terminologies--consumer}:
: Third party who requests permission or is already allowed to access the *operator's* *personal 
data* through her *PDaaS*; sometimes referred to as *(data) collector*.

Data Broker:
: Third party with commercial interests in collecting, aggregating and analyzing information/data 
about humans from any possible resource in order to combine and enrich the data, to finally license 
those corpora to other organisations. [@report_2014_data-brokers]

Permission Request:
: A formalized attempt made by a third party to request permissions in order to access certain data 
points on the *PDaaS*. The request has to include all the data points that are demanded to being 
accessed as well as sufficient information about the purpose. It requires the third party to already 
being registered as *data consumer*.

Access Request:
: An attempt to actually access data provided by a *PDaaS*. The request primarily consists of a 
query, that defines what data points are tried to be accessed. The access is only permitted if
the query matches against the *permission profiles*.

Permission Profile:
: A set of access rules and configuration tied to a *data consumer*. It determines how long and what 
data is accessible by the related *data consumer*. The profile is the result of a reviewed and 
granted *permission request*. 

Endpoint:
: An endpoint is defined as part of a URI that uniquely associates to exactly one single *data 
consumer*. Usually it's the first part of a URI (e.g. domain incl. subdomains), whereas following 
parts indicating different resources that might be available within that endpoint. It can also be 
viewed as group of resources whose access is restricted. 