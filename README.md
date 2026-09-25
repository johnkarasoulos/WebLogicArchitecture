# WebLogicArchitecture

Historically, financial-services enterprise applications delivered by the integrator have been deployed on dedicated hardware at each client location, with each environment operating its own Oracle Database and WebLogic instance.

The objective is to transition to a SaaS platform hosted within a single Oracle Cloud Infrastructure (OCI) tenancy. This approach will consolidate the existing standalone deployments, reduce the operational cost and complexity of maintaining separate technology stacks, and continue to meet the isolation requirements of financial-services clients.

This article sketches a target architecture and the design decisions behind it.
