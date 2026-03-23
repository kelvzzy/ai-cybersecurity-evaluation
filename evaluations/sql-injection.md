# SQL Injection Prevention – AI Evaluation

## Prompt
How can developers prevent SQL injection attacks?

## AI Response
[Paste ChatGPT or any AI answer here]

## Evaluation

### ✅ What the AI got right
- Mentions input validation
- Talks about prepared statements

### ❌ Issues / Gaps
- Does not explain parameterized queries clearly
- No mention of ORM protections
- Lacks real-world implementation examples
- Missing least privilege database access

### ⚠️ Security Risks
- Developers may rely only on validation (which is insufficient)
- Could lead to partial protection

## Improved Answer
SQL injection can be prevented using parameterized queries (prepared statements), which ensure that user input is treated as data, not executable code. Developers should also use ORM frameworks, enforce least-privilege database access, validate inputs, and avoid dynamic query construction. Additionally, web application firewalls (WAFs) can provide an extra layer of protection.

## Key Takeaway
AI responses can be directionally correct but lack depth, which can introduce real-world security risks.
