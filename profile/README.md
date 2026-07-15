<div align="center">

# Talyh Studio

**Technology that works. Games that captivate. Products people trust.**

[![English](https://img.shields.io/badge/Language-English-3D5AFE?style=for-the-badge)](README.md)
[![Русский](https://img.shields.io/badge/Язык-Русский-00B8CC?style=for-the-badge)](README-RU.md)

[Website](https://talyh.com/) · [Support](mailto:support@talyh.com) · [Security](mailto:security@talyh.com)

</div>

---

## We build digital products people trust

Talyh Studio develops software, developer tools, and games. We turn complex ideas into functional, usable, stable, and engaging products through clear design and honest engineering.

Our work is guided by four principles:

| Principle | What it means |
|---|---|
| **Quality & reliability** | Products should behave predictably and remain maintainable over time. |
| **User at the center** | Technology should solve real problems without creating unnecessary friction. |
| **Engineering honesty** | Architecture, limitations, licensing, and data use should be communicated clearly. |
| **Creativity & play** | Useful products can also be expressive, memorable, and enjoyable. |

## What we build

- Desktop software and productivity tools.
- Extensible applications with documented plugin interfaces.
- Developer tools and reusable technical components.
- Games and interactive experiences.
- Cross-platform products for Windows, macOS, Linux, and other supported platforms where applicable.

## Product and licensing model

Some Talyh Studio products use a free-core model:

- the main application is available free of charge;
- selected optional plugins and advanced modules may be licensed separately;
- voluntary product registration may be offered in connection with a contribution to product development;
- registration is not required for the core application unless a specific product explicitly states otherwise.

The application executable, private source code, public plugin ABI/API, official plugins, third-party plugins, and third-party dependencies may use different licenses. Repository-specific `LICENSE`, `NOTICE`, and third-party notice files always take precedence over this overview.

Public plugin ABI/API materials are intended to be published under the **Apache License 2.0**, unless a repository or file states otherwise. This allows independent developers to create free or commercial plugins, including closed-source plugins, subject to applicable licenses and law.

Compatibility with a Talyh Studio product does not by itself mean that a third-party plugin has been reviewed, certified, supported, or endorsed by Talyh Studio.

## Local-first and privacy-conscious

Our text-editor architecture is designed around local document processing and data minimization:

- document contents remain on the user's device and are not transmitted to Talyh Studio by the core application;
- the product does not provide a proprietary cloud document-storage service;
- local filenames, paths, editing history, clipboard contents, and in-document searches are not collected by the core application;
- behavioral advertising identifiers and document-content analytics are not part of the core design;
- voluntary registration is separate from normal document editing.

Where voluntary registration is enabled, an e-mail address may be used to derive a pseudonymous identifier. The recommended design uses **HMAC-SHA-256 with a server-side secret** for the identifier and **Ed25519** separately for signing and verifying registration or license tokens.

Complete EULA, Privacy Policy, and third-party notices are distributed with the relevant product and may also be published on the [Talyh Studio website](https://talyh.com/) or in a dedicated legal repository.

## Repositories and contributions

Public repositories may contain:

- product documentation and release information;
- public plugin ABI/API headers and examples;
- integration guides and sample projects;
- selected open-source tools and reusable libraries;
- issue trackers and public roadmaps where enabled.

Before opening an issue or pull request, review the repository's `README`, `CONTRIBUTING`, `SECURITY`, `LICENSE`, and `NOTICE` files. Do not publish confidential information, personal data, license secrets, or document contents in public issues.

## Support and security

- Product support: [support@talyh.com](mailto:support@talyh.com)
- Security reports: [security@talyh.com](mailto:security@talyh.com)

Please report suspected vulnerabilities privately. Do not disclose an unpatched vulnerability in a public issue.

---

<div align="center">

[![English](https://img.shields.io/badge/Language-English-3D5AFE?style=for-the-badge)](README.md)
[![Русский](https://img.shields.io/badge/Язык-Русский-00B8CC?style=for-the-badge)](README-RU.md)

[Website](https://talyh.com/) · [Support](mailto:support@talyh.com) · [Security](mailto:security@talyh.com)

Copyright © 2026 Talyh Studio. All rights reserved.

Repository licenses do not grant rights to use the Talyh Studio name, logo, or other brand identifiers except where expressly stated.

</div>
