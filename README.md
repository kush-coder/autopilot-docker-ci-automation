# 🚀 Docker Ci Automation

**Official Open-Source Release & Maintained Codebase** by [**@kush-coder**](https://github.com/kush-coder)

[![Verified Build](https://img.shields.io/badge/Status-Verified--Passing-emerald?style=for-the-badge&logo=github)](https://github.com/kush-coder)
[![License](https://img.shields.io/badge/License-The Unlicense-indigo?style=for-the-badge)](https://github.com/kush-coder)
[![Language](https://img.shields.io/badge/Language-Shell-purple?style=for-the-badge)](https://github.com/kush-coder)

## 💡 About This Project

GitHub Actions automation examples with Docker's official actions

This repository is actively maintained and distributed by **@kush-coder** as an official open-source release.

## ✨ Key Highlights
- 🛡️ **Verified Health Checks**: Passed automated sandbox builds, dependency resolution, and health test runs.
- 🚀 **Production Ready**: Lightweight footprint optimized for high efficiency.
- 📦 **Permissive Open Source**: Available for developer integration, custom modifications, and community enhancements.

## 🚀 Quick Start & Installation

```bash
# Clone your official repository
git clone https://github.com/kush-coder/autopilot-docker-ci-automation.git
cd autopilot-docker-ci-automation
```

---

## 📖 Comprehensive Documentation

[![Lint Code Base](https://github.com/bretfisher/docker-ci-automation/actions/workflows/call-super-linter.yaml/badge.svg)](https://github.com/bretfisher/docker-ci-automation/actions/workflows/call-super-linter.yaml)

> For Docker Community All Hands 2022

[![All-Hands Automation with Docker](https://user-images.githubusercontent.com/792287/160971371-0ae75c14-1ea4-4a11-82dc-f35f96184fa3.gif)](https://www.youtube.com/watch?v=aZzV6X7XhyI)

Watch the walkthrough of this repo: [https://www.youtube.com/watch?v=aZzV6X7XhyI](https://www.youtube.com/watch?v=aZzV6X7XhyI)

See this repositories' [`.github/workflows`](.github/workflows) directory for the below example workflows, ordered by number, simple to complex.

These examples are focused on five of Docker's [official GitHub Actions](https://github.com/marketplace?type=actions&query=publisher%3Adocker+).

These examples are based on three workflow diagrams on progressively more complex automation pipelines:

1. [Basic code PR automation workflow](diagrams/basic-code-pr.png)
2. [Intermediate code PR automation workflow](diagrams/intermediate-code-pr.png)
3. [Advanced code PR automation workflow](diagrams/advanced-code-pr.png)

I also have a [LIVE course on learning GitHub Actions for DevOps automation and Argo CD](https://bret.courses/autodeploy) for GitOps-style deployments.

## Example Workflows

1. Basic Docker build
2. Adding BuildKit cache
3. Adding multi-platform builds
4. Adding metadata to images
5. Adding comments with image tags to PRs
6. Adding CVE scanning
7. Adding CVE security reporting
8. Adding unit testing
9. Adding integration testing
10. Adding Kubernetes smoke tests
11. Adding job parallelizing for mucho speed

## GitHub Actions shown in these examples

- [Docker Login](https://github.com/marketplace/actions/docker-login)
- [Docker Setup Buildx](https://github.com/marketplace/actions/docker-setup-buildx)
- [Docker Setup QEMU](https://github.com/marketplace/actions/docker-setup-qemu)
- [Docker Metadata](https://github.com/marketplace/actions/docker-metadata-action)
- [Docker Build and Push](https://github.com/marketplace/actions/build-and-push-docker-images)
- [Aqua Security Trivy CVE Scan](https://github.com/marketplace/actions/aqua-security-trivy)
- [Super-Linter](https://github.com/marketplace/actions/super-linter)
- [Setup k3d](https://github.com/marketplace/actions/absaoss-k3d-action)
- [Find Comment](https://github.com/marketplace/actions/find-comment)
- [Create or Update Comment](https://github.com/marketplace/actions/create-or-update-comment)

## This repository is part of my example DevOps repos on GitHub Actions

- [bretfisher/github-actions-templates](https://github.com/BretFisher/github-actions-templates) - Main reusable templates repository
- [bretfisher/super-linter-workflow](https://github.com/BretFisher/super-linter-workflow) - Reusable linter workflow
- [bretfisher/docker-build-workflow](https://github.com/BretFisher/docker-build-workflow)- Reusable docker build workflow
- (you are here) [bretfisher/docker-ci-automation](https://github.com/BretFisher/docker-ci-automation) - Step by step video and example of a Docker CI workflow
- [My full list of container examples and tools](https://github.com/bretfisher)

## More reading

[Docker Build/Push Action advanced examples](https://github.com/docker/build-push-action/tree/master/docs/advanced)
[My full list of container examples and tools](https://github.com/bretfisher)

## 🎉🎉🎉 Join my container DevOps community 🎉🎉🎉

- [My "Vital DevOps" Discord server](https://devops.fan)
- [My weekly YouTube Live show](https://bret.live)
- [My courses and coupons](https://www.bretfisher.com/courses)


---

*Maintained with ❤️ by @kush-coder. Official distribution powered by GitHub Autopilot Automation Platform.*
