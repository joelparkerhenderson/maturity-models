# Infrastructure as Code (IaC) maturity model by Joel Parker Henderson

Free, open source, Creative Commons License.


## Level 1: Initial, Informal, Implicit, Irregular, Inconsistent, Individual Usage

Level 1 is Initial, Informal, Implicit, Irregular, Inconsistent, Individual Usage.

* Infrastructure as Code is in initial stages, including areas such as assessments, a trial project, a pilot, a prototype.

* Teammates on a project are starting to talking about IaC, typically with one hero or small group of people who want it.

* Code quality of the IaC code tends to be hand-rolled, or hand-tested, or hand-tooled.

Examples:

* Sign up for Amazon Web Services

* Write a shell script that check a server's uptime

Ideas to improve:

* Shift from using hand-rolled one-off installations toward using package managers such as apm, apt, brew, choco melpa, gem, pip, yum, as well as configuration management such as config files and dot files.

* Learn about any popular mainstream configuration tools, such as Ansible, Salt, Puppet, Chef.



## Level 2: Developing, Describing, Departmental Usage

Level 2 is Developing, Describing, Department-wide Usage.

* Infrastructure is developing, typically because of a team's need. Typical software at this level often includes cloud services (e.g. AWS), containerization (e.g. Docker), configuration management (e.g. Ansible), orchestration tooling (e.g. Kubernetes), continuous delivery software (e.g. GoCD), and potentially platform as a service offerings (e.g. Heroku).

* Teammates from the department  are talking about IaC, and working on ways to use IaC to help the department across multiple projects.

* Code quality is starting to use automated tests for the IaC code, not just any application code.

Examples:

* There are at least a few projects where a developer can commit a line of code, and the code flows into production, by using continuous integration, continuous delivery, and optionally capabilities for feature flags, throttle releases (blue/green, go/no, canary releases, etc.).

* The department shares IaC code and does IaC collaboration using source code repositories, and optionally capabilities for chat, help, documentation, wikis, planning, and the like.

Ideas to improve:

* Technical: Develop IaC code in ways that align with your teams' project code, such as doing code reviews, roadmap planning, idempotency testing, etc. Get familiar with all of the examples above: AWS, Docker, Ansible, Kubernetes, GoCD< Heroku; even if you choose to use alternatives to these, the learning will transfer well.

* Social: Share IaC code with other teams, get feedback, and improve the code and all its related capabilities for collaboration, documentation, verification, etc.



## Level 3: Standardizing

Level 3 is Standardizing, Specifying, Scaling, Service-oriented, Segment Usage

* Infrastructure is standardizing, typically thanks to teams creating specifications, sharable code, source code repositories.

* Team members can quickly, confidently, and effectively create IaC projects, complete with end-to-end success, as well as any documentation and certification.

* Code quality aims toward service-oriented capabilities, such as APIs, discoverability, mixability.

Examples:

* Typically projects can be one-button deployed, including just-in-time as-needed creation of related resources, databases, networks, addresses, etc.

* IaC is in use beyond just the IT department; this may include self-service tools, such as setting up new laptops, as well as significant business tools, such as IT-business teams that can configure and deploy new services independently of IT system adminsitrators.

How to improve:

* Technical: Learn how to modularize Iac code and distribute it, such as by using package managers, modules, libraries, functional decomposition, idempotency testing, hot reloads, etc.

* Social: Explicity plan for good governance. Governance includes technical areas such as versioning and release management, team areas such as five-why root cause analysis and blameless retrospectives, and management areas such as budgeting and approvals.


## Level 4: Managing

* Level 4 is Managing, Measuring, Mainstreaming, Mission-oriented, Mass-scale Usage.

* Infrastructure is managed and measured in concert with explicit mission statements. Good candidates are [OKRs (Objectives and Key Results)](https://github.com/joelparkerhenderson/objectives_and_key_results), [KPI (Key Performance Indicator) metrics](ttps://github.com/joelparkerhenderson/key_performance_indicator), and a [Strategic Balanced Scorecard](https://github.com/joelparkerhenderson/strategic_balanced_scorecard).

* Team members can easily use scoreboards, dashboards, metrics, measurments, and similar data-driven tooling to run, upgrade, and verify IaC code. IT executive leadership can easily use rollup systems to prove IT-business capabilities and cost justifications.

* Code quality is consistently measured and tested using continuous delivery tooling, automated code quality vetting, scaling benchmarking, etc.

Examples:

* Many projects are one-button initiated, end-to-end, from sunrise to sunset. This can include Application Lifcycle Management (ALM),
Porfolio_ Pogramme_Project_Management (PPPM), best practices, maturity model matching, etc.

* IaC tooling emits metrics, which in turn are useful for Application Performance Monitoring (APM), synthetic monitoring, debugging, and capability growth planning.

How to improve:

* Technical: improve code so it's suitable for mainstream usage. This includes thorough test coverage for corner cases, failure modes, chaos interruptions, outage mitigations.

* Social: Plan IaC in terms of long-term management and mainstream usage, including roadmaps for lifecycle management, funding management, communication management, value stream mapping, and governance management.


## Level 5: Optimizing

* Level 5 is Optimizing, Orchestrating, Ongoing, Opportunity-oriented, Organization-wide Usage.

* Infrastructure research and development is funded to create new products and services, and also new business opportunities.

* Code quality is consistently able evolve, and welcomes contributions, discussions, and usage by the entire organization, and potentially its partners, vendors, customers, and the public.

Examples:

* Amazon creating AWS, Google creating GCS, Facebook creating React, Netflix creating many open source projects.

* Orchestrating with tools such as Kubernetes,

How to improve:

* Create code that inspires people to grow more IaC capabilities. This includes publicizing the code, such as blogging about it, creating help channels for it, and teaching how to use it.

* Use IT to drive strategic opportunities, such as investments in companies, products, and people.
