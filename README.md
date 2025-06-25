# Cursor Rules Configuration

Modular `.cursorrules` files for consistent AI-assisted development across projects.

## Files

- `.cursorrules` - Main file that references the modules below
- `.cursorrules_best_practices` - Code quality, testing, and development best practices  
- `.cursorrules_hallucinations` - Accuracy requirements and hallucination prevention rules

## Usage

Copy all files to your project root:

```bash
curl -L \
  -O https://raw.githubusercontent.com/arnoldcano/cursorrules/main/.cursorrules \
  -O https://raw.githubusercontent.com/arnoldcano/cursorrules/main/.cursorrules_best_practices \
  -O https://raw.githubusercontent.com/arnoldcano/cursorrules/main/.cursorrules_hallucinations
```

That's it! Your project now has comprehensive AI assistant rules.

## Sources

These rules are derived from official Anthropic documentation:

- **Best Practices**: [Claude 4 prompt engineering best practices](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/claude-4-best-practices)
- **Hallucination Prevention**: [Reduce hallucinations](https://docs.anthropic.com/en/docs/test-and-evaluate/strengthen-guardrails/reduce-hallucinations) 