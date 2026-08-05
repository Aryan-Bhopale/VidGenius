# Security Policy for VIDGENIUS 🔒

## Supported Versions

We actively maintain and support the following versions of VIDGENIUS:

| Version | Status       |
|---------|-------------|
| main    | Supported   |

Please make sure you are using a supported version before reporting any security issues.

---

## Reporting a Vulnerability

If you discover a security vulnerability in VIDGENIUS, please **report it privately** to the maintainers.  

**Steps to report:**

1. **Do not create a public issue**.  
2. Send an email to: **bhanugahlot2003@gmail.com**  
3. Include the following details:
   - Description of the vulnerability  
   - Steps to reproduce  
   - Affected versions  
   - Any suggested fixes (optional)  

We will respond within **48 hours** and work with you to resolve the issue responsibly.

---

## Security Best Practices for Contributors

When contributing code to VIDGENIUS, please follow these security guidelines:

- **Validate all user inputs** to prevent injection attacks.  
- **Never commit secrets or credentials** to the repository. Use environment variables instead.  
- **Sanitize outputs** to prevent XSS or code injection.  
- **Review dependencies** regularly for vulnerabilities.  
- **Follow the principle of least privilege** in your code.  

💡 Tip: Run automated security scanners on your changes before submitting a PR.

---

## Handling Sensitive Data

VIDGENIUS may handle sensitive user data depending on usage. Please adhere to the following:

- Store secrets in environment variables or secure vaults.  
- Avoid logging sensitive information.  
- Ensure any third-party libraries you use are secure and actively maintained.  

---

## Acknowledgements

We appreciate anyone who responsibly reports security vulnerabilities. Your contributions help make VIDGENIUS safer for everyone!  

If you would like to be acknowledged publicly for a security report, please indicate this when reporting.

---

## Resources

- [OWASP Top Ten Security Risks](https://owasp.org/www-project-top-ten/)  
- [GitHub Security Best Practices](https://docs.github.com/en/code-security)  
- [Responsible Disclosure Guide](https://www.first.org/resource/security-disclosure-guide)

