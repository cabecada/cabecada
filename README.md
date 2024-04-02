# Vijaykumar Jain
  - vijaykumar.tater@gmail.com
  - 9769545966
  - Mumbai, Maharashtra, India

## Executive Summary
Accomplished System Architect with over 13 years of hands-on experience managing large-scale databases, including those of 10s of 60TB scale. Proficient in designing and implementing robust monitoring and logging solutions to ensure optimal performance and reliability. Demonstrated expertise in building highly scalable architectures capable of handling substantial data volumes while maintaining seamless operations. Solid experience in facilitating ease of migration, upgrades, and incident management processes, ensuring minimal disruption and downtime. Adept at generating insightful reports to provide stakeholders with comprehensive visibility into system health and performance metrics. Proven track record of optimizing database environments for maximum efficiency and resilience in dynamic business landscapes.

## Skills:

* Systems Architecture               (General architecture meeting and discussions, making POCs in testlabs)  
* Reliability Engineering            (uptime, fault injection and tolerance, upgrades, disaster recovery)
* Observability Tools                (e.g., Graphite, Prometheus, Grafana)
* Logging Tools                      (e.g ELK, pgbadger)
* Scalability Planning               (loose coupling, scatter gather in parallel to avoid cross node latency)
* Automation                         (CI/CD pipelines)
* Containerization                   (Docker, Mesos)
* Configuration Management           (Puppet, Rex, Ansible, TheForeman)
* Databases                          (PostgreSQL, MongoDB)
* Virtualisation                     (VMware vSphere)
* FileSystems                        (ext4, zfs)
* OperatingSystems                   (Ubuntu, Redhat, Gentoo)
* Backup and Recovery Strategies     (FileSystem Snapshots, logical backups using pgbackrest of 28TB dbs)
* Troubleshooting and Debugging      (perf, flamegraph, gdb) 
* Quick Learner                      (opensource support for postgresql, pocs, ask questions on slack channels)  

### PostgreSQL DBRE at Adjust
#### May 2022 – Jan 2023

Key Responsibilities and Achievements:
- Provided expert support for PostgreSQL databases ranging from 10TB to 60TB in size, 100s in node scale, ensuring high availability and optimal performance on bare metal servers.
- Implemented robust failover strategies and managed seamless upgrades for PostgreSQL clusters, minimizing downtime and ensuring continuous service delivery.
- Implemented Point-in-Time Recovery (PITR) and backup solutions using pgBackRest, ensuring data integrity and facilitating quick recovery in case of failures.
- Proactively tracked and remediated PostgreSQL page corruption issues by leveraging in-depth knowledge of page geometry.
- Optimized storage configurations on MDRAID (ext4) and ZPool (ZFS), tuning and monitoring for maximum performance and reliability.
- Configured, tuned, and monitored pgBouncer for efficient connection pooling, both on the client and server sides.
- Implemented table partitioning using pg_partman, enhancing query performance and manageability.
- Designed and implemented sharding solutions using consistent hashing and range-based sharding techniques, leveraging foreign data wrappers (FDW).
- Installed and configured various PostgreSQL extensions, including pg_repack, pg_partman, and parquet_fdw, to enhance functionality and performance.
- Utilized parquet_fdw to query Parquet files using SQL, optimizing PostgreSQL servers for large OLAP queries in complex setups.
- Investigated the use of DuckDB for querying parquet_fdw as part of ongoing performance optimization efforts.
- Managed PostgreSQL replication setups, including streaming, cascading, and logical replication, ensuring data consistency and availability across distributed environments.
- Collaborated Remotely with teams in Japan, Germany and India.


