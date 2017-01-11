# Data Center Automation Maturity Model by Xebia

Credit: https://www.xebia.com/datacenter-automation

<table>

<tr>
<th>Area</th>
<th>Level 0<br>Not started</th>
<th>Level 1<br>Beginner</th>
<th>Level 2<br>Basic</th>
<th>Level 3<br>Intermediate</th>
<th>Level 4<br>Advanced</th>
<th>Level 5<br>Expert</th>
</tr>

<tr>
<th>Security and Compliance</th>
<td>No formal process for security around compliance.</td>
<td>Periodic patch rounds of OS packages.</td>
<td>No shared accounts. Policies defined. Up to date components.</td>
<td>Full audit trail; policies periodically validated.
<td>Fully automated security and compliance checks.
<td>Full insight into and control of security and compliance risks.</td>
</tr>

<tr>
<th>Operational Management</th>
<td>Order new hardware after systems run out of capacity.</td>
<td>Order new hardware when more capacity requested; hardware is project specific.</td>
<td>Hardware capacity shared among projects.</td>
<td>Periodic checks of available and used capacity.</td>
<td>Cost allocated per use; detection of under-used components.</td>
<td>Fully automated insight into capacity, cost, business value and operational burden.</td>
</tr>

<tr>
<th>Resiliency</th>
<td>Multiple single points of failure; repaired manually.</td>
<td>Backup/restore procedures validated periodically.</td>
<td>Critical components are redundant.</td>
<td>Backup/restore procedures are automated and validated frequently.</td>
<td>All components are redundant.</td>
<td>Auto-healing.</td>
<td>Planned and unplanned, automated resiliency test; predictive autoscaling.</td>
</tr>

<tr>
<th>Observability</th>
<td>No monitoring and logging; end users notice downtime first.</td>
<td>Logging available via Ops. Basic monitoring for platform components.</td>
<td>Monitoring available via dashboards. Alerts go to centralized Ops team.</td>
<td>Logging available via self-service for every product team.</td>
<td>Configurable alerts and custom dashboards for product teams.</td>
<td>Custom metrics. Product teams configure alerts based on custom events.</td>
</tr>

<tr>
<th>Provisioning</th>
<td>No procedures, no automation; all changes performed manually and according to operator's personal insight.</td>
<td>Standardized procedures; basic scripts.</td>
<td>Provisioning using standard configuration management tools.</td>
<td>No manual changes; full configuration management.</td>
<td>Immutable infrastructure.</td>
<td>Infrastructure as code.</td>
</tr>

<tr>
<th>Data Center Delivery</th>
<td>No tools; no documentation.</td>
<td>Standardized procedures; people trained to execute.</td>
<td>Changes lab-tested before applied.</td>
<td>Features delivered in small iterations.</td>
<td>Automated tests for most components.</td>
<td>Continuous delivery of all infrastructure components.</td>
</tr>

<tr>
<th>Production Team Autonomy</th>
<td>No formal process; make request through Ops and hope for eventual delivery.</td>
<td>Standardized request forms picked up whenever Ops get around to it.</td>
<td>Standardized requests; completed in under two weeks.</td>
<td>Partial self-service for basic features.</td>
<td>Self-service portal with graphical UI.</td>
<td>Full self-service with graphical UI and APIs.</td>
</tr>

</table>

