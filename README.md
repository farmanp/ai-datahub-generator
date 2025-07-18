# AI DataHub Generator

This repository expands the minimal **ai-spec-generator** template to focus on
DataHub. It contains YAML taxonomies describing DataHub's entity model,
ingestion framework, metadata lifecycle, and service architecture. Prompt
templates help analyze source code and guide teams on how to apply these
taxonomies.

## Repository layout

- **`specs/`** – YAML specifications for DataHub taxonomies and an example spec.
- **`prompts/`** – Prompt templates for tasks such as ingestion opportunity
  analysis, business glossary creation, entity mapping, and architecture
  assessment.
- **`scripts/`** – Stubs for building generators that consume the specs.
- **`examples/`** – Sample output generated from the prompts and specs.
- **`docs/`** – Additional documentation including the "Getting Started" guide.
- **`templates/`** – A skeleton YAML file for authoring new specs.
- **`tests/`** – Basic tests for the generator scripts.

## Usage

1. Add or edit YAML files in `specs/` using `templates/spec-template.yaml` as a
   starting point.
2. Modify the prompt templates in `prompts/` to suit your DataHub analysis
   needs.
3. Implement your generation logic in `scripts/generate_from_spec.py` and use
   the examples as references.
4. Consult `docs/getting-started.md` for more details and expand the tests in
   `tests/` as functionality grows.

This project is released under the [MIT License](LICENSE).
