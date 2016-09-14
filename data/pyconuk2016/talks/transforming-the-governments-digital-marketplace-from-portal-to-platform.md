title: 'Transforming the government’s Digital Marketplace from portal to platform'
subtitle:
speaker: kevin-keenoy
---
The public sector can use the Digital Marketplace (https://www.digitalmarketplace.service.gov.uk/) to find people and technology for digital projects. Over £1,000,000,000 has been spent on cloud services by government through the G-Cloud framework since it launched in 2012, over half of that spend being with SMEs rather than big systems integrators. 

Back in 2014 the Digital Marketplace was a single Grails application (written in Groovy, running on the JVM) that provided a simple searchable catalogue of cloud services. Applications from suppliers to provide their services were handled externally by two separate systems run by the Crown Commercial Service.

Since then we have rebuilt the Digital Marketplace from scratch in Python as a RESTful system of Flask applications and expanded its functionality to supplant these external systems. It is now on its way to becoming a general-purpose platform for handling suppliers’ applications to sell their services to government.

This talk will explain how the the architecture of the system has evolved over a series of iterations of supplier application processes, and also delve deeper into how we drive both the frontend applications and data validation from a separate “content repository” of YAML files that can be maintained by content designers rather than developers.