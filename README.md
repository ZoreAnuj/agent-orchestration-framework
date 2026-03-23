# Agent Orchestration Framework

A Kubernetes-native framework for orchestrating autonomous AI coding agents. It provides a scalable, declarative approach to managing multi-agent workflows, enabling teams to automate complex development tasks with reliability and observability.

## Key Features
- Declarative agent workflows defined via Kubernetes Custom Resources
- Built-in support for popular LLM providers and vector databases
- Horizontal scaling of agent pods with health monitoring
- Persistent conversation history and state management

## Tech Stack
- Kubernetes, Custom Resource Definitions (CRDs)
- Go, Python
- PostgreSQL, Redis
- OpenTelemetry for observability

## Getting Started
```bash
git clone https://github.com/zoreanuj/agent-orchestration-framework.git
cd agent-orchestration-framework
kubectl apply -f deploy/manifests/
```