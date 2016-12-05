# Agile DevOps Maturity Model by Hewlett Packard Enterprise (HPE)

See [Building an integrated Agile/DevOps Maturity Model showing how to progress](
https://community.hpe.com/t5/Cloud-Source/Building-an-integrated-Agile-DevOps-Maturity-Model-showing-how/ba-p/6796526)

<table>

<tr style="vertical-align:top">
<th></th>
<th>Organization</th>
<th>Teamwork</th>
<th>Build Management Continuous Integration</th>
<th>Continuous Delivery and Deployment</th>
<th>Lifecycle Management & Compliance</th>
<th>Testing</th>
<th>Data & Integration Management</th>
</tr>

<tr style="vertical-align:top">

<th>Optimized</th>

<td style="vertical-align:top">
<p>Lean and agile are part of the organizational culture.</p>
<p>Continuous learning and optimization of the work processess.</p>
</td>

<td style="vertical-align:top">
<p>Effective knowledge sharing.</p>
<p>Individual empowerment.</p>
</td>

<td style="vertical-align:top">
<p>Teams regularly meet to discuss integration problems.</p>
<p>Teams resolve problems with automation, fast feedback, and better visibility.</p>
</td>

<td style="vertical-align:top">
<p>Environments are managed effectively.</p>
<p>Provisioning is fully automated.</p>
<p>Standard topologies are available for common components.</p>
</td>

<td style="vertical-align:top">
<p>Full portfolio and lifecycle management are in place, and integrate user requirements, development, testing, staging, and production.</p>
</td>

<td style="vertical-align:top">
<p>Testing is fully automated.</p>
<p>Production rollbacks are rare.</p>
<p>Defects are found and fixed immediately.</p>
</td>

<td style="vertical-align:top">
<p>Release-to-release feedback loop of database and ingration performance and deployment processes.</p>
</td>

</tr>

<tr style="vertical-align:top">

<th>Measured</th>

<td style="vertical-align:top">
<p>Communities of practice support agile habits and high maturity across the organization.</p>
<p>Measurement systems are in place to keep track of business value delivered.</p>
<p>Inefficiencies are identified and acted upon.</p>
</td>

<td style="vertical-align:top">
<p>Integrations among development teams, testing teams, and operations teams are implemented, even among teams in multiple countries.</p>
<p>Success is celebrated.</p>
<p>People are fully respected and recognized for their contributions.</p>
</td>

<td style="vertical-align:top">
<p>Build metrics are gathered, made visible, and acted upon.</p>
<p>Lessons are learned.</p>
<p>Continuous improvement is in place.</p>
</td>

<td style="vertical-align:top">
<p>Deployments are orchestrated and managed.</p>
<p>Release processes are tested.</p>
<p>Rollback processes are tested.</p>
</td>

<td style="vertical-align:top">
<p>Environmental health and application health are monitored and proactively managed.</p>
<p>Cycle times are monitored.</p>
</td>

<td style="vertical-align:top">
<p>Quality metrics and trends are tracked.</p>
<p>Non-functional requirements are defined and measured.</p>
</td>

<td style="vertical-align:top">
<p>Database upgrades and rollbacks are tested with every deployment.</p>
<p>Database performance is monitored and optimized.</p>
<p>Integration is performed by using message queues, enabling scale-up and scale-down.</p>
</td>

</tr>

<tr style="vertical-align:top">

<th>Defined</th>

<td style="vertical-align:top">
<p>Disciplined agile delivery processes and practices are implemented.</p>
<p>Continuous improvement is in place.</p>
<p>Appropriate governance is in place.</p>
</td>

<td style="vertical-align:top">
<p>Co-located development, testing, and operations teams are starting to work together towards a common goal.</p>
<p>Communications and feedback loops are initated across the whole supply chain.</p>
</td>

<td style="vertical-align:top">
<p>Every time a source code change is committed, an automated build and test cycle is performed.</p>
<p>Dependencies are managed.</p>
<p>Scripts and tools are re-usable.</p>
</td>

<td style="vertical-align:top">
<p>Software is deployed using a fully-automated, self-service process.</p>
<p>Same deployment process is used for every environment.</p>
</td>

<td style="vertical-align:top">
<p>Lean portforlio management.</p>
<p>Change management and approval processes are in place and enforced.</p>
</td>

<td style="vertical-align:top">
<p>Automated unit tests.</p>
<p>Automated acceptance tests.</p>
<p>Testing is part of the devleopment process.</p>
<p>Feedback loops are in place.</p>
<p>Continuous improvement is measured and managed.</p>
</td>

<td style="vertical-align:top">
<p>Databases and integrations are included in the deployment process.</p>
</td>

</tr>

<tr style="vertical-align:top">

<th>Managed</th>

<td style="vertical-align:top">
<p>The organization is starting to embrace agile habits within development.</p>
<p>Operations is still seen as separate.</p>
<p>Consistency across teams is variable.</p>
</td>

<td style="vertical-align:top">
<p>Some knowledge sharing activities get under way.</p>
<p>Teams are starting to communication within development.</p>
<p>Standard work practices are defined and mostly followed.</p>
</td>

<td style="vertical-align:top">
<p>Automation is implemented in the build phase and test phase, but is still siloed.</p>
<p>No central infrastructre in place.</p>
</td>

<td style="vertical-align:top">
<p>Deployment is partially automated to some environments.</p>
<p>Some environments can be provisioned automatically.</p>
<p>Some middleware and database components are provided centrally.</p>
</td>

<td style="vertical-align:top">
<p>Lifecycle management is painful and infrequent but releases are reliable.</p>
<p>There is limited traceability from requirement to release.</p>
<p>Quality is improving.</p>
</td>

<td style="vertical-align:top">
<p>Test scripts and test data are generated as part of the development process.</p>
<p>Test scripst and test data are used for automating some tests.</p>
</td>

<td style="vertical-align:top">
<p>Database changes are done through the use of automated scripts with versions associated to applications.</p>
<p>An Enterprise Application Integration bus is implemented to facilitate integration.</p>
</td>

</tr>

<tr style="vertical-align:top">

<th>Initial</th>

<td style="vertical-align:top">
<p>Development teams work in isolation, and use the tools, middleware, and components they deem most appropriate to deliver the work.</td>
</td>

<td style="vertical-align:top">
<p>Poor teamwork, ad-hoc communication & coordination.</p>
<p>No knowledge pool.</p>
<p>Little sharing.</p>
<p>Success achieved primarily through heroic individual efforts.</p>
</td>

<td style="vertical-align:top">
<p>Manual and reactive processes.</p>
<p>Little management of artifacts, documentation, and source code.</p>
<p>Uncontrolled.</p>
</td>

<td style="vertical-align:top">
<p>Software is deployed manually, using environment-specific binaries.</p>
<p>Environment is provisioned manually.</p>
</td>

<td style="vertical-align:top">
<p>Infrequent and unreliable releases.</p>
<p>Manual application lifecycle.</p>
<p>Software quality turns out to be variable.</p>
</td>

<td style="vertical-align:top">
<p>Manual testing.</p>
<p>No test scripts.</p>
<p>Typically done after development.</p>
</td>

<td style="vertical-align:top">
<p>Data migrations are performed manually.</p>
<p>Integration is ad-hoc and often point-to-point.</p>
</td>

</tr>

</table>
