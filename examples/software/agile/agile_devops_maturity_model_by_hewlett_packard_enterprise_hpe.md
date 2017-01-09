# Agile DevOps Maturity Model by Hewlett Packard Enterprise (HPE)

[Link to Google Forms Self Assessment](https://docs.google.com/forms/d/e/1FAIpQLSdIa65_t8ua6Er6B5r66huSfboJQtQriwDsgD9UDd68kRrrFw/viewform)

See [Building an integrated Agile/DevOps Maturity Model showing how to progress](
https://community.hpe.com/t5/Cloud-Source/Building-an-integrated-Agile-DevOps-Maturity-Model-showing-how/ba-p/6796526)

Contents:
* [Table of all items](#table)
* [Organization](#organization)
* [Teamwork](#teamwork)
* [Build management continuous integration](#build-management-continuous-integration)
* [Continuous delivery and deployment](#continuous-delivery-and-deployment)
* [Lifecycle management & compliance](#lifecycle-management-compliance)
* [Testing](#testing)
* [Data & integration management](#data-integration-management)

<h2><a name="table">Table of all items</a></h2>

<table>

<tr>
<th></th>
<th>Organization</th>
<th>Teamwork</th>
<th>Build Management Continuous Integration</th>
<th>Continuous Delivery and Deployment</th>
<th>Lifecycle Management & Compliance</th>
<th>Testing</th>
<th>Data & Integration Management</th>
</tr>

<tr>

<th>Optimized</th>

<td>
<p>Lean and agile are part of the organizational culture.</p>
<p>Continuous learning and optimization of the work processess.</p>
</td>

<td>
<p>Effective knowledge sharing.</p>
<p>Individual empowerment.</p>
</td>

<td>
<p>Teams regularly meet to discuss integration problems.</p>
<p>Teams resolve problems with automation, fast feedback, and better visibility.</p>
</td>

<td>
<p>Environments are managed effectively.</p>
<p>Provisioning is fully automated.</p>
<p>Standard topologies are available for common components.</p>
</td>

<td>
<p>Full portfolio and lifecycle management are in place, and integrate user requirements, development, testing, staging, and production.</p>
</td>

<td>
<p>Testing is fully automated.</p>
<p>Production rollbacks are rare.</p>
<p>Defects are found and fixed immediately.</p>
</td>

<td>
<p>Release-to-release feedback loop of database and integration performance and deployment processes.</p>
</td>

</tr>

<tr>

<th>Measured</th>

<td>
<p>Communities of practice support agile habits and high maturity across the organization.</p>
<p>Measurement systems are in place to keep track of business value delivered.</p>
<p>Inefficiencies are identified and acted upon.</p>
</td>

<td>
<p>Integrations among development teams, testing teams, and operations teams are implemented, even among teams in multiple countries.</p>
<p>Success is celebrated.</p>
<p>People are fully respected and recognized for their contributions.</p>
</td>

<td>
<p>Build metrics are gathered, made visible, and acted upon.</p>
<p>Lessons are learned.</p>
<p>Continuous improvement is in place.</p>
</td>

<td>
<p>Deployments are orchestrated and managed.</p>
<p>Release processes are tested.</p>
<p>Rollback processes are tested.</p>
</td>

<td>
<p>Environmental health and application health are monitored and proactively managed.</p>
<p>Cycle times are monitored.</p>
</td>

<td>
<p>Quality metrics and trends are tracked.</p>
<p>Non-functional requirements are defined and measured.</p>
</td>

<td>
<p>Database upgrades and rollbacks are tested with every deployment.</p>
<p>Database performance is monitored and optimized.</p>
<p>Integration is performed by using message queues, enabling scale-up and scale-down.</p>
</td>

</tr>

<tr>

<th>Defined</th>

<td>
<p>Disciplined agile delivery processes and practices are implemented.</p>
<p>Continuous improvement is in place.</p>
<p>Appropriate governance is in place.</p>
</td>

<td>
<p>Co-located development, testing, and operations teams are starting to work together towards a common goal.</p>
<p>Communications and feedback loops are initated across the whole supply chain.</p>
</td>

<td>
<p>Every time a source code change is committed, an automated build and test cycle is performed.</p>
<p>Dependencies are managed.</p>
<p>Scripts and tools are re-usable.</p>
</td>

<td>
<p>Software is deployed using a fully-automated, self-service process.</p>
<p>Same deployment process is used for every environment.</p>
</td>

<td>
<p>Lean portforlio management.</p>
<p>Change management and approval processes are in place and enforced.</p>
</td>

<td>
<p>Automated unit tests.</p>
<p>Automated acceptance tests.</p>
<p>Testing is part of the devleopment process.</p>
<p>Feedback loops are in place.</p>
<p>Continuous improvement is measured and managed.</p>
</td>

<td>
<p>Databases and integrations are included in the deployment process.</p>
</td>

</tr>

<tr>

<th>Managed</th>

<td>
<p>The organization is starting to embrace agile habits within development.</p>
<p>Operations is still seen as separate.</p>
<p>Consistency across teams is variable.</p>
</td>

<td>
<p>Some knowledge sharing activities get under way.</p>
<p>Teams are starting to communication within development.</p>
<p>Standard work practices are defined and mostly followed.</p>
</td>

<td>
<p>Automation is implemented in the build phase and test phase, but is still siloed.</p>
<p>No central infrastructre in place.</p>
</td>

<td>
<p>Deployment is partially automated to some environments.</p>
<p>Some environments can be provisioned automatically.</p>
<p>Some middleware and database components are provided centrally.</p>
</td>

<td>
<p>Lifecycle management is painful and infrequent but releases are reliable.</p>
<p>There is limited traceability from requirement to release.</p>
<p>Quality is improving.</p>
</td>

<td>
<p>Test scripts and test data are generated as part of the development process.</p>
<p>Test scripst and test data are used for automating some tests.</p>
</td>

<td>
<p>Database changes are done through the use of automated scripts with versions associated to applications.</p>
<p>An Enterprise Application Integration bus is implemented to facilitate integration.</p>
</td>

</tr>

<tr>

<th>Initial</th>

<td>
<p>Development teams work in isolation, and use the tools, middleware, and components they deem most appropriate to deliver the work.</td>
</td>

<td>
<p>Poor teamwork, ad-hoc communication & coordination.</p>
<p>No knowledge pool.</p>
<p>Little sharing.</p>
<p>Success achieved primarily through heroic individual efforts.</p>
</td>

<td>
<p>Manual and reactive processes.</p>
<p>Little management of artifacts, documentation, and source code.</p>
<p>Uncontrolled.</p>
</td>

<td>
<p>Software is deployed manually, using environment-specific binaries.</p>
<p>Environment is provisioned manually.</p>
</td>

<td>
<p>Infrequent and unreliable releases.</p>
<p>Manual application lifecycle.</p>
<p>Software quality turns out to be variable.</p>
</td>

<td>
<p>Manual testing.</p>
<p>No test scripts.</p>
<p>Typically done after development.</p>
</td>

<td>
<p>Data migrations are performed manually.</p>
<p>Integration is ad-hoc and often point-to-point.</p>
</td>

</tr>

</table>


<h2><a name="organization">Organization</a></h2>

1. Initial

  * Development teams work in isolation, and use the tools, middleware, and components they deem most appropriate to deliver the work.

2. Managed

  * The organization is starting to embrace agile habits within development.

  * Operations is still seen as separate.

  * Consistency across teams is variable.

3. Defined

  * Disciplined agile delivery processes and practices are implemented.

  * Continuous improvement is in place.

  * Appropriate governance is in place.

4. Measured

  * Communities of practice support agile habits and high maturity across the organization.

  * Measurement systems are in place to keep track of business value delivered.

  * Inefficiencies are identified and acted upon.

5. Optimized

  * Lean and agile are part of the organizational culture.

  * Continuous learning and optimization of the work processess.


<h2><a name="teamwork">Teamwork</a></h2>

1. Initial

  * Poor teamwork, ad-hoc communication & coordination.

  * No knowledge pool.

  * Little sharing.

  * Success achieved primarily through heroic individual efforts.

2. Managed

  * Some knowledge sharing activities get under way.

  * Teams are starting to communication within development.

  * Standard work practices are defined and mostly followed.

3. Defined

  * Co-located development, testing, and operations teams are starting to work together towards a common goal.

  * Communications and feedback loops are initated across the whole supply chain.

4. Measured

  * Integrations among development teams, testing teams, and operations teams are implemented, even among teams in multiple countries.

  * Success is celebrated.

  * People are fully respected and recognized for their contributions.

5. Optimized

  * Effective knowledge sharing.

  * Individual empowerment.


<h2><a name="build-management-continuous-integration">Build management continuous integration</a></h2>

1. Initial

  * Manual and reactive processes.

  * Little management of artifacts, documentation, and source code.

  * Uncontrolled.

2. Managed

  * Automation is implemented in the build phase and test phase, but is still siloed.

  * No central infrastructre in place.

3. Defined

  * Every time a source code change is committed, an automated build and test cycle is performed.

  * Dependencies are managed.

  * Scripts and tools are re-usable.

4. Measured

  * Build metrics are gathered, made visible, and acted upon.

  * Lessons are learned.

  * Continuous improvement is in place.

5. Optimized

  * Teams regularly meet to discuss integration problems.

  * Teams resolve problems with automation, fast feedback, and better visibility.


<h2><a name="continuous-delivery-and-deployment">Continuous delivery and deployment</a></h2>

1. Initial

  * Software is deployed manually, using environment-specific binaries.

  * Environment is provisioned manually.

2. Managed

  * Deployment is partially automated to some environments.

  * Some environments can be provisioned automatically.

  * Some middleware and database components are provided centrally.

3. Defined

  * Software is deployed using a fully-automated, self-service process.

  * Same deployment process is used for every environment.

4. Measured

  * Deployments are orchestrated and managed.

  * Release processes are tested.

  * Rollback processes are tested.

5. Optimized

  * Environments are managed effectively.

  * Provisioning is fully automated.

  * Standard topologies are available for common components.


<h2><a name="lifecycle-management-compliance">Lifecycle management & compliance</a></h2>

1. Initial

  * Infrequent and unreliable releases.

  * Manual application lifecycle.

  * Software quality turns out to be variable.

2. Managed

  * Lifecycle management is painful and infrequent but releases are reliable.

  * There is limited traceability from requirement to release.

  * Quality is improving.

3. Defined

  * Lean portforlio management.

  * Change management and approval processes are in place and enforced.

4. Measured

  * Environmental health and application health are monitored and proactively managed.

  * Cycle times are monitored.

5. Optimized

  * Full portfolio and lifecycle management are in place.

  * Management integrates user requirements, development, testing, staging, and production.


<h2><a name="testing">Testing</a></h2>

1. Initial

  * Manual testing.

  * No test scripts.

  * Typically done after development.

2. Managed

  * Test scripts and test data are generated as part of the development process.

  * Test scripst and test data are used for automating some tests.

3. Defined

  * Automated unit tests.

  * Automated acceptance tests.

  * Testing is part of the devleopment process.

  * Feedback loops are in place.

  * Continuous improvement is measured and managed.

4. Measured

  * Quality metrics and trends are tracked.

  * Non-functional requirements are defined and measured.

5. Optimized

  * Testing is fully automated.

  * Production rollbacks are rare.

  * Defects are found and fixed immediately.


<h2><a name="data-integration-management">Data & Integration Management</a></h2>

1. Initial

  * Data migrations are performed manually.

  * Integration is ad-hoc and often point-to-point.

2. Managed

  * Database changes are done through the use of automated scripts with versions associated to applications.

  * An Enterprise Application Integration bus is implemented to facilitate integration.

3. Defined

  * Databases and integrations are included in the deployment process.

4. Measured

  * Database upgrades and rollbacks are tested with every deployment.

  * Database performance is monitored and optimized.

  * Integration is performed by using message queues, enabling scale-up and scale-down.

5. Optimized

  * Release-to-release feedback loop of database and integration performance and deployment processes.
