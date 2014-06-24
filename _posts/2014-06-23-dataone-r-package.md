---
layout: post
title: "Create a native R package for accessing DataONE"
description: "Design and implement a native DataONE implementation in R."
category: Data management
tags: [data management, R]
---
{% include JB/setup %}

# Overview
Refactor the dataone R package to natively implement access to the DataONE REST services API within the R language.  The current implementation uses a bridge to execute the Java DataONE libclient library, which is not portable across platforms, and can be fragile to build and install on certain platforms.  By refactoring, all R platforms will be supported through the use of the RCurl library.

# Participants (confirmed)
- Matt Jones (NCEAS)

# Participants (proposed)
- Carl Boettiger
- Karthik Ram

