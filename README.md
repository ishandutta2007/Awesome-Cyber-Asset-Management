# Awesome-Cyber-Asset-Management

## Top Cyber Asset Management Tools Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Cyber Asset Management, IT Asset Discovery, Asset Inventory, CMDB, Infrastructure Discovery & Cybersecurity Asset Intelligence*  
**Last updated: August 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cyber Asset Management**. These tools discover, inventory, classify, enrich, monitor, and manage an organization's hardware, software, endpoints, cloud resources, network infrastructure, identities, applications, and other technology assets.

**Examples** include Axonius, Armis, RunZero, Noetic Cyber, Device42, Lansweeper, ServiceNow Discovery, Tanium, Forescout, Qualys CyberSecurity Asset Management, and other cyber asset-management and infrastructure-discovery platforms.

Cyber Asset Management sits at the intersection of **Cyber Asset Attack Surface Management (CAASM), Cybersecurity Asset Management (CSAM), IT Asset Management (ITAM), Configuration Management Databases (CMDB), IT Discovery, Network Discovery, Endpoint Management, Vulnerability Management, Exposure Management, Cloud Asset Inventory, Software Asset Management (SAM), Infrastructure Observability, and Security Operations**.

**Open-source emphasis**: This repository heavily emphasizes open-source software that can be self-hosted and used as building blocks for cyber asset-management systems. The open-source ecosystem is considerably more fragmented than the commercial CAASM market, so this list includes both dedicated asset-management platforms and specialized open-source components for discovery, inventory, network mapping, endpoint telemetry, configuration management, CMDB, IPAM/DCIM, cloud inventory, and security visibility.

Important open-source building blocks include **GLPI, Snipe-IT, Ralph, OCS Inventory NG, Open-AudIT, CMDBuild, iTop, NetBox, Device42 alternatives, osquery, Fleet, Wazuh, Zabbix, Nmap, Masscan, Zeek, and CloudQuery**.

**Important distinction**: Most open-source projects below are **not one-to-one replacements** for Axonius, Armis, Noetic, or ServiceNow Discovery. Commercial cyber asset-management products typically combine discovery connectors, asset normalization, identity resolution, relationship graphs, vulnerability data, SaaS/cloud integrations, risk analytics, and security workflows. Open-source systems generally provide individual layers that can be combined into a complete platform.

