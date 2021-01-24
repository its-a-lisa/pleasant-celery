---
title: 'GoComply with OSCAL & FedRAMP :: Introduction to OpenControl'
subtitle: Open source pi
author: _data/authors/jane-doe.yaml
excerpt: "This is the first post of the\_GoComply series\_that introduces open source pipeline to produce and process OSCAL and FedRAMP documents."
date: '2020-12-08'
thumb_image: images/3_thumb.jpg
thumb_image_alt: A group of people working in a cafe
image_alt: A group of people working in a cafe
layout: post
---
This is the first post of the [GoComply series](http://isimluk.com/tags/gocomply/) that introduces open source pipeline to produce and process OSCAL and FedRAMP documents. If You want to achieve continuous compliance at the lowest possible cost, [GoComply project](https://github.com/gocomply) is here to help. With GoComply, You will rely on open source tooling and your data will be stored in standardized formats and thus you will have a enough head room and knee room to achieve your organizational goals.


## OpenControl :: The File Format

So, let’s get started with the introduction of one simple file format that you can use to store your compliance related data. [OpenControl](https://open-control.org/) calls itself [A YAML-Powered Antidote To Bureaucracy](https://open-control.org/philosophy/), it is file format developed and adopted by dozen’s of industry [partners](https://open-control.org/members/). OpenControl presents this simple yet powerful idea that compliance data should not really be stored in excel sheet print outs, rather the data should be machine and human readable to lower the cost of compliance.

OpenControl Format is so easy to understand, that I won’t be wasting your time describing it. Instead, let me just reference one OpenControl document that contains Control Responses to NIST-800-53 for [OpenShift Container Platform 4](https://github.com/ComplianceAsCode/redhat/blob/7532d895f08c63f8ca592ebde5caff4452863f90/build/openshift-container-platform-4/component.yaml).

As we will see later in the GoComply series, OpenControl file format is advantageous for policy writing. The format is so easy to comprehend. Not only that security specialist don’t need to be trained to write it, but more importantly security specialist won’t be bothered too much to write it as compared to some other formats.

## OpenControl :: The Tools

Beyond the file format, [OpenControl project](https://github.com/opencontrol/) provides the open source tools to show case use of the OpenControl files and repositories. Important piece of the puzzle is project called [Compliance Masonry](https://github.com/opencontrol/compliance-masonry). It is a library to manipulate OpenControl files and it comes with a simple command-line tool to show case its capabilities.

Exemplary usage: Let’s pull OpenControl data with all the dependencies for Red Hat products. We will use ready made gocomply container that contains open-control masonry command. We will mount local directory to be able to see the results on the host.

## OpenControl :: The data

Multiple organizations published their compliance data in OpenControl format on the internet, many of those are published under Public Domain license. The [OpenControl Github Organization](https://github.com/opencontrol/) hosts such projects in a shared space others are linked from the project website.

I have spent some time in the repository of Compliance data for Red Hat products. Enterprising users are advised to look at the Makefile and github actions to see what best practices we have developed for OpenControl authorship.

## Summary

Today, we have learned about simple & open format for storing compliance data, the open source tools to process the format, and exemplary open source projects using these.
