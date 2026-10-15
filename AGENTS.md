# Repository Agent Instructions

Apply the required [workspace instructions](../../AGENTS.md). The rules below are this repository's delta and override shared rules on conflict.

This repository contains Vanessa Automation UI scenarios for Kafka Adapter. Current scenarios and test results are primary evidence of test behavior.

- Edit Vanessa feature files and other non-1C test configuration directly in UTF-8; do not use EDT for them.
- Preserve existing Gherkin language, naming, indentation, fixtures, and scenario style.
- Run only affected features or scenarios through a command documented by this repository when the environment is available.
- Do not change product source without explicit multi-repository scope.
- For Vanessa MCP research, scenario updates, execution and debugging, use `$vanessa-ui-tests` with this repository's local profile. The initial setup check uses form-opening scenarios; `013_Справочники_Запись.feature` changes existing data and requires a specific fixture/state strategy before execution on the main base.
- Always launch the test manager and TestClient in the Taxi interface (`/iTaxi`).
