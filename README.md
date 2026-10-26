# Ansible (ansible)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ansible is an open-source IT automation platform developed by Red Hat that provides agentless configuration management, application deployment, cloud provisioning, and orchestration. Using YAML-based playbooks and an SSH-native architecture, Ansible automates infrastructure at scale without requiring agents or custom security infrastructure on managed nodes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/apis.yml)

## Tags

- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure As Code
- Open Source
- Orchestration
- Red Hat

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Ansible Automation Platform API

RESTful API for Ansible Automation Platform (formerly Ansible Tower) that provides programmatic access to job templates, inventories, credentials, workflow templates, schedules, notifications, and job execution. Supports OAuth2 authentication and delivers a comprehensive management interface for enterprise-scale Ansible deployments.

- **Human URL:** [https://docs.ansible.com/automation-controller/latest/html/controllerapi/](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)
- **Base URL:** `https://your-controller-host/api/v2/`

#### Tags

- Ansible
- Automation
- Enterprise
- Inventories
- Jobs
- Red Hat
- Workflows

#### Properties

- [Documentation](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)
- [API Reference](https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html)
- [Authentication](https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html)
- [Getting Started](https://docs.ansible.com/automation-controller/latest/html/quickstart/)
- [Postman Collection](collections/ansible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWX API

AWX is the open-source upstream project for Ansible Automation Platform, providing a web-based UI, REST API, and task engine for Ansible under the Apache 2.0 license. The AWX API mirrors the AAP API surface for job management, inventory, credentials, workflow templates, and scheduling.

- **Human URL:** [https://github.com/ansible/awx](https://github.com/ansible/awx)
- **Base URL:** `https://your-awx-host/api/v2/`

#### Tags

- Ansible
- Automation
- AWX
- Jobs
- Open Source

#### Properties

- [Documentation](https://ansible.readthedocs.io/projects/awx/en/latest/)
- [API Reference](https://github.com/ansible/awx/blob/devel/docs/rest_api.md)
- [GitHub Repository](https://github.com/ansible/awx)
- [Getting Started](https://github.com/ansible/awx/blob/devel/INSTALL.md)
- [Postman Collection](collections/ansible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Galaxy API

REST API for Ansible Galaxy — the community hub for sharing and downloading Ansible roles and collections. The v1 API covers roles and the v3 API covers collections with namespace management, versioning, search, and content download capabilities.

- **Human URL:** [https://galaxy.ansible.com/](https://galaxy.ansible.com/)
- **Base URL:** `https://galaxy.ansible.com/api/`

#### Tags

- Ansible
- Collections
- Community
- Galaxy
- Roles

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [API Reference](https://galaxy.ansible.com/api/v3/)
- [GitHub Repository](https://github.com/ansible/galaxy)
- [Postman Collection](collections/ansible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Automation Hub API

The Red Hat Ansible Automation Hub API provides access to certified Ansible collections and roles curated by Red Hat and partners. Available through console.redhat.com, it serves certified content for enterprise Ansible Automation Platform deployments.

- **Human URL:** [https://console.redhat.com/ansible/automation-hub](https://console.redhat.com/ansible/automation-hub)
- **Base URL:** `https://console.redhat.com/api/automation-hub/v3/`

#### Tags

- Ansible
- Certified Content
- Collections
- Enterprise
- Red Hat

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/)
- [API Reference](https://console.redhat.com/api/automation-hub/v3/)
- [Portal](https://console.redhat.com/ansible/automation-hub)
- [Postman Collection](collections/ansible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ansible)
- [Portal](https://www.ansible.com)
- [Getting Started](https://docs.ansible.com/ansible/latest/getting_started/)
- [Documentation](https://docs.ansible.com/)
- [Blog](https://www.ansible.com/blog)
- [GitHub Organization](https://github.com/ansible)
- [Forum](https://forum.ansible.com/)
- [Support](https://access.redhat.com/products/red-hat-ansible-automation-platform/)
- [Training](https://www.ansible.com/products/training-certification)
- [Terms of Service](https://www.redhat.com/en/about/terms-use)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [SDK](https://pypi.org/project/ansible/)
- [SDK](https://pypi.org/project/ansible-runner/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/json-schema/ansible-playbook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ansible/refs/heads/main/vocabulary/ansible-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/ansible/aap-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
