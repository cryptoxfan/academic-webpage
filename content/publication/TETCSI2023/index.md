---
title: "Private Delegated Computations Using Strong Isolation"
authors:
- Mathias Brossard
- Guilhem Bryant
- Basma El Gaabouri
- admin
- Alexandre Ferreira
- Edmund Grimley-Evans
- Christopher Haster
- Evan Johnson
- Derek Miller
- Fan Mo
- Dominic P. Mulligan
- Nick Spinale
- Eric van Hensbergen
- Hugo J. M. Vincent
- Shale Xiong

date: "2023-06-01T00:00:00Z"
doi: "10.1109/TETC.2023.3281738"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Technology Innovation Management Review*"
publication_short: ""

abstract: Computations are now routinely delegated to third-parties. In response, Confidential Computing technologies are being added to microprocessors offering a trusted execution environment (TEE) that provides confidentiality and integrity guarantees to code and data hosted within—even in the face of a privileged attacker. TEEs, along with an attestation protocol, permit remote third-parties to establish a trusted “beachhead” containing known code and data on an otherwise untrusted machine. Yet, they introduce many new problems, including how to ease provisioning of computations safely into TEEs; how to develop distributed systems spanning multiple classes of TEE; and what to do about the billions of “legacy” devices without support for Confidential Computing? Tackling these problems, we introduce Veracruz, a pragmatic framework that eases the design and implementation of complex privacy-preserving, collaborative, delegated computations among a group of mutually mistrusting principals. Veracruz supports multiple isolation technologies and provides a common programming model and attestation protocol across all of them, smoothing deployment of delegated computations over supported technologies. We demonstrate Veracruz in operation, on private in-cloud object detection on encrypted video streaming from a video camera. In addition to supporting hardware-backed TEEs—like AWS Nitro Enclaves and Arm® Confidential Computing Architecture Realms—Veracruz also provides pragmatic “software TEEs” on Armv8-A devices without hardware Confidential Computing capability, using the high-assurance seL4 microkernel and our IceCap framework.
---