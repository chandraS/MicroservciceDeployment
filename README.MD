A web client front end to the package tracking microservice system.

This is an Angular app, served up using nginx.

There is also a routing set up so that the Angular client can access the API gateway backend - all URLS prefixed /api/ are routed on to the API gateway container.

A production grade microservice running on AWS EKS cluster.
