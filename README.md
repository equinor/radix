![radix](./images/radix-2x3.jpg)
# 🌐 Radix — Open Source Portal

*Your single entry point into the Radix open‑source ecosystem 🚀*

Welcome to the **Radix Open Source Portal** — the central directory for all Radix open‑source projects, tools, libraries, and reference implementations related to Radix.  
Instead of navigating repo jungles 🌴, you now have one clean, friendly, “we‑promise‑this-is-organised” overview.

***

## 📖 Table of Contents

1.  About This Portal
2.  What Is Radix?
3.  Repository Index
    *   Core Repositories
    *   Tools & Utilities
    *   Integrations
    *   Examples & Templates
4.  How to Contribute
5.  Community & Support
6.  License

***

## 🧭 About This Portal

This repository acts as the **navigation hub** for the Radix open‑source ecosystem.  
Here you will find:

*   🔗 Direct links to all Radix-related repositories
*   📘 Short descriptions of each project
*   🧭 Clear organisation by category and purpose
*   🆕 Updates as new repos are released
*   🤝 Contribution info for open‑source collaborators

Basically: this repo is your **tour guide** through the Radix code universe ✨ (sadly without the headset and umbrella).

***

## ⚙️ What Is Radix?

Radix is a **platform for automated application operations**, enabling teams to deploy, run, and maintain applications with minimal friction.  
By focusing on simplicity, scalability, and developer experience, Radix helps teams deliver reliable software faster — without reinventing the Ops wheel 🔧.

***

## 📦 Repository Index

### Core Platform
- [Radix Operator](https://github.com/equinor/radix-operator) — The core Kubernetes operator that manages Radix workloads, deployments, and platform resources
- [Radix API](https://github.com/equinor/radix-api) — REST API exposing platform capabilities to users, services, and the web console
- [Radix Web Console](https://github.com/equinor/radix-web-console) — Web-based GUI for creating, managing, and monitoring Radix applications
- [Radix CLI](https://github.com/equinor/radix-cli) — Command-line interface for interacting with the Radix platform
- [Radix Platform](https://github.com/equinor/radix-platform) — Base infrastructure scripts, Terraform/HCL configs, and platform setup
- [Radix Common](https://github.com/equinor/radix-common) — Shared Go library with common logic used across Radix system applications
- [Radix Log API](https://github.com/equinor/radix-log-api) — API for accessing historical logs for Radix applications

### CI/CD
- [Radix Image Builder](https://github.com/equinor/radix-image-builder) — Container image builder for Radix application pipelines
- [Radix BuildKit Builder](https://github.com/equinor/radix-buildkit-builder) — BuildKit-based image builder for improved build performance
- [Radix GitHub Webhook](https://github.com/equinor/radix-github-webhook) — Webhook handler that triggers Radix pipelines from GitHub push events

### Security
- [Radix OAuth Guard](https://github.com/equinor/radix-oauth-guard) — Forward auth service to validate, authenticate, and authorize JWT tokens
- [Radix Vulnerability Scanner](https://github.com/equinor/radix-vulnerability-scanner) — Scans container images in RadixDeployments for security vulnerabilities
- [Radix Vulnerability Scanner API](https://github.com/equinor/radix-vulnerability-scanner-api) — API for querying and serving vulnerability scan results

### Infrastructure & Operations
- [Radix Flux](https://github.com/equinor/radix-flux) — GitOps configuration for Radix clusters using Flux CD
- [Radix Ingress Default Backend](https://github.com/equinor/radix-ingress-default-backend) — Default backend for ingress-nginx in Radix clusters
- [Radix NetworkPolicy Canary](https://github.com/equinor/radix-networkpolicy-canary) — Canary service for verifying network policy enforcement
- [Radix CI/CD Canary](https://github.com/equinor/radix-cicd-canary) — Automated end-to-end testing of the Radix platform inside clusters
- [Radix Prometheus Proxy](https://github.com/equinor/radix-prometheus-proxy) — Exports selected Prometheus query results for monitoring

### Utilities
- [Radix ACR Cleanup](https://github.com/equinor/radix-acr-cleanup) — Cleanup service for removing unused container images from Azure Container Registry
- [Radix Cluster Cleanup](https://github.com/equinor/radix-cluster-cleanup) — CLI for automated cleanup of applications in Radix clusters (playground)
- [Radix Cost Allocation](https://github.com/equinor/radix-cost-allocation) — Exports resource usage and cost data from Prometheus to an external SQL database
- [Radix Cost Allocation API](https://github.com/equinor/radix-cost-allocation-api) — API for querying application cost allocation data


## 🤝 How to Contribute

We ❤️ contributions!  
If you want to help improve Radix, here’s how to get started:

1.  Fork the repository you want to contribute to
2.  Create a feature branch
3.  Commit your changes with meaningful messages
4.  Open a pull request
5.  Enjoy the feeling of making open source better 🎉

For large changes, please open an issue first — so we can discuss the approach.

***

## 🧑‍🤝‍🧑 Community & Support

Need help? Want to get involved?  
You can find us here:

*   🐞 Issue tracker: via individual repositories
*   📧 Contact: issue in this repository

Good vibes guaranteed ✨

***

## 📄 License

This project and all linked repositories are licensed under:  
**MIT License** 

Open, permissive, and collaboration‑friendly — just like we like it 😎


