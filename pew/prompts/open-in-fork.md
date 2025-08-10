# Open in Fork

<instruction>
Open the Git repository we just worked on in Fork.
</instruction>

<context>
If it's unclear what to open, ask:
1. This repository
2. Other repository (specify path)
</context>

<constraints>
- Use `fork` CLI command or `open -a Fork`
- Always open repository root, not individual files
- Detect .git directory to find repository root
</constraints>

Execute: `fork {{repository_path}}`