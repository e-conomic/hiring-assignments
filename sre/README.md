# Recruitment assignment for Site Reliability Engineer

This task is intended for candidates applying for an SRE position at the Visma 
e-conomic Site Reliability Engineering team. This assignment is built around some of the 
technologies used in our production environment.

We're super happy that you're considering to join us at e-conomic. The 
challenge below should hope to bring a small view into the life of an SRE, 
and serve as a entrypoint for a good discussion at the technical interview.

## Introduction

e-conomic runs a broad palette of services to provide the functionality our 
application serves our customers. A part of this functionality is provided 
by a layer of microservices. 
These microservices are hosted in Kubernetes and have different requirements in 
terms of availability and resilience, both from the requests they serve but also
the data that some of them hold.
To verify how well a given candidate fit our needs, the test is built with the 
intention for you to show of your skills in some of the technologies we use on a
daily basis.  
Should you feel like expanding above and beyond the scope of the test, feel free
to do so. We will enjoy discussing your reasoning for doing so.

## The Challenge

1. Develop a microservice which
_What if I can't develop a service?_

  1. Takes HTTP GET requests with a random ID (/1, /529852, etc.), requests a 
  document from the microservice we have provided in the `dummy-pdf-or-png` 
  subdirectory of this repository, and then returns the document with correct 
  ime-type.
  1. Provides an endpoint for health monitoring.
  1. Has tests, so regressions can be identified.
  1. Fails safe.
  1. Logs relevant info.
  1. Exposes pormetheus metrics.

1. Provision your infrastructure
  1. Use IaC to provision your cloud resources

1. Package and deploy the  service 
  1. Setup a CI and CD pipeline for the service. It should build the service, run the tests and deploy it. 
  1. Provide a docker file and containerize your service. 
  1. Provide a k8s manifest or use helm charts

Overall the service must be considered production-ready.

Bonus points if you consider that here is a good developer experience

## Delivery

Fork this repository into a public repository on your own Github profile, and 
deliver your solution there.

## Questions?

If you have questions about the task or would like us to further specify some of
the tings written above, you can contact the person who gave you the assignment.
