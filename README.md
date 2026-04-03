# GitHub Actions Workflow Templates Store

**Production-tested CI/CD workflows to automate your releases, security, and deployments.**

A curated collection of robust, real-world GitHub Actions workflows designed to accelerate your CI/CD pipeline setup. These templates solve common automation challenges, from monorepo builds to multi-cloud deployments, saving you hours of research and configuration.

## Quick Start

Browse the available workflow templates in the `templates/` directory. Each template includes inline documentation and key configuration points. To use a template:

1. Copy the desired `.yml` file to your repository's `.github/workflows/` directory.
2. Review the inline comments and adjust environment variables, job names, and triggers to match your project.
3. Commit and push the workflow file to trigger it based on its defined events (e.g., push, pull_request, release).

## Usage Examples

The templates cover a range of common scenarios. For instance:

- **Automated Semantic Release:** Automate version bumps, changelog generation, and GitHub releases on every merge to main.
- **Monorepo Build Matrix:** Efficiently build and test only changed packages within a monorepo using path filtering and matrix strategies.
- **Security & Compliance:** Integrated pipelines for SAST, dependency vulnerability scanning, and license compliance checks.
- **Multi-Platform Docker Builds:** Build, tag, and push Docker images for multiple architectures (linux/amd64, linux/arm64) to container registries.
- **Cloud Deployment:** One-click deployment workflows for AWS, Google Cloud, and Azure.

## Features

*   **Production-Proven:** Templates are extracted from and tested in real-world, high-traffic repositories.
*   **Comprehensive Coverage:** Addresses key CI/CD patterns: building, testing, releasing, securing, and deploying.
*   **Clear Documentation:** Each template is heavily commented, explaining the purpose of each step and key configuration options.
*   **Modular Design:** Mix and match workflows to create a pipeline tailored to your stack and needs.
*   **Standardized Best Practices:** Implements GitHub's recommended patterns for caching, artifact management, and job organization.

## Premium Version

These free templates provide a solid foundation. For teams requiring complete, out-of-the-box solutions, consider the **Premium Version** available on [Gumroad](https://gumroad.com/).

The **Premium Version** includes:
*   **Full workflow code** with all secrets and environment variables meticulously documented.
*   A **detailed step-by-step customization guide** for integrating with your specific project structure and tools.
*   **Priority support** for complex setups, monorepo configurations, and troubleshooting.

Purchase individual workflows ($5-12) or the complete **Team Pack** ($39) for access to the entire library.

## License

This project is distributed under the MIT License. See the `LICENSE` file for more information.