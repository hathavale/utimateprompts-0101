# Coding & Development Prompts

A collection of prompts for software development tasks including code generation, debugging, code review, and architecture design.

---

## Code Generation

### Generate a Function

```
Write a [language] function called `[function name]` that [describe what it should do].

Requirements:
- [requirement 1]
- [requirement 2]

Include error handling and add a docstring or comments explaining the logic.
```

### Build a REST API Endpoint

```
Create a [language/framework] REST API endpoint for [resource name].

It should support the following operations:
- GET /[resource]: return a list of all [resource] items
- GET /[resource]/:id: return a single item by ID
- POST /[resource]: create a new item
- PUT /[resource]/:id: update an existing item
- DELETE /[resource]/:id: delete an item

Use proper HTTP status codes and include input validation.
```

### Generate a Database Schema

```
Design a relational database schema for [application type].

The application needs to store:
- [entity 1] with fields: [fields]
- [entity 2] with fields: [fields]

Include primary keys, foreign keys, and indexes for common query patterns.
```

---

## Debugging

### Explain and Fix a Bug

```
I have the following [language] code that produces an unexpected result:

```[language]
[paste your code here]
```

Expected behavior: [describe what should happen]
Actual behavior: [describe what is happening]
Error message (if any): [paste error]

Please identify the bug, explain why it occurs, and provide a corrected version of the code.
```

### Optimize Slow Code

```
The following [language] code is running too slowly:

```[language]
[paste your code here]
```

It currently takes [X seconds/ms] to complete. My performance goal is [Y seconds/ms].

Please identify bottlenecks and suggest optimizations. Explain each change and its expected impact.
```

---

## Code Review

### Full Code Review

```
Please review the following [language] code:

```[language]
[paste your code here]
```

Evaluate it on:
1. Correctness – does the logic work as intended?
2. Readability – is the code clear and well-structured?
3. Performance – are there any obvious inefficiencies?
4. Security – are there any vulnerabilities (e.g., injection, unvalidated input)?
5. Best practices – does it follow idiomatic [language] conventions?

Provide specific, actionable suggestions for each issue found.
```

### Security Review

```
Perform a security-focused code review of the following [language] code:

```[language]
[paste your code here]
```

Look for vulnerabilities such as:
- Injection attacks (SQL, command, etc.)
- Insecure handling of user input
- Hardcoded credentials or secrets
- Improper error handling that leaks information
- Insecure dependencies

For each issue found, describe the risk and recommend a fix.
```

---

## Software Architecture

### Design a System Architecture

```
Design a high-level system architecture for [application description].

Key requirements:
- [requirement 1]
- [requirement 2]
- Expected scale: [number of users / requests per second]

Describe the major components, how they interact, the data flow, and your technology choices. Include trade-offs for any major decisions.
```

### Choose Between Approaches

```
I am building [feature/system description] and considering the following approaches:

Option A: [describe option A]
Option B: [describe option B]

My constraints are:
- [constraint 1, e.g., team size, timeline, budget]
- [constraint 2]

Compare the two options across maintainability, scalability, complexity, and risk. Recommend one and explain your reasoning.
```

---

## Testing

### Write Unit Tests

```
Write unit tests for the following [language] function using [testing framework]:

```[language]
[paste your function here]
```

Cover:
- Normal/happy-path cases
- Edge cases (empty input, boundary values, etc.)
- Error/exception cases

Use descriptive test names that explain what each test verifies.
```

### Generate Test Data

```
Generate realistic test data for a [entity name] with the following fields:
- [field name]: [type and constraints]
- [field name]: [type and constraints]

Provide [N] sample records in [JSON / CSV / SQL INSERT] format that cover a variety of realistic scenarios including edge cases.
```

---

## Documentation

### Write a README

```
Write a README.md for a [project type] called "[project name]".

The project: [brief description of what it does]
Tech stack: [list technologies used]
Target audience: [developers / end users / etc.]

Include the following sections: Overview, Features, Installation, Usage (with examples), Configuration, and Contributing.
```

### Document an API

```
Write API documentation for the following endpoint:

Method: [GET / POST / PUT / DELETE]
Path: [/api/path]
Description: [what the endpoint does]
Request body / parameters: [describe inputs]
Response: [describe outputs]

Format the documentation using Markdown with sections for Description, Request, Response, and an example curl command.
```