A particularly effective open-source architecture combines **network discovery + endpoint telemetry + cloud inventory + CMDB/IPAM + vulnerability intelligence + asset normalization + a search/graph layer**.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Cyber Asset Management Stack](#open-source-cyber-asset-management-stack)
- [Important Cyber Asset Management Concepts](#important-cyber-asset-management-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Axonius](https://www.axonius.com/)**  
  Cyber asset management and cybersecurity asset intelligence platform that aggregates data from security and IT-management systems to build a unified view of assets, identify gaps, and automate remediation.

- **[Armis](https://www.armis.com/)**  
  Cyber exposure management platform providing visibility across managed and unmanaged devices, IoT, OT, medical devices, cloud assets, applications, and other connected assets.

- **[RunZero](https://www.runzero.com/)**  
  Cyber asset management and network discovery platform focused on rapidly discovering devices and services across enterprise, remote, and unmanaged environments.

- **[Noetic Cyber](https://noeticcyber.com/)**  
  Cyber asset management and cyber hygiene platform that continuously discovers assets, correlates security data, identifies control gaps, and automates remediation workflows.

- **[Device42](https://www.device42.com/)**  
  IT infrastructure discovery and dependency-mapping platform providing comprehensive inventory, CMDB, application dependency mapping, IP address management, and data-center infrastructure visibility.

- **[Lansweeper](https://www.lansweeper.com/)**  
  IT asset discovery and inventory platform that discovers hardware, software, users, cloud resources, and other technology assets across enterprise environments.

- **[ServiceNow Discovery](https://www.servicenow.com/products/it-operations-management/what-is-discovery.html)**  
  Enterprise infrastructure discovery capability that identifies IT infrastructure and populates the ServiceNow CMDB with configuration items and relationships.

- **[Tanium](https://www.tanium.com/)**  
  Endpoint management and security platform providing real-time visibility, inventory, endpoint querying, vulnerability management, and control across large distributed environments.

- **[Forescout](https://www.forescout.com/)**  
  Cybersecurity platform focused on device discovery, device classification, network visibility, asset intelligence, and security policy enforcement across IT, IoT, OT, and IoMT environments.

- **[Qualys CyberSecurity Asset Management](https://www.qualys.com/apps/cybersecurity-asset-management/)**  
  Cyber asset-management capability providing continuous asset discovery, inventory, classification, and security context integrated with the Qualys platform.

- **[Rapid7 InsightVM / Insight Platform](https://www.rapid7.com/)**  
  Security platform combining asset discovery, vulnerability assessment, endpoint and network visibility, and exposure analytics.

- **[Microsoft Defender External Attack Surface Management](https://www.microsoft.com/en-us/security/business/solutions/external-attack-surface-management)**  
  External attack-surface discovery capability for identifying internet-facing assets and understanding an organization's externally exposed technology footprint.

- **[Microsoft Defender for Endpoint](https://www.microsoft.com/en-us/security/business/endpoint-security/microsoft-defender-endpoint)**  
  Endpoint security platform providing endpoint inventory, telemetry, device discovery, vulnerability information, and security posture visibility.

- **[CrowdStrike Falcon](https://www.crowdstrike.com/)**  
  Cloud-native endpoint and security platform providing endpoint telemetry, asset visibility, vulnerability intelligence, and security context.

- **[Wiz](https://www.wiz.io/)**  
  Cloud security platform providing cloud asset discovery, security graphing, identity relationships, vulnerabilities, and exposure analysis across cloud environments.

- **[Orca Security](https://orca.security/)**  
  Cloud security platform providing agentless discovery and inventory of cloud assets together with vulnerabilities, identities, misconfigurations, and attack-path context.

- **[Lacework](https://www.fortinet.com/products/cloud-security/lacework)**  
  Cloud security platform focused on cloud asset visibility, workload discovery, configuration analysis, and security monitoring.

- **[Sysdig](https://sysdig.com/)**  
  Cloud and container security platform providing visibility into hosts, containers, Kubernetes resources, workloads, and cloud infrastructure.

- **[SentinelOne Singularity](https://www.sentinelone.com/platform/)**  
  Security platform providing endpoint visibility, device inventory, telemetry, vulnerability context, and automated security operations.

- **[Qualys](https://www.qualys.com/)**  
  Cloud security and compliance platform providing asset discovery, vulnerability management, IT asset inventory, configuration assessment, and security intelligence.

- **[Tenable One](https://www.tenable.com/products/tenable-one)**  
  Exposure-management platform combining asset discovery, vulnerability management, attack-surface intelligence, and exposure analytics.

- **[Tenable Attack Surface Management](https://www.tenable.com/products/attack-surface-management)**  
  External attack-surface discovery and asset-inventory capability designed to identify internet-facing infrastructure and unknown assets.

- **[Ivanti Neurons](https://www.ivanti.com/platform/ivanti-neurons)**  
  Unified endpoint and asset-management platform providing device discovery, inventory, endpoint management, automation, and security context.

- **[Flexera One](https://www.flexera.com/products/flexera-one)**  
  Technology intelligence platform covering IT asset inventory, software asset management, cloud infrastructure, SaaS, and technology lifecycle information.

- **[BMC Helix Discovery](https://www.bmc.com/it-solutions/helix-discovery.html)**  
  Infrastructure discovery and dependency-mapping platform that discovers IT assets and relationships for CMDB and service-management use cases.

- **[Device42](https://www.device42.com/)**  
  Infrastructure discovery and dependency-mapping solution covering hardware, software, networks, applications, virtual machines, cloud infrastructure, and data-center assets.

- **[InvGate Asset Management](https://www.invgate.com/asset-management/)**  
  IT asset-management platform covering hardware, software, inventory, lifecycle management, and IT service-management workflows.

- **[SolarWinds Service Desk](https://www.solarwinds.com/service-desk)**  
  IT service-management and asset-management platform with inventory, discovery, configuration, and service-management capabilities.

- **[ManageEngine AssetExplorer](https://www.manageengine.com/products/asset-explorer/)**  
  IT asset-management and CMDB platform providing hardware/software inventory, lifecycle management, discovery, and configuration management.

- **[Lansweeper](https://www.lansweeper.com/)**  
  Automated technology asset discovery and inventory platform supporting IT, OT, cloud, software, hardware, and network assets.

- **[Freshservice Asset Management](https://www.freshworks.com/freshservice/)**  
  IT service-management platform with hardware/software asset discovery, lifecycle management, CMDB, and service relationships.

- **[NinjaOne](https://www.ninjaone.com/)**  
  Endpoint management and IT operations platform providing device inventory, endpoint monitoring, patch management, software management, and automation.

- **[Datadog Infrastructure Monitoring](https://www.datadoghq.com/product/infrastructure-monitoring/)**  
  Infrastructure observability platform that automatically discovers hosts, containers, services, cloud resources, and infrastructure relationships.

- **[Dynatrace](https://www.dynatrace.com/)**  
  Observability platform providing automatic discovery and topology mapping across applications, services, infrastructure, cloud environments, and dependencies.

## Open-Source GitHub Projects

- **[GLPI](https://github.com/glpi-project/glpi)**  
  Open-source IT asset management, service desk, inventory, and CMDB platform. GLPI can track computers, servers, network equipment, software, licenses, and other IT assets and can be extended with inventory/discovery integrations.

- **[Snipe-IT](https://github.com/grokability/snipe-it)**  
  Free and open-source IT asset and license-management platform built around asset inventory, ownership, lifecycle, software licenses, accessories, and hardware tracking.

- **[Ralph](https://github.com/allegro/ralph)**  
  Open-source asset-management, DCIM, and CMDB platform designed for data centers and back-office hardware, with asset lifecycle and infrastructure-management capabilities.

- **[OCS Inventory NG](https://github.com/OCSInventory-NG/OCSInventory-Server)**  
  Open-source automated IT inventory and asset-discovery platform that collects hardware and software information from endpoints and provides centralized inventory management.

- **[Open-AudIT](https://github.com/lateralblast/Open-AudIT)**  
  Open-source network discovery and IT inventory software designed to discover network devices, collect hardware/software information, and maintain infrastructure inventory.

- **[CMDBuild](https://github.com/nature40/cmdbuild)**  
  Open-source CMDB and asset-management platform for modeling IT infrastructure, relationships, configuration items, workflows, and organizational assets.

- **[iTop](https://github.com/Combodo/iTop)**  
  Open-source IT service-management and CMDB platform providing configuration-item management, relationships, service modeling, incident management, and infrastructure visibility.

- **[NetBox](https://github.com/netbox-community/netbox)**  
  Open-source network source-of-truth and infrastructure resource-modeling platform covering devices, IP addresses, racks, sites, VLANs, circuits, virtual machines, and network relationships.

- **[NetBox Discovery](https://github.com/netbox-community)**  
  NetBox ecosystem integrations and automation projects for importing discovered infrastructure information into a network source of truth.

- **[Nmap](https://github.com/nmap/nmap)**  
  Open-source network discovery and security auditing tool capable of identifying hosts, ports, services, operating systems, and network characteristics.

- **[Masscan](https://github.com/robertdavidgraham/masscan)**  
  High-speed Internet-scale port scanner useful for large-scale network discovery and asset enumeration.

- **[osquery](https://github.com/osquery/osquery)**  
  Open-source operating-system instrumentation framework that exposes endpoint information through SQL-like queries, enabling detailed hardware, software, process, network, and configuration inventory.

- **[Fleet](https://github.com/fleetdm/fleet)**  
  Open-source device-management and osquery-based endpoint visibility platform providing centralized querying, inventory, policies, and endpoint management.

- **[Wazuh](https://github.com/wazuh/wazuh)**  
  Open-source security platform providing endpoint agents, system inventory, vulnerability information, configuration assessment, threat detection, and security monitoring.

- **[Zabbix](https://github.com/zabbix/zabbix)**  
  Open-source monitoring platform capable of network discovery, infrastructure monitoring, host inventory, and automated detection of networked systems.

- **[Rudder](https://github.com/Normation/rudder)**  
  Open-source infrastructure automation and configuration-management platform providing endpoint inventory, configuration enforcement, policy management, and compliance visibility.

- **[OpenNMS](https://github.com/OpenNMS/opennms)**  
  Open-source network-management platform providing network discovery, monitoring, topology information, and infrastructure visibility.

- **[LibreNMS](https://github.com/librenms/librenms)**  
  Open-source network monitoring platform with automatic network discovery, device inventory, SNMP-based monitoring, and infrastructure visualization.

- **[Observium Community](https://github.com/observium/observium-community)**  
  Network monitoring platform providing automatic discovery and inventory of network devices and infrastructure.

- **[Netdisco](https://github.com/netdisco/netdisco)**  
  Open-source web-based network management and discovery system that discovers network devices, switch ports, MAC addresses, IP addresses, and connected hosts.

- **[NetBox](https://github.com/netbox-community/netbox)**  
  Open-source infrastructure resource-management platform particularly useful as the authoritative inventory/source-of-truth layer in a cyber asset-management architecture.

- **[phpIPAM](https://github.com/phpipam/phpipam)**  
  Open-source IP address-management application useful for maintaining IP space, subnets, VLANs, and network infrastructure inventory.

- **[Nautobot](https://github.com/nautobot/nautobot)**  
  Open-source network automation and source-of-truth platform for modeling devices, IP addresses, circuits, interfaces, locations, and network relationships.

- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  
  Open-source cyber threat-intelligence platform useful for connecting assets, indicators, vulnerabilities, threat actors, campaigns, and other security entities.

- **[MISP](https://github.com/MISP/MISP)**  
  Open-source threat-intelligence sharing platform useful for enriching cyber asset data with indicators, threat intelligence, and contextual security information.

- **[Greenbone Community Edition](https://github.com/greenbone)**  
  Open-source vulnerability-management ecosystem that can provide vulnerability findings and security context for discovered assets.

- **[OpenVAS Scanner](https://github.com/greenbone/openvas-scanner)**  
  Open-source vulnerability scanner useful for identifying vulnerabilities associated with discovered hosts and services.

- **[Nuclei](https://github.com/projectdiscovery/nuclei)**  
  Open-source vulnerability and security scanning engine useful for enriching asset inventories with security findings.

- **[httpx](https://github.com/projectdiscovery/httpx)**  
  Fast open-source HTTP probing toolkit useful for discovering and fingerprinting web services associated with assets.

- **[Naabu](https://github.com/projectdiscovery/naabu)**  
  Open-source port-scanning tool useful for identifying exposed services during attack-surface discovery.

- **[Amass](https://github.com/owasp-amass/amass)**  
  Open-source attack-surface discovery and network mapping toolkit useful for discovering domains, subdomains, DNS infrastructure, and externally exposed assets.

- **[Subfinder](https://github.com/projectdiscovery/subfinder)**  
  Open-source passive subdomain discovery tool useful for external attack-surface enumeration.

- **[SpiderFoot](https://github.com/smicallef/spiderfoot)**  
  Open-source OSINT automation platform useful for discovering and correlating domains, IP addresses, DNS records, usernames, vulnerabilities, and other infrastructure intelligence.

- **[OWASP Netattacker](https://github.com/OWASP/Netattacker)**  
  Open-source network assessment project useful for security-oriented infrastructure discovery and assessment workflows.

- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  
  Open-source cloud asset inventory and security data platform that extracts infrastructure configuration from cloud and SaaS APIs into queryable destinations.

- **[Steampipe](https://github.com/turbot/steampipe)**  
  Open-source framework that lets users query cloud APIs and infrastructure as SQL tables, making it useful for building cloud asset inventories and compliance queries.

- **[Cartography](https://github.com/lyft/cartography)**  
  Open-source asset and infrastructure graphing tool that ingests cloud and infrastructure metadata into Neo4j to build a searchable graph of assets and relationships.

- **[Prowler](https://github.com/prowler-cloud/prowler)**  
  Open-source cloud-security assessment tool that inventories cloud resources and evaluates them against security and compliance controls.

- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)**  
  Open-source multi-cloud security auditing tool that collects and analyzes cloud configuration and resource information.

- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)**  
  Open-source cloud governance engine useful for querying, classifying, and enforcing policies across cloud resources.

- **[Kubevious](https://github.com/kubevious/kubevious)**  
  Kubernetes visualization and configuration-management tool useful for discovering workloads and relationships within Kubernetes environments.

- **[Headlamp](https://github.com/kubernetes-sigs/headlamp)**  
  Open-source Kubernetes web UI providing visibility into clusters, workloads, nodes, namespaces, and resources.

- **[Kubernetes Dashboard](https://github.com/kubernetes/dashboard)**  
  Open-source Kubernetes management UI useful for visualizing cluster resources and workloads.

- **[NetAlertX](https://github.com/jokob-sk/NetAlertX)**  
  Open-source network monitoring and device-discovery application that detects devices on local networks and provides inventory and alerting capabilities.

- **[NetBox Inventory Plugins](https://github.com/netbox-community/netbox)**  
  Community ecosystem around NetBox for automatically importing infrastructure and device information into an authoritative source of truth.

- **[Snipe-IT](https://github.com/grokability/snipe-it)**  
  Particularly useful as the lifecycle/ownership layer of an open-source asset-management stack, while discovery systems such as OCS Inventory, osquery, Nmap, or Open-AudIT provide technical visibility.

## Additional Strong Open-Source Options

The following projects are not necessarily complete Cyber Asset Management platforms, but are highly valuable components for building a self-hosted CAASM/CSAM/ITAM system.

### IT Asset Management & CMDB

- **[GLPI](https://github.com/glpi-project/glpi)** — ITAM + ITSM + CMDB.
- **[Snipe-IT](https://github.com/grokability/snipe-it)** — Hardware, software, license, and lifecycle management.
- **[Ralph](https://github.com/allegro/ralph)** — Data-center asset management and CMDB.
- **[OCS Inventory NG](https://github.com/OCSInventory-NG/OCSInventory-Server)** — Automated endpoint inventory.
- **[CMDBuild](https://github.com/nature40/cmdbuild)** — Customizable open-source CMDB.
- **[iTop](https://github.com/Combodo/iTop)** — CMDB + ITSM.
- **[Open-AudIT](https://github.com/lateralblast/Open-AudIT)** — Network discovery and auditing.
- **[NetBox](https://github.com/netbox-community/netbox)** — Network source of truth and DCIM.
- **[Nautobot](https://github.com/nautobot/nautobot)** — Network automation/source of truth.
- **[phpIPAM](https://github.com/phpipam/phpipam)** — IPAM and network inventory.

### Endpoint Discovery & Telemetry

- **[osquery](https://github.com/osquery/osquery)** — SQL-based endpoint inventory and inspection.
- **[Fleet](https://github.com/fleetdm/fleet)** — Centralized osquery fleet management.
- **[Wazuh](https://github.com/wazuh/wazuh)** — Endpoint security + inventory.
- **[Rudder](https://github.com/Normation/rudder)** — Endpoint configuration and compliance.
- **[GLPI Agent](https://github.com/glpi-project/glpi-agent)** — Endpoint inventory agent for GLPI.
- **[Zabbix](https://github.com/zabbix/zabbix)** — Infrastructure monitoring and discovery.
- **[LibreNMS](https://github.com/librenms/librenms)** — Network discovery and monitoring.

### Network Discovery

- **[Nmap](https://github.com/nmap/nmap)** — Host/service discovery and fingerprinting.
- **[Masscan](https://github.com/robertdavidgraham/masscan)** — High-speed port scanning.
- **[Netdisco](https://github.com/netdisco/netdisco)** — Network topology and connected-device discovery.
- **[Amass](https://github.com/owasp-amass/amass)** — External attack-surface discovery.
- **[Naabu](https://github.com/projectdiscovery/naabu)** — Port discovery.
- **[httpx](https://github.com/projectdiscovery/httpx)** — HTTP service discovery.
- **[Subfinder](https://github.com/projectdiscovery/subfinder)** — Subdomain discovery.
- **[SpiderFoot](https://github.com/smicallef/spiderfoot)** — Automated OSINT infrastructure discovery.

### Cloud Asset Discovery

- **[CloudQuery](https://github.com/cloudquery/cloudquery)** — Cloud/SaaS asset inventory.
- **[Steampipe](https://github.com/turbot/steampipe)** — SQL-based cloud inventory.
- **[Cartography](https://github.com/lyft/cartography)** — Infrastructure relationship graph.
- **[Prowler](https://github.com/prowler-cloud/prowler)** — Cloud resource discovery and security assessment.
- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** — Multi-cloud security inventory.
- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** — Cloud resource policy engine.
- **[kube-state-metrics](https://github.com/kubernetes/kube-state-metrics)** — Kubernetes resource-state telemetry.

### Vulnerability & Security Enrichment

- **[Greenbone Community Edition](https://github.com/greenbone)** — Open-source vulnerability-management ecosystem.
- **[OpenVAS](https://github.com/greenbone/openvas-scanner)** — Vulnerability scanning.
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** — Template-based security scanning.
- **[Nmap NSE](https://github.com/nmap/nmap)** — Network/service security discovery.
- **[Wazuh](https://github.com/wazuh/wazuh)** — Vulnerability and security-state enrichment.
- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)** — Threat-intelligence graph.
- **[MISP](https://github.com/MISP/MISP)** — Threat-intelligence sharing and enrichment.

### Infrastructure Graph & Relationship Mapping

- **[Cartography](https://github.com/lyft/cartography)** — Infrastructure graph based on Neo4j.
- **[Neo4j](https://github.com/neo4j/neo4j)** — Graph database for asset relationships.
- **[Apache AGE](https://github.com/apache/age)** — Graph capabilities for PostgreSQL.
- **[NetworkX](https://github.com/networkx/networkx)** — Python graph-analysis library.
- **[JanusGraph](https://github.com/JanusGraph/janusgraph)** — Distributed graph database.
- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** — Search and analytics engine.
- **[Elasticsearch](https://github.com/elastic/elasticsearch)** — Distributed search and analytics.

### Infrastructure Monitoring

- **[Zabbix](https://github.com/zabbix/zabbix)** — Infrastructure monitoring and discovery.
- **[Prometheus](https://github.com/prometheus/prometheus)** — Metrics collection and infrastructure telemetry.
- **[Grafana](https://github.com/grafana/grafana)** — Infrastructure dashboards and visualization.
- **[LibreNMS](https://github.com/librenms/librenms)** — Network monitoring and discovery.
- **[OpenNMS](https://github.com/OpenNMS/opennms)** — Network management and discovery.
- **[Netdata](https://github.com/netdata/netdata)** — Real-time infrastructure monitoring.

### Asset Data Processing & Integration

- **[Apache Kafka](https://github.com/apache/kafka)** — Event streaming for asset-data pipelines.
- **[Apache NiFi](https://github.com/apache/nifi)** — Data ingestion and integration.
- **[Apache Airflow](https://github.com/apache/airflow)** — Asset-data workflow orchestration.
- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation and integrations.
- **[Logstash](https://github.com/elastic/logstash)** — Data ingestion and transformation.
- **[Fluent Bit](https://github.com/fluent/fluent-bit)** — Lightweight telemetry and log collection.
- **[Vector](https://github.com/vectordotdev/vector)** — High-performance observability data pipeline.

### Databases & Search

- **[PostgreSQL](https://github.com/postgres/postgres)** — Structured asset database.
- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** — Asset search and analytics.
- **[Elasticsearch](https://github.com/elastic/elasticsearch)** — Full-text and structured asset search.
- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** — Large-scale asset telemetry analytics.
- **[DuckDB](https://github.com/duckdb/duckdb)** — Local analytical processing of asset datasets.
- **[Redis](https://github.com/redis/redis)** — Caching and fast asset lookups.
- **[Neo4j](https://github.com/neo4j/neo4j)** — Asset relationship graph.

## Open-Source Cyber Asset Management Stack

A serious self-hosted cyber asset-management system can be assembled from the following layers:

```text
                         ┌─────────────────────────────────┐
                         │         Asset Sources             │
                         │                                 │
                         │ Endpoints / Servers / Networks   │
                         │ Cloud / SaaS / Containers / OT   │
                         │ IoT / IoMT / Applications       │
                         └───────────────┬─────────────────┘
                                         │
              ┌──────────────────────────┼──────────────────────────┐
              │                          │                          │
              ▼                          ▼                          ▼
     ┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
     │ Network Discovery │      │ Endpoint         │      │ Cloud Discovery  │
     │                  │      │ Discovery        │      │                  │
     │ Nmap             │      │ osquery          │      │ CloudQuery       │
     │ Masscan           │      │ Fleet            │      │ Steampipe        │
     │ Open-AudIT        │      │ OCS Inventory    │      │ Prowler          │
     │ Netdisco          │      │ Wazuh            │      │ ScoutSuite       │
     └─────────┬────────┘      └─────────┬────────┘      └─────────┬────────┘
               │                         │                         │
               └─────────────────────────┼─────────────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │       Asset Normalization        │
                         │                                 │
                         │ Deduplication / Fingerprinting │
                         │ Hostname / IP / MAC / UUID      │
                         │ Cloud IDs / Serial Numbers      │
                         │ Software / Hardware Mapping     │
                         └───────────────┬─────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │        Entity Resolution          │
                         │                                 │
                         │ Same Asset Across Multiple      │
                         │ Discovery & Security Sources     │
                         │                                 │
                         │ osquery ↔ Nmap ↔ EDR ↔ Cloud    │
                         └───────────────┬─────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │       Asset Intelligence          │
                         │                                 │
                         │ Hardware / Software / Users      │
                         │ Vulnerabilities / Ownership      │
                         │ Tags / Business Criticality      │
                         │ Exposure / Security Controls     │
                         └───────────────┬─────────────────┘
                                         │
                    ┌────────────────────┼────────────────────┐
                    │                    │                    │
                    ▼                    ▼                    ▼
          ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
          │ CMDB / ITAM     │  │ Security        │  │ Asset Graph     │
          │                 │  │ Intelligence    │  │                 │
          │ GLPI            │  │ Wazuh           │  │ Neo4j           │
          │ Snipe-IT        │  │ OpenVAS         │  │ Cartography     │
          │ Ralph           │  │ Nuclei          │  │ NetworkX        │
          │ iTop            │  │ OpenCTI         │  │                 │
          │ NetBox          │  │ MISP            │  │                 │
          └────────┬────────┘  └────────┬────────┘  └────────┬────────┘
                   │                    │                    │
                   └────────────────────┼────────────────────┘
                                        │
                                        ▼
                         ┌─────────────────────────────────┐
                         │        Cyber Asset Graph          │
                         │                                 │
                         │ Asset → User → Software         │
                         │ Asset → Network → Service       │
                         │ Asset → Vulnerability → Risk    │
                         │ Asset → Cloud → Identity        │
                         │ Asset → Application → Dependency │
                         └───────────────┬─────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │        Exposure Analytics          │
                         │                                 │
                         │ Unknown Assets / Rogue Devices   │
                         │ Vulnerable Assets / EOL Software │
                         │ Internet Exposure / Shadow IT    │
                         │ Missing Security Controls        │
                         │ Attack Paths / Critical Assets   │
                         └───────────────┬─────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │       Risk Prioritization          │
                         │                                 │
                         │ Asset Criticality                 │
                         │ Vulnerability Severity            │
                         │ Exploitability                    │
                         │ Internet Exposure                 │
                         │ Business Context                  │
                         │ Security Control Coverage         │
                         └───────────────┬─────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │      Dashboards / Search / API    │
                         │                                 │
                         │ Asset Inventory / CMDB           │
                         │ Attack Surface / Exposure        │
                         │ Security Coverage / Compliance   │
                         │ Infrastructure Graph             │
                         └───────────────┬─────────────────┘
                                         │
                                         ▼
                         ┌─────────────────────────────────┐
                         │       Remediation Automation      │
                         │                                 │
                         │ Ticketing / SOAR / ITSM          │
                         │ Patch / EDR / MDM / IAM          │
                         │ Firewall / Network Automation     │
                         │ Workflow / Notification           │
                         └─────────────────────────────────┘
