# ML Engineering on Google Cloud Platform

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)


This repository maintains hands-on labs and code samples that demonstrate best practices and patterns for implementing and operationalizing production grade machine learning workflows on Google Cloud Platform. 

## Navigating this repository
This repository is organized into two sections:
- [Mini workshops](./workshops/)
- [Code samples](./examples/)


### Mini workshops
This section contains hands-on labs for instructor led ML Engineering mini workshops. 

### Code Samples
This section compiles  samples demonstrating design and code patterns for a variety of ML Engineering topics. 


WCHOY QUIKLAB
Aug 22 @9:31PM EST.

steps:
- name: 'gcr.io/cloud-builders/docker'
  args: ['build', '-t', 'gcr.io/$PROJECT_ID/myimage', '.']
images: ['gcr.io/$PROJECT_ID/myimage']

Already have image (with digest): gcr.io/cloud-builders/docker
invalid argument "gcr.io/qwiklabs-gcp-03-b9322d5eece0/lab-03-tfx-image:" for "-t, --tag" flag: invalid reference format
See 'docker build --help'.