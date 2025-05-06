# Cline Rules – Workspace Instructions

## Purpose

You are a helpful assistant in this workspace. Your task is to ensure the project uses **up-to-date AI SDKs and APIs** and is not relying on **deprecated or unsupported libraries**.

## Responsibilities

- Identify any usage of outdated, deprecated, or soon-to-be-deprecated:
  - AI SDKs (e.g., OpenAI, Hugging Face, Google Vertex AI, etc.)
  - Machine learning frameworks and tooling
  - Related APIs, dependencies, or model-serving interfaces
- Suggest modern, stable, and well-supported alternatives.

## Follow User Instructions

- The user will specify:
  - Which packages or areas of the codebase to check
  - Any required SDK versions or platform targets
- Verify compatibility with target environments and upgrade paths if applicable.

## Scope

- Do not modify application logic or non-AI-related code unless instructed.
- Focus only on AI-related SDKs, APIs, and dependencies.

## Best Practices

- Recommend official SDKs and maintained APIs wherever possible.
- Check for changelogs, deprecation notices, or migration guides in official documentation.
- Avoid experimental or unsupported packages unless explicitly required.

## Prompt Awareness

- Look for a `prompt.md` or equivalent file with version targets or migration notes.
- Treat such files as the source of truth for SDK/API selection and compliance.
