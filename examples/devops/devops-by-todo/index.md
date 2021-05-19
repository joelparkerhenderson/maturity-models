# DevOps by TODO

See https://github.com/ramyrams/DevOps

Credit: 
https://camo.githubusercontent.com/bda83d076818b865aa6c9b64aa055d789d1d1580/687474703a2f2f626c6f672e6172756e67757074612e6d652f77702d636f6e74656e742f75706c6f6164732f323031352f30322f636f6e74696e756f75732d64656c69766572792d6d617475726974792d6d6f64656c2d76312e302d31303234783733342e706e67

<table>

<tr>

<th></th>
<th>Initial</th>
<th>Managed</th>
<th>Defined</th>
<th>Quantitatively management</th>
<th>Optimizing</th>

</tr><tr>

<th>Culture & organization</th>

<td>
<ul>
<li>Teams organzized based on plaftform/technology
<li>Defined and documented processes
</ul>
</td>

<td>
<ul>
<li>One backlog per team
<li>Adopt agile methodologies
<li>Remove team boundaries
</ul>
</td>

<td>
<ul>
<li>Extended team collaboration
<li>Remove boundary de/ops
<li>Common process for all changes
</ul>
</td>

<td>
<ul>
<li>
<li>Cross-team continuous improvement
<li>Teams responsible all the way to production
</ul>
</td>

<td>
<ul>
<li>Cross functional teams
</ul>
</td>

</tr><tr>

<th>Build & deploy</th>

<td>
<ul>
<li>Centralized version control
<li>Automated build scripts
<li>No management of artifacts
<li>Manual deployment
<li>Environments are manually provisioned
</ul>
</td>

<td>
<ul>
<li>Polling CI builds
<li>Any build can be re-created from source control
<li>Management of build artifacts
<li>Automated deployment scripts
<li>Automated provisioning of environments
</ul>
</td>

<td>
<ul>
<li>Commit hook CI builds
<li>Build fails if quality is not met (code analysis, performance, etc.)
<li>Push-button deployment of any releasable artifact to any environment
</ul>
</td>

<td>
<ul>
<li>Team prioritizes keeping codebase deployable over doing new work
<li>Builds are not left broken
<li>Orchestrated deployments
<li>Blue/green deployments
</ul>
</td>

<td>
<ul>
<li>Zero-touch continuous deployments
</ul>
</td>

</tr><tr>

<th>Release</th>

<td>
<ul>
<li>Infrequent & unreliable releases
<li>Manual process
</ul>
</td>

<td>
<ul>
<li>Painful infrequent but reliable releases
</ul>
</td>

<td>
<ul>
<li>Infrequent but fully automated and reliable releases in any environment
</ul>
</td>

<td>
<ul>
<li>Frequent fully-automated releases
<li>Deployment disconnected from release
<li>Canary releases
</ul>
</td>

<td>
<ul>
<li>No rollbacks; always roll forward
</ul>
</td>

</tr><tr>

<th>Data management</th>

<td>
<ul>
<li>Data migrations are performed manually, with no scripts
</ul>
</td>

<td>
<ul>
<li>Data migrations use versioned scrips, performed manually
</ul>
</td>

<td>
<ul>
<li>Automated and versioned changes to datastores
</ul>
</td>

<td>
<ul>
<li>Changes to datastores automatically performed as part of the deployment processs
</ul>
</td>

<td>
<ul>
<li>Automatic datastore changes and rollbacks, tested with every deployment
</ul>
</td>

</tr><tr>

<th>Test & verification</th>

<td>
<ul>
<li>Automated unit tests
<li>Separate test environment
</ul>
</td>

<td>
<ul>
<li>Automatic integration tests
<li>Static code analysis
<li>Test coverage analysis
</ul>
</td>

<td>
<ul>
<li>Automatic functional tests
<li>Manual performance tests and security tests
</ul>
</td>

<td>
<ul>
<li>Fully automatic acceptance tests
<li>Automatic performance tests and security tests
<li>Manual exploratory testing based on risk-based testing analysis
</ul>
</td>

<td>
<ul>
<li>Verify expected business value
<li>Defects found and fixed immediately (roll forward)
</ul>
</td>

</tr><tr>

<th>Information &reporting</th>

<td>
<ul>
<li>Baseline performance metrics
<li>Manual reporting
<li>Visible to report runner
</ul>
</td>

<td>
<ul>
<li>Measure the process
<li>Automatic reporting
<li>Visible to team
</ul>
</td>

<td>
<ul>
<li>Automatic generation of release notes
<li>Pipeline traceability
<li>Reporting history
<li>Visible to cross-silio
</ul>
</td>

<td>
<ul>
<li>Report trend analysis
<li>Real-time graphs on deployment pipeline metrics
</ul>
</td>

<td>
<ul>
<li>Dynamic self-service of information
<li>Customizable dashboards
<li>Cross-reference across organizational boudaries
</ul>
</td>

</tr>

</table>
