# Agile Maturity Model by ThoughtWorks

See https://info.thoughtworks.com/rs/thoughtworks2/images/agile_maturity_model.pdf

<table>

<tr>
<th>Practice</th>
<th>Build management and continuous integration</th>
<th>Environments and deployment</th>
<th>Release management and compliance</th>
<th>Testing</th>
<th>Data management</th>
</tr>

<tr>

<th>Level 3<br>Optimizing:<br>Focus on process improvement</th>

<td>
<p>Teams regularly meet to discuss integration problems.</p>
<p>Teams resolve problems with automation, fast feedback, and better visibility.</p>
</td>

<td>
<p>All environments managed effectively.</p>
<p>Provisioning fully automated.</p>
<p>Virtualization used if appropriate.</p>
</td>

<td>
<p>Operations and delivery teams regularly collaborate to manage risks and reduce cycle time.</p>
</td>

<td>
<p>Production rollbacks rare.</p>
<p>Defects found and fixed immediately.</p>
</td>

<td>
<p>Release-to-release feedback loop of database performance and deployment process.</p>
</td>

</tr>

<tr>

<th>Level 2<br>Quantitatively managed:<br>Process measured and controlled</th>

<td>
<p>Build metrics gathered, made visible, and acted on.</p>
<p>Builds are not left broken.</p>
</td>

<td>
<p>Orchestrated deployments managed.</p>
<p>Release a rollback processes tested.</p>
</td>

<td>
<p>Environment and application health monitored and proactively managed.</p>
<p>Cycle time monitored.</p>
</td>

<td>
<p>Quality metrics and trends tracked.</p>
<p>Non-functional requirements defined and measured.</p>
</td>

<td>
<p>Database upgrades and rollbacks testing with every deployment.</p>
<p>Database performance monitored and optimized.</p>
</td>

</tr>

<tr>

<th>Level 1<br>Consistent:<br>Automated processes applied across whole application lifecycle management</th>

<td>
<p>Automated build and test cycle every time a change is committed.</p>
<p>Dependencies managed.</p>
<p>Re-use of scripts and tools.</p>
</td>

<td>
<p>Fully automated, self-service push-button process for deploying software.</p>
<p>Same process to deploy to every environment.</p>
</td>

<td>
<p>Change management and approvals process defined and enforced.</p>
<p>Regulatory and compliance conditions met.</p>
</td>

<td>
<p>Automated unit and acceptance tests, the latter written with testers.</p>
<p>Testing part of the development process.</p>
</td>

<td>
<p>Database changes performed automatically as part of the deployment processes.</p>
</td>

</tr>
<tr>

<th>Level 0<br>Repeatable:<br>Process documented and partly automated</th>

<td>
<p>Regular automated build and testing.</p>
<p>Any build can be re-created from source control using automated process.</p>
</td>

<td>
<p>Automated deployment to some environments.</p>
<p>Creation of new environments is cheap.</p>
<p>All configuration externalized/versioned.</p>
</td>

<td>
<p>Painful and infrequent, but reliable, releases.</p>
<p>Limited traceability from requirements to release.</p>
</td>

<td>
<p>Automated tests written as part of story development.</p>
</td>

<td>
<p>Changes to databases done with automated scripts versioned with application.</p>
</td>

</tr>
<tr>

<th>Level -1<br>Regressive:<br>Processes unrepeatable, poorly controlled, and reactive</th>

<td>
<p>Manual processes for building software.</p>
<p>No management of artifacts and reports.</p>
</td>

<td>
<p>Manual process for deploying software.</p>
<p>Environment-specific binaries.</p>
<p>Environments provisioned manually.</p>
</td>

<td>
<p>Infrequent and unreliable releases.</p>
</td>

<td>
<p>Manual testing after development.</p>
</td>

<td>
<p>Data migrations unversioned and performed manually.</p>
</td>

</tr>

</table>
