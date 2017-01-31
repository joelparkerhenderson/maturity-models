# Infrastructure as Code (IaC) maturity model

Credit: https://programmaticponderings.com/2016/11/25/infrastructure-as-code-maturity-model/


## IaC Level -1: Regressive

Processes unrepeatable, poorly controlled, and reactive

  * Limited infrastructure is provisioned and managed as code
  * Infrastructure provisioning still requires many manual processes
  * Infrastructure code is not written using industry-standard tooling and patterns
  * Infrastructure code not built, unit-tested, provisioned and managed, as part of a pipeline
  * Infrastructure code, processes, and procedures are inconsistently documented, and not available to all required parties

## IaC Level 0: Repeatable

Processes documented and partly automated

  * All infrastructure code and configuration are stored in a centralized version control system
  * Testing, provisioning, and management of infrastructure are done as part of automated pipeline
  * Infrastructure is deployable as individual components
  * Leverages programmatic interfaces into physical devices
  * Automated security inspection of components and dependencies
  * Self-service CLI or API, where internal customers provision their resources
  * All code, processes, and procedures documented and available
  * Immutable infrastructure and processes

## IaC Level 1: Consistent

Automated processes applied across whole application lifecycle

  * Fully automated provisioning and management of infrastructure
  * Minimal use of unsupported, ‘home-grown’ infrastructure tooling
  * Unit-tests meet code-coverage requirements
  * Code is continuously tested upon every check-in to version control system
  * Continuously available infrastructure using zero-downtime provisioning
  * Uses configuration registries
  * Templatized configuration files (no awk/sed magic)
  * Secrets are securely management
  * Auto-scaling based on user-defined load characteristics

## IaC Level 2: Quantitatively Managed

Processes measured and controlled

  * Uses infrastructure definition files
  * Capable of automated rollbacks
  * Infrastructure and supporting systems are highly available and fault tolerant
  * Externalized configuration, no black box API to modify configuration
  * Fully monitored infrastructure with configurable alerting
  * Aggregated, auditable infrastructure logging
  * All code, processes, and procedures are well documented in a Knowledge Management System
  * Infrastructure code uses declarative versus imperative programming model, maybe…

## IaC Level 3: Optimizing

Focus on process improvement

  * Self-healing, self-configurable, self-optimizing, infrastructure
  * Performance tested and monitored against business KPIs
  * Maximal infrastructure utilization and workload density
  * Adheres to Cloud Native and 12-Factor patterns
  * Cloud-agnostic code that minimizes cloud vendor lock-in
