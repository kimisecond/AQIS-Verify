## Ensuring Reliability in ML-Enhanced Industrial Systems: A Formal Verification Approach

![Static Badge](https://img.shields.io/badge/MIT-blue?style=flat&label=license&labelColor=black&color=blue)
![Static Badge](https://img.shields.io/badge/welcome-green?style=flat&label=PRs&labelColor=black&color=green)
![Static Badge](https://img.shields.io/badge/Python-green?style=flat&label=Language&labelColor=black&color=green)
![Static Badge](https://img.shields.io/badge/Lustre-green?style=flat&label=Language&labelColor=black&color=green)

## 📢 Overview

<p align="justify">
As industrial systems increasingly incorporate sophisticated machine learning (ML) components, ensuring their reliability becomes crucial. This paper presents a novel approach that combines a compositional verification framework with formal verification using Kind 2, an SMT-based model checker, applied to an Automated Quality Inspection System (AQIS) for industrial assembly lines. Our AQIS comprises a conveyor belt, cameras, a Vision Transformer-based anomaly detection model, a controller unit, actuators, and a human-machine interface. We formulate and verify four critical properties: Detection Guarantee, False Positive Constraint, Response Correctness, and No Unbounded Delays. The framework aims to identify potential failures resulting from inconsistencies in the ML model's output. Leveraging Kind 2's capabilities for modeling synchronous systems, we create a comprehensive verification environment. We demonstrate our approach on a simulated AQIS, uncovering subtle interactions between the ML component and the overall system that may lead to property violations. This work contributes to the field of verifiable AI in industrial applications, offering a rigorous methodology for analyzing safety-critical systems incorporating ML components.
</p>

## ⭐ Architecture

- WIP

## 🛠️ Usage

- WIP

```bash
$ git clone https://github.com/kimisecond/AQIS-Verify.git
```

As for the installation and detailed usage of Kind 2, please refer to https://kind2-mc.github.io/kind2/

## 🎫 License

This project is under the Apache 2.0 license. See [LICENSE](./LICENSE) for details.
