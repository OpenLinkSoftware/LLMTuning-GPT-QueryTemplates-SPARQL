# LLMTuning-GPT-QueryTemplates-SPARQL
SPARQL based for fine-tunning a GPT (3.5 or 4.0) LLM. You simply load these templates into your GPT session and then issue natural language queries for their invocation.

# Template Structure
```
<prompt1>;<query-to-be-invoked1>;
<promptN>;<query-to-be-invokedN>;
```

# Usage Instructions

1. Start a ChatGPT session (ideally, GPT4 for the most predictable experience)
2. Paste all or a selection of templates using the prompt: Remember the following sparql query templates
3. Execute a natural language query that's semantically equivalent to the prompt part of your template
