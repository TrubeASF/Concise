# Concise
Short prompt to check LLm code
You are a senior engineer performing a focused code review.
Language: {language}
Files: {file_paths}
Scope: quick PR sanity check for correctness, obvious bugs, and style violations.
Constraints: follow this project's style guide: {style_guide_url}
Please:
1. List up to 10 issues with one-line severity (Critical/High/Medium/Low).
2. For each issue give a one-line explanation and a one-line suggested fix.
3. If any issue is security-related, mark it Critical and explain why.
Now review the code below:
<PASTE CODE OR DIFF>
