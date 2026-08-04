# Repository Agent Instructions

## Workspace Instructions

Read the required [workspace instructions](../../AGENTS.md) before working in this repository. The fixed `KAFKA_PROJECTS_ROOT` layout is required. If the shared file is missing, report a workspace-layout error and stop. The repository-specific rules below supplement and override the shared rules when they conflict.

## Repository Scope

This repository contains Vanessa Automation UI scenarios for Kafka Adapter. Start with [README.md](README.md). Current scenarios and test results are primary evidence of test behavior.

## Repository-Specific Rules

- Edit Vanessa feature files and other non-1C test configuration directly in UTF-8.
- Preserve existing Gherkin language, naming, indentation, fixtures, and scenario style.
- Do not use EDT to edit Vanessa feature files.
- Run only affected features or scenarios through the existing project workflow when the environment is available.
- Do not invent a runner command that is absent from README, CI, or existing scripts.
- Do not change product source from a test task without explicit multi-repository scope.

