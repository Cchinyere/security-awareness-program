# Developer Security Awareness

## Purpose

Developers and technical teams play a critical role in reducing security risk across applications, systems, data flows, APIs, automation, and AI-enabled solutions.

This training helps developers understand practical secure development behaviours and AI-era risks that should be considered throughout the software development lifecycle.

## Audience

This guidance applies to:

- Software developers
- Application engineers
- DevOps engineers
- Cloud engineers
- QA testers
- Solution architects
- Product teams involved in technical design
- Teams building, buying, or integrating AI-enabled systems

## Key Risks

Developer-related risks include:

- Insecure code
- Hard-coded secrets
- Weak authentication or authorization
- Insecure APIs
- Vulnerable dependencies
- Poor input validation
- Misconfigured cloud services
- Inadequate logging and monitoring
- Sensitive data exposure
- Lack of secure design review
- Insecure AI integrations
- Prompt injection and AI output manipulation

## Required Behaviours

Developers should:

1. Build security into design and development decisions.
2. Avoid hard-coding passwords, API keys, tokens, or secrets.
3. Use approved secrets management tools.
4. Validate and sanitize user input.
5. Apply secure authentication and authorization controls.
6. Keep dependencies updated.
7. Review security findings and remediate according to risk.
8. Avoid exposing sensitive data in logs or error messages.
9. Follow secure coding standards.
10. Include security testing in development workflows.

## Secure Development Principles

Development teams should apply:

- Secure by design
- Least privilege
- Defense in depth
- Secure defaults
- Input validation
- Output encoding
- Secure error handling
- Logging and monitoring
- Dependency management
- Threat modelling
- Code review
- Secure deployment practices

## AI-Era Considerations

Where AI tools or AI-enabled systems are used, developers should understand:

- Prompt injection
- Insecure output handling
- Sensitive data leakage through prompts or responses
- AI model and plugin supply chain risk
- Training data poisoning
- Excessive agency in AI agents
- Hallucinated or insecure AI-generated code
- Overreliance on AI-generated recommendations
- Lack of human review before deployment

## Safe Use of AI Coding Tools

When using AI coding assistants, developers should:

1. Review AI-generated code before use.
2. Test generated code for security weaknesses.
3. Avoid pasting secrets, credentials, customer data, or proprietary code into unapproved AI tools.
4. Validate licensing and intellectual property concerns where required.
5. Avoid assuming AI-generated code is secure.
6. Run static analysis, dependency checks, and peer review.
7. Document AI-assisted development where organizational policy requires it.

## Prompt Injection Awareness

Prompt injection occurs when a user or external content manipulates an AI system into ignoring instructions, exposing data, or performing unintended actions.

Developers working with AI systems should:

- Treat prompts and AI outputs as untrusted input.
- Validate AI outputs before they trigger actions.
- Limit what AI systems can access.
- Apply authorization checks outside the AI model.
- Avoid exposing sensitive system instructions.
- Monitor unusual AI behaviour.
- Test AI systems against abuse cases.

## Secure API and Application Practices

Developers should pay attention to:

- Authentication and session management
- Authorization checks
- Rate limiting
- Input validation
- API key protection
- Secure headers
- Error handling
- Logging and monitoring
- Encryption in transit and at rest
- Secure file upload handling
- Access control testing

## Dependency and Supply Chain Security

Development teams should:

- Use approved package repositories.
- Review dependency risk.
- Keep packages updated.
- Remove unused dependencies.
- Monitor known vulnerabilities.
- Avoid installing unknown packages without review.
- Use lock files where appropriate.
- Review build and deployment pipelines.

## Cloud and DevOps Security

Developers and DevOps teams should:

- Avoid public exposure of storage buckets.
- Protect CI/CD secrets.
- Apply least privilege to service accounts.
- Use infrastructure as code review.
- Monitor cloud configuration drift.
- Avoid excessive permissions.
- Secure container images.
- Scan code, containers, and dependencies.

## Scenario Examples

### Scenario 1: Hard-Coded API Key

A developer places an API key directly in a source code file.

Expected response:

- Remove the secret from the code.
- Rotate the exposed key.
- Use an approved secrets management solution.
- Review repository history where needed.
- Report the exposure according to policy.

### Scenario 2: AI-Generated Code

A developer uses AI to generate an authentication function.

Expected response:

- Review the code carefully.
- Test for security weaknesses.
- Validate against secure coding standards.
- Request peer review before deployment.
- Do not assume the AI output is secure.

### Scenario 3: Prompt Injection Risk

An application uses an AI assistant to summarize customer-uploaded documents.

Expected response:

- Treat uploaded content as untrusted.
- Prevent document content from overriding system instructions.
- Limit AI access to sensitive data.
- Validate outputs before business action.
- Log and monitor unusual outputs.

## Security Testing Activities

Recommended activities include:

- Secure code review
- Static application security testing
- Dynamic application security testing
- Dependency scanning
- Container scanning
- Infrastructure as code scanning
- Threat modelling
- Abuse case testing
- API security testing
- AI-specific security testing where relevant

## Metrics

Recommended metrics include:

- Developer security training completion rate
- Number of secrets detected in repositories
- Dependency vulnerability remediation time
- Number of secure code review findings
- Percentage of critical findings remediated on time
- Number of AI-related security issues identified
- Secure coding standard adoption rate
- Number of applications with threat models completed

## Key Takeaways

- Security should be built into design, development, testing, and deployment.
- AI-generated code still requires human review and security testing.
- Secrets should never be hard-coded or entered into unapproved AI tools.
- Prompt injection and insecure AI output handling are important AI-era risks.
- Developers are central to reducing application and AI system risk.
