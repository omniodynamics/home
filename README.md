# Omnio Dynamics Incorporated


## Repositories
- [odinet.ca](https://github.com/omniodynamics/odinet.ca) - CA Cluster
- [odinet.me](https://github.com/omniodynamics/odinet.me) - IAM
- [odinet.run](https://github.com/omniodynamics/odinet.run) - Runtime, Operations, State
- [odinet.sh](https://github.com/omniodynamics/odinet.sh) - Control Nodes, Source, IaC
- [odinet.pub](https://github.com/omniodynamics/odinet.pub) - Public Cluster
- [odinet.work](https://github.com/omniodynamics/odinet.work) - Queue, Scheduling, Orchestration
- [omniodynamics](https://github.com/omniodynamics/omniodynamics) - Corporate\


## Skills

| Skill                             | Score | Priority |     Comments                                   |
|---------------------------------|-------|----------|--------------------------------------------|
| Step Functions                  | 1     | 1        | Stateful workflows that integrate well across AWS. |
| Lambda                           | 2     | 2        | User defined tasks, "SaaS-Light"           |
| SES, SNS, SQS                    | 1     | 3        | Solution design                            |
| Federation (SSO)                 |       |          |                                            |
| OAuth 2.0                        |       |          |                                            |
| OIDC                             |       |          |                                            |
| Kubectl Port Forward             |       |          |                                            |
| Kubectl Proxy                    |       |          |                                            |
| End User Messaging               |       |          |                                            |
| CICD Githubs Base                |   3    | 4          |                                            |
| Generic Microservice Feature Pattern |  2     |    1      |                                            |
| Traffic Transforming             |     3  |      1    |                                            |
| Github Workflow Mocking, Act     |    3   |      3    |                                            |
| PVC, VP, SS                      |       |          |                                            |
| Deployments, DaemonSet           |       |          |                                            |
| NetworkPolicy                    |       |          |                                            |
| SA                               |       |          |                                            |
| StorageClass                     |       |          |                                            |
| Tooling                          |       |          |                                            |
| LoadBalancer                     |       |          |                                            |
| EKS Addons (CSI)                 |       |          |                                            |
| IRSA (IAM Roles Service Accounts)|       |          |                                            |
| OIDC                             |       |          |                                            |
| AWS EBS PV Controller            |       |          |                                            |
| Python                           | 4     |  3         |       |
| Typescript                       | 3     |           4 |               | 4|
| Machine Learning | 0 | 4 | Needed for solution development & understanding howto evaluate vendor solutions |


## TODO
| Subject              | Score | Priority | Comments | Date        | Related |
|----------------------|-------|----------|----------|-------------|---------|
| Taints               |       |          |          |             |         |
| Affinity             |       |          |          |             |         |
| ECS                  |   1    |     3     |          |             |    2024-12-09     |
| Lambda               |       |          |          |             |         |
| Glue                 |       |          |          |             |         |
| RDS                  |   3    |     3    |          |             |         |
| CloudWatch           |       |          |          |             |         |
| Cluster Autoscaler   |       |          |          |             |         |
| EFS                  |       |          |          |             |         |
| Istio                |    1   |    3     |          |             |         |
| Dynamic NGINX Backends |   1    |   1       |          |             |         |
| NGINX Controller     |     1  |     1     |          |             |         |
| ArgoCD               |     0  |    4      |          |             |     2024-12-09    |
| Monitoring           |    1   |     5     |          |             |   2024-12-09      |
| Email Protocol AWS Services (SMTP, POP, IMAP) |       |          |          |             |         |
| Auth0 IDP            |       |          |          |             |         |
| NodeJS Microservice Dependency Testing Frameworks (Jest, Supertest) |   1    |   4       |          |             |         |
| VPNs                 |    0   |    2      |          |             |         |
| Cost Estimations     |   0    |     5     |          |             |     FY2025-Q1-Q2    |
| Github CLI           |       |          |          |             |         |
| GCP                  |       |          |          |             |         |
| Azure                |       |          |          |             |         |
| Mobile OS App Prototyping |       |          |          |             |         |
| Controller Development & GOLANG |       |          |          |             |         |
| Resource Quota       |       |          |          |             |         |
| K8s Service Discovery |   2    |     3     |          |             |         |
| Browser UI Frontend Framework | 0 | 5 | Need to look around here to select something "modern".  Django likely stale. |2024-12-16 ||

## Market
### In Demand
- Collaborative Document Editing
- Modular Request && Response Chaining
- Modular Platform Feature Development
- User Task & Workflow Management
- User Notifications
- Integrations
- Mobile Application Frontends
- Generic App Integrations
- Legal Policy Enforcement
- Request Proxying
- Async User Task Execution
- User Document Templating
- User Workflow Collaboration

### Common Features
- User IAM
- SSO
- Document Storage
- Object Versioning
- User Object Model Storage
- Metadata Parsing
- Policy Enforcement
- Generic Data Source Scraping
- User Object & Document Query Languages

### Technical Hard Pills To Swallow
- Garbage Collection, Org Shuffle, Corporate Process, Monitoring Noise
- User Data Metadata & Hyper Linking
- Solution Design Cost Comparision
- Browser Integrations
- Supply Chain Protection & Controls

### Tooling & Services
#### Preferred List
- Grok
- Cygwin
- Chocolately
- Docker
- Terraform
- Typescript
- CommonJS
- GitOps
- IAM
- Corporate Governance Management
- User Defined Tasks (Jobs vs Lambda vs ...)
- Enterprise Applications (M$365, etc, ... )

#### Unused Recently
- Python
- CRDs

#### Deprecated
- CloudFormation
- Ansible
- Terragrunt
- Chef
- Shell Shims
- ChatGPT
- LinkedIn

#### Terrible
- GoDaddy

# History

## December, 2024
- Renamed repos.  Post-GoDaddy blunder, registered a bunch of odinet.* domains.
- NGINX, proxying, SSL-insepection.
- Typescript, MVC generics source dev, async fundamentals.
- Self-Signed CA Server
    - NGINX Exposes https://odinet.sh/crl/crl.pem (Revocation Lists)
    - /etc/nginx/sites-enabled (symlink to) /etc/nginx/sites-available (CRL Server)
    - Let's Encrypt ACME (certbot) Analog
        - Prototype off-of ACME to develop a Certificate Authority server / service.
        - Hosts API for user's to register accounts, perform certmgmt ops.
    - Attempted SSL Inspection
        - CSP Issues, Browser XSS Defaults
        - CA Signing Tooling Resolution
            - SSL Tangents
- Proxy Server
    - Generic TCP/UDP Proxy Server
- Frontend Framework & APIs Prototyping
    - Vue.js Abstracts Fundamental Internals (XSS, Cluster-Needed-Knowledge)
    - Javascript (ES2017?)
        - Fetch
        - Local Storage
        - Web Sockets
        - XHTTP (older)
    - Custom Handling MVC Means Refresher On Browser JS
- Typescript Generics
    - Quick MVC (interface model, view methods, controller + DAO)
    - Sqlite3, Mongo Testing

> Overall, working on creating servers, containers, learning the tooling, to allow me to create a DevOps / SRE Platform.  

- Botkit OPS CLI Tool
- Docker
- Github Actions, Github CLI (gh)
- Git Commit Signing (gnupg)
- Openssl Tools & Config
- NGINX Config
- Debian-Based OS Certificates & Trust (ca-certificates, update-ca-certificates)

## November, 2024
- Projects home for [Ryan Warren](https://github.com/ryancwarren).
- Main goal is to demo / test / study DevOps & SRE skills.
- Secondary goal is to prototype demo's and help create **proposals** for RFIs / RFPs.
- Last updated on Dec 12, 2024.  Next update Dec 8/9 2024.

