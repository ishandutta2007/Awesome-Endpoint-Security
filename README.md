# Awesome-Endpoint-Security

Top Endpoint Security Platforms Ecosystem
Top Endpoint Security Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Endpoint Protection, EPP, EDR, XDR, Threat Hunting, Malware Detection & Incident Response
Last updated: September 2026

This repository tracks notable Enterprise Endpoint Security platforms and open-source projects for protecting, monitoring, detecting, investigating, and responding to threats across endpoints, servers, laptops, workstations, and cloud workloads.

Examples include CrowdStrike Falcon, Microsoft Defender for Endpoint, SentinelOne Singularity, Trellix Endpoint Security, VMware Carbon Black, Sophos Endpoint, Palo Alto Cortex XDR, Cisco Secure Endpoint, Bitdefender GravityZone, ESET PROTECT, Wazuh, Velociraptor, osquery, OpenEDR, Fleet, GRR Rapid Response, Santa, and Security Onion.

Open-source emphasis: The Open-Source section prioritizes projects that can serve as direct or complementary alternatives to commercial endpoint security platforms. Because a modern EDR/EPP suite combines endpoint telemetry, prevention, detection, response, threat hunting, malware analysis, vulnerability management, and centralized management, the list includes both complete open-source endpoint-security platforms and specialized building blocks that can be combined into a self-hosted EDR/XDR stack.

Contributions welcome! Please add missing endpoint-security platforms, open-source EDR projects, endpoint agents, threat-hunting tools, malware-analysis engines, and security infrastructure.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

CrowdStrike Falcon
Cloud-native endpoint security platform combining endpoint protection, EDR, threat intelligence, behavioral detection, threat hunting, and automated response through the Falcon platform.

Microsoft Defender for Endpoint
Cloud-native endpoint security platform providing endpoint protection, EDR, attack-surface visibility, advanced hunting, automated response, and XDR integration across Windows, macOS, Linux, mobile, and IoT environments.

SentinelOne Singularity
AI-powered endpoint, cloud, and identity security platform providing prevention, detection, investigation, response, remediation, and autonomous security capabilities.

Trellix Endpoint Security
Multi-layered endpoint protection platform spanning on-premises, cloud, and disconnected environments with centralized management and integrated prevention, detection, and remediation.

VMware Carbon Black
Enterprise endpoint security technology providing endpoint protection, EDR, threat hunting, behavioral detection, application control, and incident response capabilities.

Sophos Endpoint / Intercept X
Endpoint security platform combining malware protection, exploit prevention, ransomware protection, web protection, application control, device control, and EDR/XDR capabilities.

Palo Alto Networks Cortex XDR
XDR platform combining endpoint, network, cloud, and identity telemetry for threat detection, investigation, hunting, and response.

Cisco Secure Endpoint
Enterprise endpoint protection and EDR platform providing endpoint telemetry, malware detection, behavioral protection, threat investigation, and response capabilities.

Bitdefender GravityZone
Enterprise endpoint-security platform providing prevention, malware protection, behavioral detection, EDR, risk analytics, and centralized security management.

ESET PROTECT
Enterprise endpoint-security management platform providing endpoint protection, EDR, vulnerability and patch visibility, cloud sandboxing, encryption, and centralized administration.

Trend Vision One
Cybersecurity platform combining endpoint protection, EDR, XDR, attack-surface management, email, cloud, and network security capabilities.

Symantec Endpoint Security
Enterprise endpoint protection technology providing malware prevention, behavioral protection, endpoint detection, response, and security management.

Tanium
Converged endpoint-management and security platform providing real-time endpoint visibility, asset inventory, vulnerability management, incident response, and endpoint control.

Cybereason
Endpoint and XDR security platform focused on behavioral detection, endpoint telemetry, attack investigation, threat hunting, and automated response.

Fortinet FortiEDR
Endpoint detection and response platform providing behavioral prevention, exploit protection, endpoint telemetry, threat investigation, and automated response.

WithSecure Elements Endpoint Protection
Cloud-managed endpoint protection platform providing malware protection, behavioral security, vulnerability management, and centralized endpoint administration.

WatchGuard Endpoint Security
Endpoint security platform combining prevention, EDR, managed detection, threat hunting, vulnerability management, and endpoint monitoring.

Acronis Cyber Protect
Cyber-protection platform combining endpoint security, anti-malware, EDR-related capabilities, backup, vulnerability assessment, and ransomware recovery.

BlackBerry Cylance
AI-driven endpoint security technology focused on malware prevention, behavioral detection, endpoint protection, and threat response.

Malwarebytes Endpoint Protection
Endpoint security platform providing malware protection, exploit protection, ransomware defense, web protection, and endpoint detection capabilities.

Huntress
Managed security platform focused on endpoint monitoring, managed EDR, threat detection, incident response, and security operations for organizations and MSPs.

Rapid7 InsightIDR / Insight Agent
Cloud security operations platform using endpoint telemetry, behavioral analytics, SIEM, detection, and investigation capabilities.

