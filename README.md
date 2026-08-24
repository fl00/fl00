# Hi there, I'm Florian Lamboley

**Executive Technical Director (CTO) | Enterprise Architect | COMEX Member**

Based in Paris, France 🇫🇷. With over 15 years of experience in executive technical leadership, I bridge the gap between business strategy and robust software engineering. 

My daily focus is on designing, urbanizing, and scaling complex Information Systems to achieve High Availability (HA) and enterprise-grade resilience. I believe that sound architecture is not about chasing the latest hype, but about finding the most pragmatic, maintainable, and proportionate solution to a business problem.

---

### Core Expertise: Enterprise Architecture & Cloud

*   **IS Urbanization & High Availability:** Structuring complex enterprise landscapes, decoupled architectures, and fault-tolerant systems designed for scale and resilience.
*   **Cloud Infrastructure (Microsoft Azure):** Extensive experience in designing Azure-centric topologies (Azure API Management, Service Bus, Azure Functions, Entra External ID).
*   **Enterprise Web Stacks & Performance:** Advanced caching strategies (Varnish, Redis, PHP-FPM) and scalable architectures for major web platforms (Drupal, Ibexa).
*   **Tech Leadership:** Structuring engineering teams, technical governance, PoC evaluations (including AI coding tools), and driving architectural roadmaps.

---

### My Engineering Philosophy
> *"Complexity is a liability. Pragmatism is a feature."*

Whether I am designing a cloud-native enterprise system or writing bare-metal firmware, my principles remain the same:
1.  **Simplicity First:** Avoid over-engineering. The best system is the one that is easy to reason about and maintain.
2.  **Mechanical Sympathy:** Software should respect the hardware it runs on.
3.  **Strict Contracts:** Strongly typed, versioned data contracts guarantee system stability over time.

---

### The Laboratory (Featured Side Project)

**[Zero-Bloat Bare-Metal IoT Platform](https://github.com/fl00/iot-airquality-platform)**

To push my architectural philosophy to its limits, I maintain a side project exploring extreme memory efficiency, mechanical sympathy, and zero-allocation data streams. It is a playground for pragmatic performance:

*   **The Goal:** An end-to-end, enterprise-grade IoT Air Quality monitoring architecture running entirely on **less than 60MB of RAM**.
*   **The Stack & Architecture Decisions (ADRs):**
    *   **Edge:** C/C++ ESP32 firmware using strictly static memory allocation (Nanopb) and Protobuf v3 binary serialization over MQTT.
    *   **Backend:** A Rust Telemetry Ingestion Hub (Tokio) acting as the sole MQTT subscriber. It handles micro-batching and circuit breaking before writing to **InfluxDB** for persistent time-series storage.
    *   **Frontend:** A Server-Driven UI built with **FastHTML (Python)** and HTMX. Live telemetry is broadcasted via an **ultra-compact 16-byte binary SSE stream**, decoded natively via JS DataView into pre-allocated TypedArrays for **Zero-GC Canvas rendering** (uPlot) at 60 FPS.
*   **Why it matters:** It demonstrates how enterprise concepts (Circuit Breakers, Decoupling, local IPC broadcasts, and Defense-in-Depth) can be applied elegantly without container bloat or heavy web frameworks. Read the **Architecture Decision Records (ADRs)** in the repo to explore the engineering trade-offs.

---

### Tech Stack & Tools

**Enterprise & Cloud Architecture**
<p align="left">
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Drupal-0678BE?style=for-the-badge&logo=drupal&logoColor=white" alt="Drupal" />
</p>

**Performance Laboratory & Side Projects**
<p align="left">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/HTMX-336699?style=for-the-badge&logo=html5&logoColor=white" alt="HTMX" />
</p>

---

### Let's Connect

- [LinkedIn](https://www.linkedin.com/in/florianlamboley/)
