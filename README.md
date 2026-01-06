
## 🧰 Tools & Technologies
- Postman (Security test design)
- Newman (CLI automation)
- JavaScript assertions
- OWASP API Top 10 methodology
- GitHub (documentation & version control)

---

## 🛡️ Security Test Coverage

| OWASP Category | Scenario Tested |
|----------------|----------------|
| Broken Object Level Authorization (BOLA) | Accessing objects by ID without authorization |
| Input Validation | Submitting invalid and unexpected payloads |
| Excessive Data Exposure | Verifying sensitive fields are not exposed |
| Error Handling | Ensuring errors do not leak stack traces or internals |
| Rate Limiting | Observational checks for request throttling |

---

## 📁 Project Structure

api-security-testing/
├── collections/
│ └── api_security_tests.postman_collection.json
├── environments/
│ └── security_env.postman_environment.json
├── reports/
│ ├── findings.md
│ └── portswigger-reference.md
├── README.md
