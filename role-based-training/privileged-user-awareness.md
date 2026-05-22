# Privileged User Security Awareness

## Purpose

Privileged users have elevated access to systems, applications, infrastructure, security tools, cloud environments, and sensitive data. Because of this access, they are high-value targets for attackers.

This training helps privileged users understand their responsibilities and apply secure practices when using administrative access.

## Audience

This guidance applies to:

- System administrators
- Cloud administrators
- Network administrators
- Security analysts
- Database administrators
- Application administrators
- IT service desk staff with elevated permissions
- Engineers with production access
- Users with access to sensitive administrative consoles

## Key Risks

Privileged user risks include:

- Credential theft
- Misuse of administrative access
- Unauthorized configuration changes
- Privilege escalation
- Poor password or MFA practices
- Shared administrator accounts
- Insecure remote access
- Unlogged or unapproved changes
- Accidental exposure of sensitive data
- Social engineering targeting IT support
- Abuse of account recovery processes

## Required Behaviours

Privileged users should:

1. Use privileged accounts only when needed.
2. Use separate accounts for normal and administrative work.
3. Protect privileged credentials with strong authentication.
4. Never share administrative passwords or tokens.
5. Follow change management procedures.
6. Avoid making unapproved production changes.
7. Use approved remote access methods.
8. Record and document administrative actions where required.
9. Report suspicious privileged account activity immediately.
10. Follow least privilege and need-to-know principles.

## Privileged Access Principles

Privileged access should be:

- Approved
- Time-bound where possible
- Role-based
- Logged and monitored
- Reviewed regularly
- Removed when no longer required
- Protected by MFA
- Used only for authorized business purposes

## AI-Era Considerations

Attackers may use AI to target privileged users through:

- Highly personalized phishing
- Fake IT support requests
- Voice-cloned manager instructions
- Deepfake approval attempts
- AI-generated scripts or commands designed to deceive
- Social engineering against help desk and account recovery processes

Privileged users should be especially cautious when receiving urgent requests involving access, resets, configuration changes, or security exceptions.

## Account Recovery and Help Desk Risks

Privileged users and IT support teams should be alert to:

- Password reset requests from unusual channels
- MFA reset or device transfer requests
- Requests involving senior executives
- Repeated failed identity verification
- Pressure to bypass normal procedures
- SIM swap or phone number change claims
- Requests to disable security controls temporarily

Expected response:

1. Follow documented identity verification procedures.
2. Do not bypass controls due to pressure or seniority.
3. Escalate suspicious requests.
4. Record recovery actions.
5. Require additional approval for privileged or executive accounts.

## Secure Administration Practices

Privileged users should:

- Use secure administrative workstations where available.
- Avoid browsing the internet or reading email from privileged sessions.
- Avoid storing credentials in scripts or plain text files.
- Use approved password vaults or secrets management tools.
- Review scripts before execution.
- Validate commands before running them in production.
- Keep administrative tools updated.
- Log out of privileged sessions when work is complete.

## Change Management Expectations

Before making changes, privileged users should confirm:

- The change is approved.
- The scope is clear.
- The risk has been assessed.
- A rollback plan exists.
- The timing is appropriate.
- Required stakeholders have been informed.
- Monitoring is in place where needed.

## Incident Reporting

Privileged users should immediately report:

- Suspicious login attempts
- Unexpected MFA prompts
- Unauthorized configuration changes
- Unknown administrator accounts
- Unusual system behaviour
- Lost or exposed credentials
- Mistaken administrative actions
- Evidence of malware or persistence
- Suspicious scripts or commands

## Scenario Examples

### Scenario 1: Unexpected MFA Prompt

A privileged user receives an MFA approval request they did not initiate.

Expected response:

- Do not approve the request.
- Report it immediately.
- Follow the account compromise procedure.
- Review recent account activity.

### Scenario 2: Urgent Request to Disable MFA

A senior manager asks IT to disable MFA urgently because they are locked out.

Expected response:

- Follow identity verification.
- Do not bypass standard procedure.
- Escalate if the request is unusual.
- Record actions taken.

### Scenario 3: Unapproved Production Change

An administrator identifies a quick fix and wants to apply it directly to production.

Expected response:

- Follow change management.
- Assess risk and impact.
- Obtain approval.
- Document the change and rollback plan.

## Metrics

Recommended metrics include:

- Privileged user training completion rate
- Number of privileged access reviews completed
- Number of unauthorized privileged access attempts
- Number of suspicious MFA reports
- Number of emergency access requests
- Percentage of privileged accounts protected by MFA
- Number of privileged access policy exceptions

## Key Takeaways

- Privileged access creates higher responsibility.
- Administrative actions should be approved, logged, and defensible.
- MFA prompts should never be approved unless expected.
- Account recovery is a common social engineering target.
- Convenience should not override security controls.
