=======================================================

Article Title: Intro to Elastic Search
Author Name: Aman 	
Author Profile: github.com/computerwala
Date: 26-10-2021

=======================================================

#What is Elasticsearch?
At its core, you can think of Elasticsearch as a server that can process JSON requests and give you back JSON data.

Elasticsearch is a distributed, open-source search and analytics engine built on Apache Lucene and developed in Java. It started as a scalable version of the Lucene open-source search framework then added the ability to horizontally scale Lucene indices. Elasticsearch allows you to store, search, and analyze huge volumes of data quickly and in near real-time and give back answers in milliseconds. It’s able to achieve fast search responses because instead of searching the text directly, it searches an index. It uses a structure based on documents instead of tables and schemas and comes with extensive REST APIs for storing and searching the data. At its core, you can think of Elasticsearch as a server that can process JSON requests and give you back JSON data.

#What is Elasticsearch used for?
Now that we have a general understanding of what Elasticsearch is, the logical concepts behind it, and its architecture, we have a better sense of why and how it can be used for a variety of use cases. Below, we’ll examine some of Elasticsearch’s primary use cases and provide examples of how companies are using it today.

##Primary Use Cases
Application search —- For applications that rely heavily on a search platform for the access, retrieval, and reporting of data.

##Website search —- Websites which store a lot of content find Elasticsearch a very useful tool for effective and accurate searches. It’s no surprise that Elasticsearch is steadily gaining ground in the site search domain sphere. 

##Enterprise search —- Elasticsearch allows enterprise-wide search that includes document search, E-commerce product search, blog search, people search, and any form of search you can think of. In fact, it has steadily penetrated and replaced the search solutions of most of the popular websites we use on a daily basis. From a more enterprise-specific perspective, Elasticsearch is used to great success in company intranets.

##Logging and log analytics —- As we’ve discussed, Elasticsearch is commonly used for ingesting and analyzing log data in near-real-time and in a scalable manner. It also provides important operational insights on log metrics to drive actions. 

##Infrastructure metrics and container monitoring —- Many companies use the ELK stack to analyze various metrics. This may involve gathering data across several performance parameters that vary by use case.

##Security analytics —- Another major analytics application of Elasticsearch is security analysis. Access logs and similar logs concerning system security can be analyzed with the ELK stack, providing a more complete picture of what’s going on across your systems in real-time.

##Business analytics —- Many of the built-in features available within the ELK Stack makes it a good option as a business analytics tool. However, there is a steep learning curve for implementing this product and in most organizations. This is especially true in cases where companies have multiple data sources besides Elasticsearch–since Kibana only works with Elasticsearch data. A good alternative is Knowi, an analytics platform that natively integrates with Elasticsearch and allows even non-technical business users to create visualizations and perform analytics on Elasticsearch data without prior knowledge or expertise of the ELK Stack.