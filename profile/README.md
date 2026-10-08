# 🏛️ CiteLibre

**Open-source digital public services**

CiteLibre is a suite of ready-to-deploy digital services provided by [**Lutece**]([Lutece](https://lutece.paris.fr/)) to help public administrations simplify interactions with citizens and modernize administrative processes.

Built on the open-source Lutece platform, CiteLibre service packs are designed to be **reusable, customizable, and containerized**. Adapt them to your organization's branding, infrastructure, and workflows — without starting from scratch.

🌐 **Website:** [citelibre.org](https://citelibre.org/) · **Documentation:** [Français](https://citelibre.org/fr/) | [English](https://citelibre.org/en/)

---

## ✨ What can you build with CiteLibre?

| Service pack | What it does | Explore |
| --- | --- | --- |
| **📅 RendezVous** | Manage service availability, appointment booking, configurable reservation forms, reminders, and notifications. | [Packaging sources](https://github.com/citelibreorg/packaging/tree/main/citelibre-rendezvous) · [Demo](https://github.com/citelibreorg/demo/tree/main/citelibre-rendezvous) |
| **📝 Service'EZ** | Create configurable online forms and administrative procedures, with workflows for processing and tracking submissions. | [Packaging sources](https://github.com/citelibreorg/packaging/tree/main/citelibre-serviceez) · [Demo](https://github.com/citelibreorg/demo/tree/main/citelibre-serviceez) |
| **🤝 Particip'EZ** | Components for citizen participation and engagement. **Work in progress.** | [Packaging sources](https://github.com/citelibreorg/packaging/tree/main/citelibre-participez) · [Demo](https://github.com/citelibreorg/demo/tree/main/citelibre-participez) |

### Why CiteLibre?

- **100% open source:** inspect, reuse, and adapt the code to your needs.
- **White-label by design:** customize the user experience and branding.
- **Built for public services:** support appointments, online procedures, and citizen engagement.
- **Packaged for deployment:** use container-based setups to simplify evaluation and integration.
- **Powered by Lutece:** build on an established modular platform for digital public services.

## 📦 Our GitHub repositories

| Repository | Purpose |
| --- | --- |
| **[packaging](https://github.com/citelibreorg/packaging)** | Assembles each service pack (Lutece core, plugins, configuration) with Maven and builds its Docker image. |
| **[demo](https://github.com/citelibreorg/demo)** | Runs the service packs locally with Docker Compose: shared platform (Keycloak, Elasticsearch/Kibana, Solr, Matomo…), one compose file per service, and end-to-end tests. |
| **[ops](https://github.com/citelibreorg/ops)** | Deploys CiteLibre on Kubernetes with Yupiik Bundlebee, with helper scripts for a local Minikube. |
| **[.github](https://github.com/citelibreorg/.github)** | Organization profile and GitHub community configuration. |

> **New here?** Start with the [demo repository](https://github.com/citelibreorg/demo) to try the services locally, then look at [packaging](https://github.com/citelibreorg/packaging) to build or customize a service pack.

## 🚀 Getting started

1. **Explore the services** on the [CiteLibre website](https://citelibre.org/).
2. **Clone the repositories** side by side:

   ```bash
   git clone https://github.com/citelibreorg/packaging.git
   git clone https://github.com/citelibreorg/demo.git
   git clone https://github.com/citelibreorg/ops.git
   ```

3. **Build a service pack** and its Docker image by following the [packaging guide](https://github.com/citelibreorg/packaging#readme).
4. **Run it locally** with Docker Compose by following the [demo guide](https://github.com/citelibreorg/demo#readme).
5. **Deploy it on Kubernetes** by following the [ops guide](https://github.com/citelibreorg/ops#readme).
6. **Customize and extend** a service pack for your organization's requirements.

Depending on the pack, the local environment may include components such as Keycloak, Elasticsearch, Solr, or Matomo. Refer to the individual project documentation for the relevant configuration and security requirements.

## 🤝 Contributing

CiteLibre welcomes contributions from developers, public administrations, integrators, and anyone interested in better digital public services.

- **Report bugs or propose improvements:** open an issue in the relevant repository — [packaging](https://github.com/citelibreorg/packaging/issues) (build, service configuration), [demo](https://github.com/citelibreorg/demo/issues) (Docker Compose, e2e tests) or [ops](https://github.com/citelibreorg/ops/issues) (Kubernetes).
- **Discuss ideas and ask questions:** [Join the discussions](https://github.com/citelibreorg/packaging/discussions).
- **Contribute code or documentation:** consult the [contribution guidelines](https://github.com/citelibreorg/.github/blob/main/CONTRIBUTING.md) and open a pull request.
- **Follow community expectations:** read the [Code of Conduct](https://github.com/citelibreorg/.github/blob/main/CODE_OF_CONDUCT.md).
- **Report security vulnerabilities responsibly:** see the [Security Policy](https://github.com/citelibreorg/.github/blob/main/SECURITY.md) instead of publishing sensitive details in a public issue.

## 📚 Useful links

- 🌍 [CiteLibre — official website](https://citelibre.org/)
- 🇫🇷 [CiteLibre — French documentation](https://citelibre.org/fr/)
- 🇬🇧 [CiteLibre — English documentation](https://citelibre.org/en/)
- 🧩 [Lutece platform](https://lutece.paris.fr/)
- 💻 [All CiteLibre repositories](https://github.com/orgs/citelibreorg/repositories)

## ⚖️ License

The CiteLibre [packaging](https://github.com/citelibreorg/packaging/blob/main/LICENSE), [demo](https://github.com/citelibreorg/demo/blob/main/LICENSE) and [ops](https://github.com/citelibreorg/ops/blob/main/LICENSE) repositories are licensed under **BSD 2-Clause**. Consult the `LICENSE` file in each repository for the terms applicable to that project.

---

<div align="center">
  <strong>Building open, reusable digital public services — together.</strong>
  <br />
  <sub>CiteLibre · Powered by Lutece · Open source</sub>
</div>
