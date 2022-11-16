---
title: Alerts
id: alerts
date: 2022-10-10
full_link: 
short_description: >
  Alerts are downstream actions after a rule is triggered.
aka:
tags:
- fundamental
- extension
---
Alerts are configurable downstream actions.

<!--more--> 

They can be as simple as logging to `stdout` or as complex as delivering a {{< glossary_tooltip text="gRPC" term_id="grpc" >}} call to a client.

Falco can send alerts to:

- Standard Output
- A file
- Syslog
- A spawned program
- A HTTP[s] end point
- A client through the gRPC API
