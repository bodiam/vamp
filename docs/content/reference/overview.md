---
title: Overview
weight: 10
menu:
  main:
    parent: reference
    identifier: reference-overview
---
# Overview

Vamp has three basic entities you can work with:

-   **Breeds**: static artifacts that describe single services and their dependencies.  
-   **Blueprints**: blueprints are, well, blueprints! They describe the how breeds work in runtime and what properties they should have.  
-   **Deployments**: running blueprints. You can have many of one blueprint and perform actions on them at runtime. Plus, you can turn any running deployment into a blueprint.  

Of these three, the blueprint is the center of attention. Why?
 
-   Because you can inline breeds into blueprints.
-   Because you create deployments by `POST`-ing a blueprint.
-   Because they have information on scale, filters and SLA's.

This means you will probably start out just using blueprints.

