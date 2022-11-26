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
  - title: Site Reliability Engineer
    company: Sotoon
    company_url: 'https://sotoon.ir/'
    company_logo: sotoon
    location: Tehran, Iran
    date_start: '2019-10-01'
    date_end: ''
    description: |2-
        * Built a platform to transfer, store, and analyze big data at petabyte scale for multiple user-facing applications with more than 110 million active users across Android, iOS, and Web
        * Developed Kubernetes operators to manage Apache {Kafka, Hadoop, ZooKeeper} clusters in a Platform-as-a-Service (PaaS) environment to reduce cluster creation and maintenance costs
        * Designed and developed a highly-available Wireguard and BGP-based cloud VPN solution with 99.9% uptime using Kubernetes operators 
        * Designed and developed CI/CD pipelines for Kubernetes operators to make the development and deployment process faster and safer
        * Maintained Apache {Druid, Kafka, Hadoop HDFS, Hadoop YARN, Spark, ZooKeeper} and Elastic Stack (ELK) clusters/services in an on-premise environment with 99.9% availability
        * Set up and maintained Monitoring and Alerting stack (Prometheus, Alertmanager, Grafana, and M3DB as long-term storage) and defined and tuned symptom-based alerts to reduce false alarms by 70%
        * Set up and maintained Kerberized Hadoop clusters to provide per-user authentication and authorization
        * Created mentorship documents and mentored new team members
        * Created maintenance and troubleshooting documents for team resources, clusters, and services to effectively train new and existing team members, share knowledge, and distribute responsibilities



  - title: Software Engineer Intern
    company: Sotoon
    company_url: 'https://sotoon.ir/'
    company_logo: sotoon
    location: Tehran, Iran
    date_start: '2019-07-15'
    date_end: '2029-09-30'
    description: |2-
        * Implemented RESTful APIs using Django and a CLI in GoLang to learn best practices, clean code, code review principles, and working in an agile team
design:
  columns: '2'
---
