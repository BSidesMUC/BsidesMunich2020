---
layout: talk
title: "Kubernetes Security: A Developer's Nightmare?"
details: true
track: 1
accepted: true
length: 45
timeslot:
  start: 2000-01-01 15:30:00
  end: 2000-01-01 16:15:00
speakers: 
  - name: Andreas Falk
    handle: andifalk
    photo: 
    bio: "Andreas Falk has been working in enterprise application development projects for more than twenty years. Currently, he is working as a managing consultant for [Novatec Consulting](https://www.novatec-gmbh.de) located in Germany.
In various projects, he has since been around as an architect, coach, and developer. His focus is on the agile development of cloud-native enterprise Java applications using the complete Spring platform. As a member of the [Open Web Application Security Project (OWASP)](https://www.owasp.org), he likes to have a closer look at all aspects of application security as well. Andreas is also a frequent speaker at conferences like Spring I/O, CloudFoundry Summit, and Devoxx."
recording_uri: https://www.youtube.com/watch?v=1wXoNUKZ6G4
slides_uri: /files/slides/01-07_andreas_falk_secure_kubernetes_dev_nightmare_slides.pdf
---

With the rise of Kubernetes, the Java developer has arrived in the SecDevOps age as well.
But by the multitude of complex tasks, the necessary security is often neglected. Even in managed clusters of well-known cloud providers, there are many points of attack waiting to be exploited.

In this session, the security-critical components of a Kubernetes cluster are presented from a developer's perspective. Typical security problems and corresponding measures to mitigate these will be shown. This includes topics such as Linux namespaces and capabilities, container security and pod security policies.

By the end of this presentation, you will know more thoroughly the essence of secure development on Kubernetes and how to escape the developer's security nightmare.

### Outline

Developing applications and deploying these securely as containerized instances into Kubernetes is hard. Kubernetes is a complex beast for developers.
In this session attendees can expect to learn about:

- Linux security basics for (docker) containers  
- How to create containers with secure coding patterns (like running with non-root etc.)
- Security patterns for Kubernetes (like pod security context etc.)
- Securely handling secrets in Kubernetes
- Useful tools for container image scanning, evaluating Kubernetes YAML configurations
