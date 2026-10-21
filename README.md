<!-- portfolio-strip:start (brief 40) -->
<sub>**Brendan Lynskey** · [Portfolio home](https://brendanjameslynskey.github.io/) · [Interactive sites](https://brendanjameslynskey.github.io/#sites)</sub>
<!-- portfolio-strip:end -->

# CI/CD & DevOps — Series Hub

From a pull request to production: GitHub, continuous integration with GitHub Actions and Jenkins, Docker from the first image to orchestration, deploying web apps and microservices, and the cloud service models underneath.

**Live index:** https://brendanjameslynskey.github.io/SW_Hub_CI_CD_DevOps/

**Who this is for.** Developers who want to ship safely and repeatably, and engineers moving from hand-run builds to pipelines and containers.

**How to use it.** Read in order for a course, or jump in. The CI decks use real runs: every GitHub Actions demo workflow ran in its repo, and the Jenkins deck's screenshots come from a local Jenkins.

## The reading order

### Part 1: Source control and CI

Where the code lives, and the pipelines that check every change.

| # | Title | Description |
| --- | --- | --- |
| 01 | [Introduction to GitHub](https://brendanjameslynskey.github.io/Introduction_to_GitHub/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_GitHub/blob/main/presentation.md)) | Interactive presentation on GitHub — repositories, pull requests, Actions, GitHub CLI, security features, Copilot, GitLab comparison, and alternative platforms |
| 02 | [Introduction to CI/CD](https://brendanjameslynskey.github.io/Introduction_to_CI_CD/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_CI_CD/blob/main/presentation.md)) | Pipelines, quality gates, protecting `main`, CI across repos, deploying safely (migrations, smoke checks, health endpoints), observability and DORA metrics, with a Key terms glossary of every CI/CD term used on this GitHub |
| 03 | [Introduction to GitHub Actions](https://brendanjameslynskey.github.io/Introduction_to_GitHub_Actions/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_GitHub_Actions/blob/main/presentation.md)) | Workflows, triggers, matrices, caching, artifacts, reusable workflows and custom actions, least-privilege tokens, environments, OIDC, script injection, debugging, rulesets and required checks, with every demo workflow run for real |
| 04 | [Introduction to Jenkins](https://brendanjameslynskey.github.io/Introduction_to_Jenkins/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_Jenkins/blob/main/presentation.md)) | Controller and agents, plugins, declarative and scripted pipelines, credentials, test reports, shared libraries and security, and Jenkins against GitHub Actions and GitLab CI, with screenshots and pipelines from a real local Jenkins |

### Part 2: Containers

Docker from the first image to a cluster.

| # | Title | Description |
| --- | --- | --- |
| 05 | [Deploying with Docker](https://brendanjameslynskey.github.io/Deploying_with_Docker/) ([md](https://github.com/BrendanJamesLynskey/Deploying_with_Docker/blob/main/presentation.md)) | Interactive presentation on Docker and containers — Dockerfiles, Compose, registries, Kubernetes basics, and cloud container hosting |
| 06 | [Docker Networking](https://brendanjameslynskey.github.io/Docker_Networking/) ([md](https://github.com/BrendanJamesLynskey/Docker_Networking/blob/main/presentation.md)) | Interactive presentation on Docker networking — bridge, host, overlay, macvlan, DNS resolution, port mapping, network isolation, and production patterns |
| 07 | [Docker Volumes & Storage](https://brendanjameslynskey.github.io/Docker_Volumes_and_Storage/) ([md](https://github.com/BrendanJamesLynskey/Docker_Volumes_and_Storage/blob/main/presentation.md)) | Interactive presentation on Docker storage — named volumes, bind mounts, tmpfs, volume drivers, backup strategies, storage drivers, and database persistence |
| 08 | [Docker Compose in Depth](https://brendanjameslynskey.github.io/Docker_Compose_in_Depth/) ([md](https://github.com/BrendanJamesLynskey/Docker_Compose_in_Depth/blob/main/presentation.md)) | Interactive presentation on Docker Compose — services, networks, volumes, profiles, watch mode, multi-environment configs, scaling, and YAML anchors |
| 09 | [Docker Multi-Stage Builds](https://brendanjameslynskey.github.io/Docker_Multi_Stage_Builds/) ([md](https://github.com/BrendanJamesLynskey/Docker_Multi_Stage_Builds/blob/main/presentation.md)) | Interactive presentation on multi-stage builds — FROM AS syntax, distroless images, BuildKit cache mounts, layer optimisation, and language-specific patterns |
| 10 | [Docker Security](https://brendanjameslynskey.github.io/Docker_Security/) ([md](https://github.com/BrendanJamesLynskey/Docker_Security/blob/main/presentation.md)) | Interactive presentation on Docker security — image scanning, non-root users, secrets, capabilities, seccomp, AppArmor, rootless Docker, and CIS benchmarks |
| 11 | [Docker for CI/CD](https://brendanjameslynskey.github.io/Docker_for_CI_CD/) ([md](https://github.com/BrendanJamesLynskey/Docker_for_CI_CD/blob/main/presentation.md)) | Interactive presentation on Docker in CI/CD — GitHub Actions, GitLab CI, Jenkins, image tagging, layer caching, security scanning, and deployment strategies |
| 12 | [Docker Troubleshooting](https://brendanjameslynskey.github.io/Docker_Troubleshooting/) ([md](https://github.com/BrendanJamesLynskey/Docker_Troubleshooting/blob/main/presentation.md)) | Interactive presentation on Docker troubleshooting — exit codes, logs, exec debugging, inspect, networking issues, volume permissions, and debugging tools |
| 13 | [Docker Swarm & Orchestration](https://brendanjameslynskey.github.io/Docker_Swarm_and_Orchestration/) ([md](https://github.com/BrendanJamesLynskey/Docker_Swarm_and_Orchestration/blob/main/presentation.md)) | Interactive presentation on Docker Swarm — cluster setup, services, overlay networking, rolling updates, stacks, secrets, scaling, and Swarm vs Kubernetes |
| 14 | [Docker for LLMs, Agents & MCP](https://brendanjameslynskey.github.io/Docker_for_LLMs_and_Agents/) ([md](https://github.com/BrendanJamesLynskey/Docker_for_LLMs_and_Agents/blob/main/presentation.md)) | Interactive presentation on Docker for AI — Ollama, vLLM, GPU passthrough, LangChain/CrewAI agents, MCP servers, MCP gateways, and production inference patterns |

### Part 3: Deploying

Getting an application in front of users.

| # | Title | Description |
| --- | --- | --- |
| 15 | [Deploying Web Applications](https://brendanjameslynskey.github.io/Deploying_Web_Applications/) ([md](https://github.com/BrendanJamesLynskey/Deploying_Web_Applications/blob/main/presentation.md)) | Interactive presentation on deploying web apps — static hosting, PaaS, cloud providers, DNS, HTTPS, and deployment strategies for free and paid access |
| 16 | [Deploying Node.js Microservices](https://brendanjameslynskey.github.io/Deploying_Node_Microservices/) ([md](https://github.com/BrendanJamesLynskey/Deploying_Node_Microservices/blob/main/presentation.md)) | Interactive presentation on deploying Node.js microservices — service design, containerisation, inter-service communication, Kubernetes, AWS, and production observability |

### Part 4: Cloud

The service models the deployments run on, in their own series.

| # | Title | Description |
| --- | --- | --- |
| 17 | [Cloud `*aaS` Hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub) | Series index — links to all six decks plus related existing material |

## Related

- [uv in Practice](https://brendanjameslynskey.github.io/uv_in_Practice/) — Python packaging recipes for Docker and CI
- [CI/CD: interview preparation](https://github.com/BrendanJamesLynskey/Interview_CI_CD) — Pipelines, deployment strategies and supply-chain security
- [DevOps: interview preparation](https://github.com/BrendanJamesLynskey/Interview_DevOps) — CI/CD, containers, infrastructure as code and monitoring
- [Containers and Kubernetes: interview preparation](https://github.com/BrendanJamesLynskey/Interview_Containers_Kubernetes) — From Docker internals to Operators and GitOps
- [Observability and SRE: interview preparation](https://github.com/BrendanJamesLynskey/Interview_Observability_SRE) — SLOs, incident response and chaos engineering

## Where this fits

Part of the [Software](https://github.com/BrendanJamesLynskey/Software) index, which keeps a short entry for every item listed here. 17 entries; the descriptions are taken from that index, some shortened.