Sophos MDR
Managed detection and response service built around Sophos endpoint, XDR, threat intelligence, and human-led security operations.

Elastic Security
Security analytics platform combining endpoint telemetry, SIEM, detection engineering, threat hunting, and response through Elastic Agent and related technologies.

Microsoft Defender XDR
Cross-domain security platform connecting endpoint, identity, email, cloud application, and other Microsoft security signals into unified detection and response workflows.

Open-Source GitHub Projects

Wazuh
Open-source security platform providing endpoint monitoring, configuration assessment, file-integrity monitoring, malware detection, vulnerability detection, threat hunting, compliance monitoring, and active response. It combines endpoint agents with centralized security analysis and response capabilities.

OpenEDR
Open-source Endpoint Detection and Response platform providing endpoint telemetry, process monitoring, file-system monitoring, registry monitoring, network monitoring, behavioral analytics, and response capabilities. OpenEDR describes itself as a full EDR codebase intended to provide real-time endpoint visibility and detection.

Velociraptor
Open-source endpoint monitoring, digital-forensics, and incident-response platform. Its VQL query language enables investigators to collect and analyze endpoint artifacts across large fleets of Windows, macOS, and Linux systems.

osquery
Open-source endpoint instrumentation framework that exposes operating-system information through SQL-like queries, enabling security teams to inspect processes, users, files, network connections, installed software, and system configuration across Linux, macOS, and Windows.

Fleet
Open-source endpoint-management and osquery orchestration platform providing centralized fleet management, live querying, software inventory, vulnerability visibility, and endpoint controls.

GRR Rapid Response
Open-source remote live-forensics framework designed for investigating endpoints at scale. It enables security teams to remotely query systems, collect forensic artifacts, and investigate incidents across endpoint fleets.

Security Onion
Open-source security-monitoring platform integrating endpoint and network-security technologies including Suricata, Zeek, osquery, Elastic-based tooling, and other detection capabilities. It is primarily an enterprise security-monitoring platform rather than a standalone EDR.

Elastic Agent
Open-source agent for collecting security and operational telemetry from endpoints and forwarding it to Elastic infrastructure. It can serve as an endpoint telemetry layer for Elastic Security deployments.

osquery Fleet
Centralized management and orchestration for large osquery deployments, providing an open-source foundation for endpoint inventory, querying, and detection workflows.

Zentral
Open-source endpoint-management and security platform focused particularly on Apple environments, providing centralized configuration, monitoring, and security controls for macOS and related Apple endpoints.

Santa
Open-source macOS security agent providing binary authorization and execution-control capabilities. It can monitor and control which binaries are allowed to execute on Mac endpoints.

Fleet osquery
Provides centralized osquery fleet management, enabling organizations to turn endpoint queries and inventory into continuously managed security telemetry.

Kolide Launcher
Open-source endpoint agent designed around osquery and fleet-oriented endpoint telemetry collection.

Kolide Fleet
Open-source endpoint-management ecosystem built around osquery-style endpoint queries and fleet visibility.

Sysmon for Linux
Open-source Linux system-monitoring component from Microsoft providing detailed telemetry about processes, network connections, files, and other system activity.

Falco
Open-source runtime threat-detection engine using system-call and kernel-level telemetry to detect suspicious behavior across Linux systems, containers, hosts, and cloud-native environments.

Tracee
Open-source Linux tracing and security framework based on eBPF for detecting suspicious system activity, malware behavior, and runtime threats.

Tetragon
Open-source eBPF-based security observability and runtime enforcement tool for Linux workloads, providing process, network, and security-event visibility.

Additional Strong Open-Source Options

ClamAV
Open-source antivirus engine providing malware scanning capabilities that can be integrated into endpoint-security, file-server, mail-security, and automated malware-analysis workflows.

YARA
Open-source pattern-matching engine widely used for malware identification, threat hunting, file classification, and incident-response investigations.

YARA-X
Modern open-source implementation of the YARA rule language and detection engine for identifying malicious or suspicious files and artifacts.

Suricata
Open-source IDS/IPS and network-security engine that can complement endpoint telemetry with network-level threat detection and protocol analysis.

Zeek
Open-source network-security monitoring framework useful for correlating endpoint events with network activity during threat hunting and incident response.

Sigma
Open-source generic detection-rule format allowing security detections to be written independently of a particular SIEM or analytics backend.

MITRE Caldera
Open-source automated adversary-emulation and breach-and-attack simulation platform useful for testing endpoint detection and response capabilities.

Atomic Red Team
Open-source library of small, focused tests mapped to MITRE ATT&CK techniques for validating endpoint detections and security controls.

Prelude Operator
Open-source endpoint security testing and adversary-emulation tooling useful for validating detection and response capabilities.

TheHive
Open-source security incident-response and case-management platform that can serve as the investigation and response layer around an endpoint-security stack.

Cortex
Open-source observable-analysis and response engine designed to automate enrichment and analysis during security investigations.

