---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Engineer
    company: Sotoon
    company_url: 'https://sotoon.ir/'
    company_logo: sotoon
    location: Tehran, Iran
    date_start: '2019-10-01'
    date_end: ''
    description: |2-
        * Built a multi-user platform to transfer, store, and analyze big data at petabyte scale 
        * Maintained Apache Druid, Kafka, Hadoop HDFS, Hadoop YARN, Spark, and ZooKeeper clusters/services in an on-premises environment
        * Set up and maintained Monitoring and Alerting stack (Prometheus, Alertmanager, Grafana, and M3DB as long-term storage)
        * Maintained Elastic Stack (ELK) cluster
        * Developed Kubernetes operators to manage Apache Kafka, Hadoop, and Zookeeper clusters and Wireguard (VPN tunnel) service in a Platform-as-a-Service (PaaS) environment
        * Created mentorship documents and Mentored new team members
        * Created technical and system documents about team resources, clusters, services, and how to maintain and troubleshoot them


  - title: Software Engineer Intern
    company: Cafe Bazaar
    company_url: 'https://cafebazaar.ir/app?l=en'
    company_logo: bazaar
    location: Tehran, Iran
    date_start: '2019-07-15'
    date_end: '2029-09-30'
    description: |2-
        * Partnered with interns to implement RESTful APIs in Django and a CLI by GoLang to learn best practices, clean code, code review principles, and working as an agile team

design:
  columns: '2'
---