### Infrastructure SRE at Opentable
#### Jun 2016 – Nov 2019
Key Responsibilities and Achievements:
- Orchestrated the deployment and management of containerized applications using Apache Mesos and Docker, ensuring efficient resource utilization and scalability.
- Leveraged Singularity as the orchestrator to automate the scheduling and execution of containerized workloads, optimizing resource allocation and workload distribution.
- Implemented service discovery mechanisms to facilitate communication between applications running in containerized environments, ensuring seamless interaction and scalability.
- Engineered fault tolerance mechanisms to maintain application availability, automatically spawning additional instances on other servers in case of server failures.
- Spearheaded canary deployments and feature flag implementations to test breaking changes and new features in production environments, minimizing risks and ensuring smooth rollouts.
- Collaborated with development teams to annotate dashboards with relevant information about changes, enabling effective monitoring and analysis of performance impacts.
- Led the management and optimization of PostgreSQL and Redis clusters across CI/UAT/Prod environments, ensuring high availability, scalability, and performance.
- Architected and implemented Redis support for high availability (HA) and sharding, utilizing industry best practices and Redis Sentinel for failover automation.
- Integrated Kafka into the ELK (Elasticsearch, Logstash, Kibana) architecture to handle high-volume log ingestion, providing real-time analytics and visualization capabilities.
- Developed standardized logging templates for applications, ensuring consistency and compatibility across various services, and used Filebeat for log shipping to Logstash via Kafka.
- Designed and implemented a standardized metrics template for developers to monitor system health and performance, leveraging tools like Graphite, Prometheus, and Grafana for visualization and analysis.
- Established CI/UAT/Prod environments with uniform configurations and deployment processes, facilitating early detection of deployment issues and streamlining the release pipeline.
- Collaborated with development teams to integrate logging and metrics templates into applications, enabling developers to create standardized dashboards for monitoring and troubleshooting.
- Provided mentorship and guidance to junior team members on best practices for system architecture, deployment automation, and monitoring strategies.

### Infrastructure Engineer at Nomura
#### Sep 2011 – May 2016
Key Responsibilities and Achievements:

- Developed a tool (frontend and backend API) to migrate multiple LDAP databases into one, creating a Virtual Interface for reading from multiple sources and writing to a single database.
- Designed a comprehensive JIRA workflow for Puppet development, ensuring smooth collaboration and task management for the team.
- Practiced Test Driven Development (TDD) using Puppet, RSpec, ServerSpec, Beaker, RVM, and Git, ensuring high-quality code and reliable infrastructure configurations.
- Led the Proof of Concept (POC) implementation of GitLab for Source Code Management (SCM) and facilitated its successful transition to production.
- Established Continuous Integration for Redhat Satellite 6 using Jenkins, improving deployment automation and efficiency.
- Developed a customized command-line interface (CLI) in Python for using Pulp (Open Source Software) to manage and deploy RPM packages, replacing legacy solutions.
- Created RPM packages using the fpm tool, simplifying software distribution and installation processes.
- Automated the existing OS build process using autotest, reducing manual effort and ensuring consistency.- 
- Implemented SSL for secure communication in web-based applications like GitLab and Pulp within the organization.
- Actively participated in sysadmin activities including provisioning and building Operating Systems, Network Boot from consoles, KVM, Vagrant, vSphere, and Kerberos.

### Senior Software Engineer at Bank of America
#### Nov 2009 – Sep 2011
Key Responsibilities and Achievements:

- First hire in India to enable across the pond support for tick data systems.
- I was able to convert 90% of manual email monitoring to Geneos Monitoring System thereby reducing clutter and executive dashboards for system health monitoring
- Implemented Perl Best Practices (PBP) to enhance code maintainability and readability, utilizing Moose and Moosex Modules to support PBP standards.
- Developed a solution for maintaining efficient tick file archives across multiple regions, minimizing redundancy and improving data management.
- Analyzed system crashes using core dumps and debugging tools such as strace, truss, pstack, and gdb, facilitating efficient issue resolution.
- Implemented real-time validation for Vhayu and XMIM tick level data, enabling immediate alerting on level breaches or bad data.
- Perl Moose framework for ETL automation reading data from xmim, Sybase, xml feeds on the internet.

### Associate at Oracle Financial Services Software LTD
#### Sep 2007 – Nov 2009
Key Responsibilities and Achievements:

- follow the sun support and maintenance of scripts for tools like Risk Management tools like Imagine and other inhouse systems for risk projections.
- perl / sybase / solaris / bash
  
