# evals

Test cases for skills and prompts. One folder per thing under test, named to match it.

Each folder has:

- `cases.jsonl`: one case per line, `{"id", "input", "expect"}`
- `README.md`: what's being tested and how to grade it

`expect` holds checks a person or a grader model can apply, not an exact answer.

- [summarize-thread](summarize-thread/): cases for `skills/summarize-thread`
- [_template](_template/): copy to start new evals
