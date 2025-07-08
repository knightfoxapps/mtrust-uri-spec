# ModelTrust Protocol (MTP) URI Scheme Specification

This repository contains the official specification for the `mtrust` URI scheme.

The `mtrust` URI scheme is designed for trusted communication between ModelTrust Protocol (MTP) clients and servers. It enables resource identification and command signaling within AI Model Proxy Control (MPC) environments.

---

## 📄 Specification Document

- [mtrust-uri-specification.txt](mtrust-uri-specification.txt)  
  *(Plain text document compliant with RFC7595 and RFC3986)*

---

## 📌 Overview

The `mtrust` URI scheme is used to:
- Identify resources in AI model control systems
- Signal tasks, actions, or requests between trusted participants
- Operate securely under transport encryption and strict access control

---

### Example URI
```plaintext
mtrust://controller.domain.example/task/execute?model_id=xyz123
