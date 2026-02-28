## Project Overview

This project simulates migrating a containerized backend application from a traditional single-server setup to a scalable, self-healing Kubernetes environment.

Rather than simply deploying a container, this platform demonstrates how Kubernetes manages availability, scaling, rolling updates, and configuration changes under realistic operational conditions. The project emphasizes workload resilience, controlled deployments, and infrastructure-level troubleshooting within a local cluster.

The environment is also designed to intentionally test and validate failure scenarios such as scaling misconfigurations, probe failures, and rollout issues to better understand Kubernetes behavior in production-like conditions.

## What This Project Demonstrates
## High Availability Through Replication

Multi-replica Deployment

Automatic pod recreation after deletion

PodDisruptionBudget to protect minimum availability

## Controlled Rolling Updates

Explicit rolling update strategy using maxUnavailable and maxSurge

Verified zero-downtime image upgrades under traffic

Readiness-gated rollout behavior

## Health Probe Management

Liveness probes for container restart logic

Readiness probes to control traffic routing

ConfigMap-driven maintenance mode affecting cluster-wide readiness

## Horizontal Pod Autoscaling (HPA)

CPU-based autoscaling configuration

Load generation to validate scaling behavior

Correct resource request configuration for accurate scaling calculations

## Declarative Configuration

Application configuration externalized using ConfigMaps

Environment variable injection at container startup

Rolling restarts required for configuration updates

## Resource Control & Scheduling

CPU and memory requests/limits defined

Demonstrated interaction between resource limits and autoscaling behavior
