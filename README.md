# event-guard
Real-time security event processing platform.

## What it does
Takes in security events (failed logins, port scans, malware alerts),
enriches them, detects threats in real time, and raises alerts.

## Architecture (planned)
event-ingestor → Kafka → event-enricher → threat-detector → alert-service

## Tech
Java 25 · Spring Boot 4 · Kafka · Kafka Streams · PostgreSQL · Docker · Kubernetes · Azure (AKS, Event Hubs)

## Status
🚧 In progress — building step by step.