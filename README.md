# Book "Kubernetes-and-Helm-A-Primer" - Repository
Official YAML manifests and files for the book titled "Kubernetes and Helm: A Primer"

## 📖 Companion Book
**"Kubernetes and Helm: A Primer"**.
[![Amazon Kindle](https://img.shields.io/badge/Amazon_Kindle-Available_Now-FF9900?style=for-the-badge&logo=amazon)](https://www.amazon.com/dp/B0HQ5QPP5L)

👉 **[Get your copy on Amazon.com](https://www.amazon.com/dp/B0HQ5QPP5L)**

## Repository Structure
This repository contains the configuration files and deployment manifests accompanying the book ***Kubernetes and Helm: A Primer***. Below is an overview of the directory structure and root files:

```text
.
├── conf/         # Kubernetes YAML manifests and Helm values.yaml organized by chapter
├── ERRATA.md     # List of known corrections, updates, and clarifications for the book
├── LICENSE       # Licensing terms for the contents of this repository
├── NOTICE        # Third-party copyright notices and attributions
└── README.md     # This file
```

## Found an Error?
If you notice a typo or a broken command, please submit an issue on this repository or check **[ERRATA.md](ERRATA.md)** for the latest updates.

​Purchasers of this eBook can update to the latest version anytime under "**Manage Your Content and Devices**" on Amazon.


## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Third-Party Attributions & Licenses
This repository contains modified configuration files (values.yaml) based on open-source projects:
- **Bitnami Helm Charts (`values.yaml`)**
  - **Original Copyright**: Copyright Broadcom, Inc. All Rights Reserved.
  - **License**: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
  - **Modifications**: Customized parameters and configuration defaults specifically tuned for the examples in *Kubernetes and Helm: A Primer*.
