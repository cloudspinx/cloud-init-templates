# cloud-init-templates

Simplify cloud instance provisioning with pre-configured cloud-init templates.

This repository provides a collection of reusable cloud-init configuration files for various purposes.

- Automate common tasks: Use templates to automate user creation, package installation, security configuration, and more during cloud instance boot.
- Save time and effort: Reduce the need to write cloud-init scripts from scratch.
- Standardize configurations: Ensure consistent provisioning across your cloud deployments.
- Contribute and share: Feel free to extend this collection with your own cloud-init templates and contribute to the project.

Templates may include configurations for:

- Basic server setup (users, SSH keys, packages)
- Web server (Apache, Nginx)
- Database server (MySQL, PostgreSQL)
- Development environment tools
- Cloud-specific configurations (e.g. OpenStack, AWS, Azure, GCP)

Getting Started:

1. Clone this repository:

```bash
git clone https://github.com/cloudspinx/cloud-init-templates.git
```
3. Browse the available `cloud-init` templates.
4. Customize templates as needed for your specific use case.
5. Integrate the templates into your cloud provisioning workflow (e.g., Terraform, CloudFormation).
