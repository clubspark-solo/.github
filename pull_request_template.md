<!-- This section is for the developer to complete. -->

## What does this PR do?


## What are the relevant tickets?


## Where should the reviewer start?


## How can this be manually tested?


## Any additional info?


## Screenshots (if appropriate)


## Definition of Done:

<!-- This section is for the reviewer to complete. -->

### Task

- [ ] This PR includes a Jira Reference
- [ ] This PR satisfies the acceptance criteria

### Documentation

- [ ] New features are documented in Confluence
- [ ] New endpoints are documented in Swagger

### Code Quality/Style

- [ ] This PR conforms to our [code style guidelines](https://github.com/clubspark/docs/blob/master/README.md)
- [ ] This PR is unit tested
- [ ] Does this PR require integration testing?
- [ ] Does this PR require regression testing?

### Secure Coding (ISO 27001 A.8.28)

- [ ] Input validation has been implemented to prevent injection attacks (SQLi, XSS, etc.)
- [ ] Sensitive data is encrypted in transit and at rest (where applicable)
- [ ] Authentication and authorization checks are enforced for all new endpoints
- [ ] Secrets, API keys, or credentials are **not** hardcoded in code/config
- [ ] Dependencies introduced/updated have been reviewed for vulnerabilities
- [ ] Error handling avoids leaking sensitive information
- [ ] Logging follows policy (no sensitive data logged)
- [ ] Code changes have been reviewed for compliance with OWASP Top 10

### Deployment / Automation

- [ ] Does this PR require any SQL scripts?
- [ ] Does this PR require any new infrastructure?
- [ ] Does this PR add new dependencies? (e.g. Mailjet, Salesforce, etc)
- [ ] Does this PR include appropriate logging?
- [ ] Does this PR include new monitoring endpoints?
