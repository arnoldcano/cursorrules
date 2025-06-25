# Cursor Rules Configuration

Modular `.cursorrules` files for consistent AI-assisted development across projects.

## Files

- `.cursorrules` - Main file that references the modules below
- `.cursorrules_best_practices` - Code quality, testing, and development best practices  
- `.cursorrules_hallucinations` - Accuracy requirements and hallucination prevention rules

## Usage

Copy all files to your project root:

```bash
curl -L https://raw.githubusercontent.com/arnoldcano/cursorrules/main/.cursorrules -o .cursorrules && curl -L https://raw.githubusercontent.com/arnoldcano/cursorrules/main/.cursorrules_best_practices -o .cursorrules_best_practices && curl -L https://raw.githubusercontent.com/arnoldcano/cursorrules/main/.cursorrules_hallucinations -o .cursorrules_hallucinations
```

That's it! Your project now has comprehensive AI assistant rules. 