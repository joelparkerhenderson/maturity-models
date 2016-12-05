# Agile DevOps Maturity Model by Hewlett Packard Enterprise (HPE)

See [Building an integrated Agile/DevOps Maturity Model showing how to progress](
https://community.hpe.com/t5/Cloud-Source/Building-an-integrated-Agile-DevOps-Maturity-Model-showing-how/ba-p/6796526)

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
<ul>
<li>Lean and agile are part of the organizational culture.</li>
<li>Continuous learning and optimization of the work processess.</li>
</ul>
</td>

<td>
<ul>
<li>Effective knowledge sharing.</li>
<li>Individual empowerment.</li>
</ul>
</td>

<td>
<ul>
<li>Teams regularly meet to discuss integration problems.</li>
<li>Teams resolve problems with automation, fast feedback, and better visibility.</li>
</ul>
</td>

<td>
<ul>
<li>Environments are managed effectively.</li>
<li>Provisioning is fully automated.</li>
<li>Standard topologies are available for common components.</li>
</ul>
</td>

<td>
<ul>
<li>Full portfolio and lifecycle management are in place, and integrate user requirements, development, testing, staging, and production.</li>
</ul>
</td>

<td>
<ul>
<li>Testing is fully automated.</li>
<li>Production rollbacks are rare.</li>
<li>Defects are found and fixed immediately.</li>
</ul>
</td>

<td>
<ul>
<li>Release-to-release feedback loop of database and ingration performance and deployment processes.</li>
</ul>
</td>

</tr>

<tr>

<th>Measured</th>

<td>
<ul>
<li>Communities of practice support agile habits and high maturity across the organization.</li>
<li>Measurement systems are in place to keep track of business value delivered.</li>
<li>Inefficiencies are identified and acted upon.</li>
</ul>
</td>

<td>
<ul>
<li>Integrations among development teams, testing teams, and operations teams are implemented, even among teams in multiple countries.</li>
<li>Success is celebrated.</li>
<li>People are fully respected and recognized for their contributions.</li>
</ul>
</td>

<td>
<ul>
<li>Build metrics are gathered, made visible, and acted upon.</li>
<li>Lessons are learned.</li>
<li>Continuous improvement is in place.</li>
</ul>
</td>

<td>
<ul>
<li>Deployments are orchestrated and managed.</li>
<li>Release processes are tested.</li>
<li>Rollback processes are tested.</li>
</ul>
</td>

<td>
<ul>
<li>Environmental health and application health are monitored and proactively managed.</li>
<li>Cycle times are monitored.</li>
</ul>
</td>

<td>
<ul>
<li>Quality metrics and trends are tracked.</li>
<li>Non-functional requirements are defined and measured.</li>
</ul>
</td>

<td>
<ul>
<li>Database upgrades and rollbacks are tested with every deployment.</li>
<li>Database performance is monitored and optimized.</li>
<li>Integration is performed by using message queues, enabling scale-up and scale-down.</li>
</ul>
</td>

</tr>

<tr>

<th>Defined</th>

<td>
<ul>
<li>Disciplined agile delivery processes and practices are implemented.</li>
<li>Continuous improvement is in place.</li>
<li>Appropriate governance is in place.</li>
</ul>
</td>

<td>
<ul>
<li>Co-located development, testing, and operations teams are starting to work together towards a common goal.</li>
<li>Communications and feedback loops are initated across the whole supply chain.</li>
</ul>
</td>

<td>
<ul>
<li>Every time a source code change is committed, an automated build and test cycle is performed.</li>
<li>Dependencies are managed.</li>
<li>Scripts and tools are re-usable.</li>
</ul>
</td>

<td>
<ul>
<li>Software is deployed using a fully-automated, self-service process.</li>
<li>Same deployment process is used for every environment.</li>
</ul>
</td>

<td>
<ul>
<li>Lean portforlio management.</li>
<li>Change management and approval processes are in place and enforced.</li>
</ul>
</td>

<td>
<ul>
<li>Automated unit tests.</li>
<li>Automated acceptance tests.</li>
<li>Testing is part of the devleopment process.</li>
<li>Feedback loops are in place.</li>
<li>Continuous improvement is measured and managed.</li>
</ul>
</td>

<td>
<ul>
<li>Databases and integrations are included in the deployment process.</li>
</ul>
</td>

</tr>

<tr>

<th>Managed</th>

<td>
<ul>
<li>The organization is starting to embrace agile habits within development.</li>
<li>Operations is still seen as separate.</li>
<li>Consistency across teams is variable.</li>
</ul>
</td>

<td>
<ul>
<li>Some knowledge sharing activities get under way.</li>
<li>Teams are starting to communication within development.</li>
<li>Standard work practices are defined and mostly followed.</li>
</ul>
</td>

<td>
<ul>
<li>Automation is implemented in the build phase and test phase, but is still siloed.</li>
<li>No central infrastructre in place.</li>
</ul>
</td>

<td>
<ul>
<li>Deployment is partially automated to some environments.</li>
<li>Some environments can be provisioned automatically.</li>
<li>Some middleware and database components are provided centrally.</li>
</ul>
</td>

<td>
<ul>
<li>Lifecycle management is painful and infrequent but releases are reliable.</li>
<li>There is limited traceability from requirement to release.</li>
<li>Quality is improving.</li>
</ul>
</td>

<td>
<ul>
<li>Test scripts and test data are generated as part of the development process.</li>
<li>Test scripst and test data are used for automating some tests.</li>
</ul>
</td>

<td>
<ul>
<li>Database changes are done through the use of automated scripts with versions associated to applications.</li>
<li>An Enterprise Application Integration bus is implemented to facilitate integration.</li>
</ul>
</td>

</tr>

<tr>

<th>Initial</th>

<td>
<ul>
<li>Development teams work in isolation, and use the tools, middleware, and components they deem most appropriate to deliver the work.</ul>
</td>
</ul>
</td>

<td>
<ul>
<li>Poor teamwork, ad-hoc communication & coordination.</li>
<li>No knowledge pool.</li>
<li>Little sharing.</li>
<li>Success achieved primarily through heroic individual efforts.</li>
</ul>
</td>

<td>
<ul>
<li>Manual and reactive processes.</li>
<li>Little management of artifacts, documentation, and source code.</li>
<li>Uncontrolled.</li>
</ul>
</td>

<td>
<ul>
<li>Software is deployed manually, using environment-specific binaries.</li>
<li>Environment is provisioned manually.</li>
</ul>
</td>

<td>
<ul>
<li>Infrequent and unreliable releases.</li>
<li>Manual application lifecycle.</li>
<li>Software quality turns out to be variable.</li>
</ul>
</td>

<td>
<ul>
<li>Manual testing.</li>
<li>No test scripts.</li>
<li>Typically done after development.</li>
</ul>
</td>

<td>
<ul>
<li>Data migrations are performed manually.</li>
<li>Integration is ad-hoc and often point-to-point.</li>
</ul>
</td>

</tr>

</table>
