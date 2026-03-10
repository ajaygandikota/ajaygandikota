<div align="center">
  
<img src="https://readme-typing-svg.herokuapp.com?size=26&duration=4000&color=00FF9C&center=true&vCenter=true&width=900&lines=Senior+System+Engineer+Cybersecurity;" />

</div>

# Technology Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=linux,aws,azure,docker,kubernetes,git,github,nginx,postgres,redis" />
</p>
<p align="center">
<img src="https://skillicons.dev/icons?i=python,bash,powershell,ansible,flask,fastapi" />
</p>
<p align="center">
<img src="https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,linux,ubuntu,debian" />
</p>
<p align="center">
<img src="https://skillicons.dev/icons?i=githubactions,git,docker,kubernetes,terraform,ansible,prometheus,grafana" />
</p>

# DevSecOps Security Pipeline
```mermaid
flowchart LR

Developer[Developer] --> Code[Code]
Code --> Git[Git Repository]
Git --> CI[CI Pipeline]
CI --> SAST[SAST Scan]
SAST --> DependencyScan[Dependency Scan]
DependencyScan --> ContainerScan[Container Scan]
ContainerScan --> ArtifactRepo[Artifact Repository]
ArtifactRepo --> Deploy[Deploy]
Deploy --> Kubernetes[Kubernetes Cluster]
Kubernetes --> RuntimeSecurity[Runtime Security]
RuntimeSecurity --> Monitoring[Monitoring & Alerts]

style Developer fill:#ff9f43,stroke:#333,stroke-width:2px,color:#fff
style Code fill:#54a0ff,stroke:#333,stroke-width:2px,color:#fff
style Git fill:#10ac84,stroke:#333,stroke-width:2px,color:#fff
style CI fill:#5f27cd,stroke:#333,stroke-width:2px,color:#fff
style SAST fill:#ee5253,stroke:#333,stroke-width:2px,color:#fff
style DependencyScan fill:#f368e0,stroke:#333,stroke-width:2px,color:#fff
style ContainerScan fill:#ff6b6b,stroke:#333,stroke-width:2px,color:#fff
style ArtifactRepo fill:#00d2d3,stroke:#333,stroke-width:2px,color:#fff
style Deploy fill:#1dd1a1,stroke:#333,stroke-width:2px,color:#fff
style Kubernetes fill:#2e86de,stroke:#333,stroke-width:2px,color:#fff
style RuntimeSecurity fill:#ff9ff3,stroke:#333,stroke-width:2px,color:#fff
style Monitoring fill:#576574,stroke:#333,stroke-width:2px,color:#fff
```
# SOC Security Architecture

```mermaid
flowchart LR

Endpoints[Endpoints] --> Logs[Log Collection]
Servers[Servers] --> Logs
Cloud[Cloud Infrastructure] --> Logs
Applications[Applications] --> Logs

Logs --> SIEM[SIEM Platform]
SIEM --> UEBA[UEBA Analytics]
UEBA --> SOAR[SOAR Automation]

SOAR --> IncidentResponse[Incident Response]
IncidentResponse --> ThreatIntel[Threat Intelligence]
ThreatIntel --> DetectionRules[Detection Rules]
DetectionRules --> SIEM

style Endpoints fill:#ff9f43,stroke:#333,stroke-width:2px,color:#fff
style Servers fill:#54a0ff,stroke:#333,stroke-width:2px,color:#fff
style Cloud fill:#5f27cd,stroke:#333,stroke-width:2px,color:#fff
style Applications fill:#10ac84,stroke:#333,stroke-width:2px,color:#fff

style Logs fill:#00d2d3,stroke:#333,stroke-width:2px,color:#fff
style SIEM fill:#2e86de,stroke:#333,stroke-width:2px,color:#fff
style UEBA fill:#ff6b6b,stroke:#333,stroke-width:2px,color:#fff
style SOAR fill:#f368e0,stroke:#333,stroke-width:2px,color:#fff

style IncidentResponse fill:#ee5253,stroke:#333,stroke-width:2px,color:#fff
style ThreatIntel fill:#1dd1a1,stroke:#333,stroke-width:2px,color:#fff
style DetectionRules fill:#576574,stroke:#333,stroke-width:2px,color:#fff
```
# Threat Intelligence Pipeline

```mermaid
flowchart LR
ThreatFeeds --> CTI
CTI --> IOC
IOC --> SIEM
SIEM --> Detection
Detection --> SOC
SOC --> Containment
Containment --> Remediation
```
# Cybersecurity Tools

| Domain                   | Tools                                |
| ------------------------ | ------------------------------------ |
| SIEM                     | Elastic SIEM, Splunk, Wazuh, Graylog |
| SOAR                     | Cortex XSOAR, Shuffle, TheHive       |
| Vulnerability Management | Nessus, OpenVAS, Nuclei              |
| Web Security             | Burp Suite, OWASP ZAP                |
| Threat Intelligence      | MISP, OpenCTI, VirusTotal            |
| Identity Security        | Keycloak, MFA, FIDO2                 |
| DevSecOps Security       | Trivy, Semgrep, CodeQL               |
| Monitoring               | Prometheus, Grafana                  |


# Cybersecurity Projects

## Cyber Infrastructure Management Platform

* SIEM
* SOAR
* UEBA
* IAM
* Patch Management
* Asset Management
* Threat Intelligence
* Vulnerability Scanner


## Enterprise NAC Deployment

* NAC
* 35,000+ endpoints
* Active-Active Architecture
* Scalable to 100k endpoints


## Threat Intelligence & Vulnerability Platform

* IOC correlation
* STIX / TAXII feeds
* Automated vulnerability detection
* Security analytics

# Connect With Me

LinkedIn: **[https://linkedin.com/in/gandikota-ajay-lk](https://linkedin.com/in/gandikota-ajay-lk)**

## ☕ Support My Work

If you find my **Cybersecurity Tools, DevSecOps Projects, and Research** useful, you can support my work.

<p align="center">
  <a href="https://www.buymeacoffee.com/ajaygandikota">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" />
  </a>
</p>



