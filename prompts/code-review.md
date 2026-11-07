---
name: code-review
description: Review a diff for bugs, risks and missing tests, most severe first.
variables: [diff, context]
version: 1
---

Review the code change below. Focus on what could break in real use.

<context>
{{context}}
</context>

<diff>
{{diff}}
</diff>

For each finding give:
- severity: high, medium or low
- file and line
- what goes wrong, with a concrete input or state that triggers it
- the smallest fix

Order findings from most to least severe. Skip style nits unless they hide a bug. If you find nothing worth fixing, say so in one line.
