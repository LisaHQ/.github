# LISA

> **Local Intelligent System Assistant**
>
> A privacy-first, local-first AI ecosystem for intelligent environments.

---

## What is LISA?

LISA (**Local Intelligent System Assistant**) is an open AI ecosystem designed to become the intelligent operating layer for smart homes, infrastructure, and future connected environments.

Unlike traditional assistants that depend heavily on cloud services, LISA prioritizes:

* Local autonomy
* Privacy
* Reliability
* Ownership
* Long-term maintainability

LISA is not just a chatbot.

LISA is not just a voice assistant.

LISA is not just a home automation platform.

LISA is an intelligent system capable of understanding, coordinating, monitoring, and improving the environment around it while remaining under the owner's control.

---

## Why LISA Exists

Modern smart-home and AI ecosystems are fragmented.

Users often manage:

* Smart-home platforms
* Voice assistants
* Cameras
* Networking equipment
* Automation engines
* Cloud AI services
* Local AI models

Each system operates independently.

LISA exists to unify them.

The goal is to create a single intelligent layer capable of reasoning across an entire environment rather than individual devices.

---

## Core Principles

### Local First

LISA should continue operating even when cloud services become unavailable.

Core functionality should not depend on external providers.

---

### Privacy First

Your environment.

Your data.

Your control.

Sensitive information should remain local whenever practical.

---

### Intelligence First

Automation is a feature.

Intelligence is the objective.

LISA focuses on:

* Understanding
* Context
* Planning
* Coordination
* Decision support

rather than simple rule execution.

---

### Recovery First

Complexity should never compromise recoverability.

LISA prioritizes:

```text
Recovery > High Availability > Complexity
```

Systems should be easy to restore, rebuild, and maintain.

---

### Open Architecture

LISA is designed as a collection of modular components.

Every layer should remain replaceable and independently deployable.

---

## Ecosystem Overview

```text
                            LISA
             Local Intelligent System Assistant

                              │
      ┌───────────────────────┼───────────────────────┐
      │                       │                       │
      ▼                       ▼                       ▼

  LISA Brain            LISA Vision           LISA Voice

      │                       │                       │
      └───────────────┬───────┴───────┬───────────────┘
                      │               │
                      ▼               ▼

                 LISA Core      LISA Integrations

                      │
                      ▼

                   LISA Edge

                      │

      ┌───────────────┼────────────────────┐
      │               │                    │

   Matter          Thread               MQTT
   UniFi           Homey          Home Assistant
```

---

## Components

### LISA Edge

Provides the infrastructure foundation of the ecosystem.

Responsibilities include:

* Networking
* Messaging
* Connectivity
* Service discovery
* VPN access
* Infrastructure services
* Operational resilience

Repository:

```text
lisa-edge
```

---

### LISA Brain

The intelligence layer.

Responsibilities include:

* Reasoning
* Planning
* Memory
* Context management
* Decision making
* Tool orchestration

Repository:

```text
lisa-brain
```

---

### LISA Vision

The perception layer.

Responsibilities include:

* Camera processing
* Event understanding
* Object detection
* Video intelligence

Repository:

```text
lisa-vision
```

---

### LISA Voice

The conversational layer.

Responsibilities include:

* Wake words
* Speech recognition
* Speech synthesis
* Natural interaction

Repository:

```text
lisa-voice
```

---

## Design Philosophy

LISA is designed around environments rather than devices.

Instead of controlling individual components, LISA aims to understand and coordinate entire systems.

Examples include:

* Smart homes
* Offices
* Labs
* Multi-site environments
* Edge infrastructure
* Future robotics platforms

The architecture intentionally avoids dependence on any specific:

* Hardware vendor
* Cloud provider
* Smart-home platform
* AI model

---

## Infrastructure Philosophy

Preferred technologies include:

* Docker Compose
* Git-managed configuration
* Infrastructure as Code
* Portable backups
* Reproducible deployments

LISA favors practical engineering over unnecessary complexity.

---

## Current Integrations

Current and planned integrations include:

* Matter
* Thread
* MQTT
* UniFi
* Home Assistant
* Homey
* WireGuard
* Headscale
* Netmaker

and future ecosystem integrations.

---

## Status

LISA is currently under active development.

The ecosystem is evolving toward a modular architecture consisting of independent components that can be deployed separately or together.

---

## Vision

The long-term goal of LISA is simple:

> Build an intelligent system that understands and improves its environment while remaining private, local, reliable, and entirely under the owner's control.

---

## LisaHQ

LISA is developed under the **LisaHQ** organization.

```text
LisaHQ/
├── lisa-core
├── lisa-edge
├── lisa-brain
├── lisa-vision
├── lisa-voice
└── lisa-docs
```

---

## License

License information will be published as repositories mature.
