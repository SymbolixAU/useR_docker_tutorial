# useR_docker_tutorial

This tutorial was delivered at the useR!2018 conference.  For the exercises you can download or fork the [r_docker_hello](https://github.com/SymbolixAU/r_docker_hello)  repo.

Here's the description:

# Production-ready R: Getting started with R and docker

## Outline

We will present some real-world data science scenarios and use these as a basis to walk participants through the process of building and deploying R-docker apps. Participants will gain experience in writing R scripts to run as stand-alone docker applications through examples, discussion and activities. We will provide code that can be used as a basis for participants' own projects.

## Topics 

See the `Presentation` folder for slides etc

* Introductory concepts 
   + Analyst data scientist vs developer data scientist and how this impacts how you design your projects and the libraries you use.
   + Discussion of scenarios to demonstrate how an analyst workflow might be approached with just R and the advantages/pitfalls of this
   + Docker and alternatives

Setting up your first docker environment (interactive tutorial): Participants will run R and Rstudio in a container, connect to it, and run simple scripts.

Demo of a simple web application and template process for renvironment variables

## Keywords 

docker, data science, shiny, cloud, automation

## Other background needed

Experience with using the command line and running basic scripts is helpful but not necessary.
We will cover concepts from R and docker in depth and touch on concepts from git and cloud computing. Some prior exposure to these things is helpful but no in depth knowledge is required.

## Target audience

Anyone who might want to share R code across users and platforms; who might be deploying automated scripts or building web applications using R.
Motivation (why do you think this would be a good tutorial for participants of useR! 2018)

R is a statistical computing environment and (increasingly) this also includes automated data pipelines, enterprise analytics applications, and web applications. Docker is an open platform that enables users to bundle code with dependencies and run it in multiple environments. When coupled with R it enables users to easily develop R scripts/applications that can be shared on different platforms, deployed in distributed cloud environments and slot into software projects alongside other components.

This is useful:

* when you have developed an automated script and need to run 100 copies of it at once to process a entire data set.
* If you must transfer an application that relies on specific environments that the user may or may not have (e.g. specific C++ or GDAL spatial frameworks)
* If you have to deploy a shiny application to a Windows Server (that doesn't
