# Ansible (ansible)
Ansible is an open-source IT automation platform developed by Red Hat that provides agentless configuration management, application deployment, cloud provisioning, and orchestration. Using YAML-based playbooks and an SSH-native architecture, Ansible automates infrastructure at scale without requiring agents on managed nodes.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Ansible, Automation, Configuration Management, DevOps, Infrastructure As Code, Open Source, Orchestration, Red Hat

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Ansible Automation Platform API
RESTful API for Ansible Automation Platform (formerly Ansible Tower) that provides programmatic access to job templates, inventories, credentials, workflow templates, schedules, notifications, and job execution.

**Human URL:** [https://docs.ansible.com/automation-controller/latest/html/controllerapi/](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)

#### Tags:

 - Ansible, Automation, Enterprise, Inventories, Jobs, Red Hat, Workflows

#### Properties

- [Documentation](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)
- [APIReference](https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html)
- [Authentication](https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html)
- [GettingStarted](https://docs.ansible.com/automation-controller/latest/html/quickstart/)

### AWX API
AWX is the open-source upstream project for Ansible Automation Platform, providing a web-based UI, REST API, and task engine for Ansible under the Apache 2.0 license.

**Human URL:** [https://github.com/ansible/awx](https://github.com/ansible/awx)

#### Tags:

 - Ansible, Automation, AWX, Jobs, Open Source

#### Properties

- [Documentation](https://ansible.readthedocs.io/projects/awx/en/latest/)
- [APIReference](https://github.com/ansible/awx/blob/devel/docs/rest_api.md)
- [GitHubRepository](https://github.com/ansible/awx)
- [GettingStarted](https://github.com/ansible/awx/blob/devel/INSTALL.md)

### Ansible Galaxy API
REST API for Ansible Galaxy — the community hub for sharing and downloading Ansible roles and collections with namespace management, versioning, search, and content download capabilities.

**Human URL:** [https://galaxy.ansible.com/](https://galaxy.ansible.com/)

#### Tags:

 - Ansible, Collections, Community, Galaxy, Roles

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [APIReference](https://galaxy.ansible.com/api/v3/)
- [GitHubRepository](https://github.com/ansible/galaxy)

### Ansible Automation Hub API
The Red Hat Ansible Automation Hub API provides access to certified Ansible collections and roles curated by Red Hat and partners for enterprise Ansible Automation Platform deployments.

**Human URL:** [https://console.redhat.com/ansible/automation-hub](https://console.redhat.com/ansible/automation-hub)

#### Tags:

 - Ansible, Certified Content, Collections, Enterprise, Red Hat

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/)
- [APIReference](https://console.redhat.com/api/automation-hub/v3/)
- [Portal](https://console.redhat.com/ansible/automation-hub)

## Common Properties

- [Portal](https://www.ansible.com)
- [GettingStarted](https://docs.ansible.com/ansible/latest/getting_started/)
- [Documentation](https://docs.ansible.com/)
- [Blog](https://www.ansible.com/blog)
- [GitHubOrganization](https://github.com/ansible)
- [Forum](https://forum.ansible.com/)
- [Support](https://access.redhat.com/products/red-hat-ansible-automation-platform/)
- [Training](https://www.ansible.com/products/training-certification)
- [TermsOfService](https://www.redhat.com/en/about/terms-use)
- [PrivacyPolicy](https://www.redhat.com/en/about/privacy-policy)
- [SDK — Ansible Python Package](https://pypi.org/project/ansible/)
- [SDK — Ansible Runner Python Package](https://pypi.org/project/ansible-runner/)
- [JSONSchema — Playbook Schema](json-schema/ansible-playbook-schema.json)
- [Vocabulary](vocabulary/ansible-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Agentless Architecture | Ansible connects to managed nodes via SSH or WinRM without requiring any agent software, simplifying deployment and reducing attack surface. |
| YAML Playbooks | Automation is defined in human-readable YAML playbooks that describe the desired state of managed systems without complex programming. |
| Idempotent Execution | Ansible tasks are idempotent — running the same playbook multiple times produces the same result, making deployments safe to rerun. |
| Module Ecosystem | Over 3,000 built-in modules covering cloud providers, network devices, databases, containers, storage, and operating system tasks. |
| Collection System | The Ansible Collections packaging format bundles related modules, roles, plugins, and documentation for modular content distribution. |
| Dynamic Inventory | Query cloud providers, CMDBs, and external systems dynamically to build host inventories at execution time rather than static files. |

## Use Cases

| Name | Description |
|------|-------------|
| Configuration Management | Ensure servers and services remain in a consistent desired state by applying configuration playbooks across fleets of hosts. |
| Application Deployment | Deploy and update applications across development, staging, and production environments with zero-downtime rolling strategies. |
| Cloud Provisioning | Provision cloud resources on AWS, Azure, GCP, and other providers using cloud-specific Ansible modules and dynamic inventory. |
| Network Automation | Configure routers, switches, and firewalls from Cisco, Juniper, Arista, and Palo Alto using vendor-specific Ansible collections. |
| Security and Compliance | Enforce security baselines, CIS benchmarks, and STIG compliance across infrastructure using Ansible hardening playbooks. |

## Integrations

| Name | Description |
|------|-------------|
| Red Hat Enterprise Linux | Ansible is the primary configuration management tool for RHEL systems with deep integration into the Red Hat platform. |
| Kubernetes / OpenShift | Manage Kubernetes clusters, namespaces, deployments, and OpenShift workloads using the kubernetes.core collection. |
| Terraform | Combine Terraform for cloud resource provisioning with Ansible for post-provisioning OS and application configuration. |
| Jenkins / GitHub Actions | Integrate Ansible playbook execution into CI/CD pipelines using the AAP Action for GitHub or Ansible Tower Plugin for Jenkins. |
| ServiceNow | Trigger Ansible automation from ServiceNow ITSM workflows using the ServiceNow ITX collection for change management automation. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Playbook Schema](json-schema/ansible-playbook-schema.json)

### JSON Structure

- [Playbook Structure](json-structure/ansible-playbook-structure.json)

### JSON-LD

- [Ansible Context](json-ld/ansible-context.jsonld)

### Examples

- [Playbook Example](examples/ansible-playbook-example.json)

## Vocabulary

- [Ansible Vocabulary](vocabulary/ansible-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 10 actions, and 4 APIs across the Ansible open-source platform

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