MISP
Open-source threat-intelligence platform for collecting, correlating, sharing, and operationalizing indicators of compromise and threat intelligence.

OpenCTI
Open-source cyber-threat-intelligence platform providing knowledge-graph-based management of threat actors, campaigns, malware, indicators, vulnerabilities, and relationships.

CAPE Sandbox
Open-source malware-analysis and sandboxing ecosystem useful for dynamically analyzing suspicious binaries and extracting behavioral indicators.

CAPEv2
Automated malware-analysis environment derived from the Cuckoo ecosystem, useful for behavioral analysis and malware triage.

Cuckoo Sandbox
Open-source automated malware-analysis system capable of executing suspicious files in isolated environments and collecting behavioral information.

REMnux
Linux-based toolkit and ecosystem for reverse engineering and malware analysis, useful as a complementary analysis environment for endpoint investigations.

Volatility 3
Open-source memory-forensics framework useful for investigating compromised endpoints, malicious processes, injected code, credentials, and other artifacts from memory images.

Plaso
Open-source forensic timeline-generation framework useful for reconstructing endpoint activity during incident response.

Timesketch
Open-source collaborative forensic-timeline analysis platform useful for investigating and correlating endpoint events during incident response.

Autopsy
Open-source digital-forensics platform providing graphical workflows around The Sleuth Kit for investigating disks, filesystems, and endpoint artifacts.

The Sleuth Kit
Open-source collection of command-line digital-forensics tools for analyzing disk images and filesystems.

Velociraptor Artifacts
Reusable VQL-based forensic and threat-hunting artifacts that allow investigators to deploy endpoint collection and detection logic across large fleets.

OpenSearch
Open-source search and analytics engine useful as a backend for security telemetry, endpoint-event search, detection analytics, and investigation dashboards.

OpenSearch Security Analytics
Open-source security analytics capabilities for detection rules, threat intelligence, security findings, and investigation workflows.

Grafana
Open-source visualization and observability platform useful for building custom endpoint-security dashboards over telemetry collected from EDR components.

Prometheus
Open-source monitoring and metrics platform useful for monitoring the health and performance of endpoint-security infrastructure and agents.

Apache Kafka
Open-source event-streaming platform useful for transporting high-volume endpoint telemetry between agents, detection engines, data lakes, and security analytics systems.

Vector
Open-source high-performance observability data pipeline useful for collecting, transforming, filtering, and routing endpoint security telemetry.

Fluent Bit
Lightweight open-source telemetry and log-processing agent useful for collecting endpoint and server security events.

OpenTelemetry Collector
Vendor-neutral open-source telemetry pipeline that can complement endpoint-security infrastructure by collecting and routing logs, metrics, and traces.

Framework for building a self-hosted Endpoint Detection & Response platform: Combine Wazuh / OpenEDR / Velociraptor / osquery / Fleet / GRR for endpoint telemetry, monitoring, hunting, and response; ClamAV / YARA / YARA-X for malware detection; Falco / Tracee / Tetragon for Linux runtime and kernel-level visibility; Suricata / Zeek for network telemetry; Sigma for portable detection rules; MISP / OpenCTI for threat intelligence; TheHive / Cortex for incident response and automated enrichment; Volatility / Plaso / Timesketch / Autopsy for digital forensics; and OpenSearch / Kafka / Vector / Fluent Bit / Grafana for telemetry transport, storage, analytics, and visualization.

This modular architecture can reproduce many of the fundamental components found in commercial EDR/XDR platforms, while allowing organizations to choose individual components and maintain greater control over their endpoint telemetry, detection logic, and security infrastructure.

How to Contribute

Fork this repository.

Add the platform or open-source project to the appropriate section.

Prefer official product websites for SaaS platforms.

Prefer official GitHub repositories for open-source projects.

Keep descriptions concise and technically accurate.

Prioritize actively maintained projects.

Clearly distinguish complete endpoint-security platforms from individual security tools and infrastructure components.

Submit a pull request with your changes.

Disclaimer

This is a curated ecosystem rather than a ranking or endorsement.

Commercial endpoint-security platforms differ significantly in prevention, EDR, XDR, threat intelligence, telemetry depth, automated response, operating-system coverage, cloud architecture, and managed-security capabilities.

Some projects in the Open-Source section are complete or near-complete endpoint-security platforms, while others are endpoint agents, EDR components, forensic tools, malware-analysis engines, detection frameworks, network-security tools, or supporting infrastructure.

Open-source does not necessarily mean that a project provides the same feature set, support model, threat intelligence, or automated prevention capabilities as a commercial EPP/EDR/XDR platform.

Open-source availability, licensing, features, supported operating systems, and project activity can change over time.

Always verify licensing, security, maintenance status, operating-system support, scalability, and deployment requirements before adopting a project.

Made for security engineers, SOC teams, incident responders, threat hunters, IT teams, DevSecOps engineers & organizations building the next generation of Endpoint Security platforms.
Let's make endpoint security more open, transparent, composable & self-hostable.

Remove duplicate open-source projects
Group open-source tools by function
