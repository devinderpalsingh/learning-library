# Introduction
## About this Workshop
The Database Configuration and Compliance Management is a fully functional Oracle Enterprise Manager environment configured to run predefined use cases against multiple Oracle Database targets:
- This Workshop VM comes preinstalled with Enterprise Manager 13.5 and Oracle Database targets - 18.3, 18.8, 18.10, 19.3 and 19.10
- It's easy and quick to deploy with everything starting automatically in under 20 minutes

*Estimated Time:* 60 minutes

## About Oracle Enterprise Manager
Oracle Enterprise Manager is Oracle’s on-premise management platform that provides a single dashboard to manage all of your Oracle deployments, in your data center or in the cloud. Through deep integration with Oracle’s product stack, it provides market-leading management and automation support for Oracle applications, databases, middleware, hardware, and engineered systems

Join Oracle's ***Wim Coekaerts***, *senior vice president of software development*, as he describes key innovations delivered in Oracle Enterprise Manager to help customers easily migrate their databases to the cloud and simplify management of hybrid IT environments

[](youtube:MZJQx6MuHA0)


#### Applicable Enterprise Manager Management Packs
Labs under this workshop are covered by the following Management Pack.
- Database Lifecycle Management Pack

### Content
Oracle Database Compliance and Drift Management including configuration and security compliance management of managed targets. The following are covered in this workshop:
- Analyze, Increase standardization, reduce number of different configuration sets
- Execute a one-time comparison to compare the latest reference configuration to one or more targets to determine the configuration differences
- Continuous drift monitoring of multiple targets against a reference target for initialization parameters using customized configuration monitoring template
- Run a review aggregated security compliance framework and standard for Oracle Database 12c and Oracle Host targets
- Host security compliance using custom compliance standard

### Additional Workshop Supported Use Cases

For additional Enterprise Manager use cases, see below and visit [LiveLabs](http://bit.ly/golivelabs) for the details.
#### 1. Database Lifecycle Automation
-	Create a Pluggable Database (PDB)
-	Un-plug/Plug an existing Pluggable Database
-	Clone an existing Pluggable Database
-	Run Compliance Management for Pluggable Database
-	Self- service to request a PDB using PDBaaS
-	Administrative Setup for PDBaaS (Private Cloud)- Review only

#### 2. Find, Fix, Validate
- View unified Database Performance via Performance Hub
- Use Real-time Database Operations Monitoring to view long running database tasks
- Identify Top SQL in a PDB and tune it using SQL Tuning Advisor
- Use SQL Performance Analyzer Optimizer to gather statistics for validation
- Use Database Workload Replay to run real workload against your changes for additional validation

#### 4. Database Fleet Maintenance - Upgrade
* Detect Configuration Pollution
* Upgrade Oracle DB Software at scale with minimal downtime
    - All Pluggable Databases in that Container Database will automatically get upgraded
    - Cleanup

#### 5. Job System Automation
* Understand how to create an OS Command Job
* Create a SQL command Job
* Create Database Backup Job using Wizard

#### 6. Real Application Testing
* Run SQL Performance Analyzer to review SQL performance before 19c Upgrade
* Capture workload of 18c Database
* Run Database Replay of 18c Database Workload in 19c Database
* Run Consolidation Replay in 2 separate Pluggable Databases

#### 7. Enterprise Monitoring
- Explore Enterprise Summary page and drill down to see a list of down targets
- Triage unassigned incidents from Incident Manager and acknowledge then assign an incident
- Change the Warning and Critical threshold of a metric from Metric and Collection Settings page. Go to the All Metrics page and review the metric in context of the thresholds
- Create a new Corrective Action and associate it with a metric
- Test a Metric Extension on a target to see the results then deploy the same Metric Extension to multiple targets
- Create a Monitoring Template from a Database Instance target and deploy the Monitoring Template to other Database Instance targets to standardize monitoring settings across the enterprise
- View the hierarchy of an existing Administrator Group
- Review out-of-the-box incident rules shipped with Enterprise Manager

#### 8. Deploy and Manage Oracle Databases with Ansible and Enterprise Manager
- Install and configure Ansible to work with Oracle Enterprise Manager 13c
- Review Oracle Enterprise Manager DBaaS setup for Pluggable Databases
- Provision, resize, shutdown, start and delete a Pluggable Database using Ansible playbooks and EM's DBaaS capabilities

## Learn More
Managing Your Hybrid Database Fleet
[](youtube:TUaAweMX3S4)

Drive Your Autonomous Future with Oracle Enterprise Manager
[](youtube:7khTglg0_3g)

- [Enterprise Manager Cloud Control Solutions](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcon/enterprise-manager-management-focus-areas.html#GUID-7F3BF18C-97DF-44BC-8BB7-6A864AF1A150)
- [Enterprise Manager Cloud Control 13.5 Getting Started](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/index.html)
- [Architecture of Enterprise Manager Cloud Control](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcon/enterprise-manager-cloud-control-architecture.html#GUID-1A384373-7CD5-434D-9939-874E940CBF21)
- [Installation and Upgrade](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/install.html)
- [Enterprise Manager Blogs](https://blogs.oracle.com/oem/)
- [Enterprise Manager Videos](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/videos.html)
- [Enterprise Manager Licensing Guide](https://www.oracle.com/pls/topic/lookup?ctx=en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5&id=OEMLI-GUID-7B2095D3-4E88-4346-9566-638219FF1130)
- [oracle.com/enterprisemanager](https://www.oracle.com/enterprise-manager/)


## Acknowledgements
- **Author** - Rene Fontcha, Master Principal Solutions Architect, NA Technology
- **Contributors** - Dave Le Roy, Harish Niddagatta - Enterprise Manager Product Management
- **Last Updated By/Date** - Rene Fontcha, LiveLabs Platform Lead, NA Technology, February 2022
