
# AI-Eval
AI-powered repository quality evaluator for source code, architecture, testing, logging, and maintainability.

It reviews areas such as:
- architecture and modularity
- test coverage
- error handling
- logging and observability
- maintainability and code quality

The output is designed to help developers quickly identify weaknesses and produce actionable recommendations in JSON and markdown formats.

## Use Cases

- Review an existing repository before refactoring
- Generate a quality report for a prototype or MVP
- Assess architecture, testing, and logging gaps
- Produce structured recommendations for engineering improvement
# Instruction

Download this project files into a folder 

## ChatGPT
1. Attach a zip file of your codebase
2. in the prompt enter:
```text
The attached file includes source code under src and your evaluation instructions under "AIEval" folder,
Can you go through each instruction and produce required output

```
## Claude Code

# Output Examples

```json
{
  "category": "architecture",
  "score": 6.5,
  "recommendation": "Split Engine into focused services for lifecycle orchestration, message routing, locking, and upgrade operations."
}
```

