# Security Policy

Thank you for helping keep **Roblox Axiom Engine** and **Precision Builder** secure.

## Supported Versions

Roblox Axiom Engine is under active development. Security fixes are evaluated for the **latest publicly released version**, when one is available. Older releases and experimental builds are not guaranteed to receive security updates.

| Version | Security support |
| --- | --- |
| Latest published release (when available) | Best-effort |
| Older releases | Not guaranteed |
| Unreleased development builds | Not guaranteed |

This policy does not promise a specific response or fix timeline.

## Reporting a Vulnerability

**Please do not open a public GitHub issue for an undisclosed security vulnerability.**

Instead, use GitHub's private vulnerability reporting feature:

1. Open the [Roblox Axiom Engine repository](https://github.com/jgzinhoooo/Roblox-Axiom-Engine).
2. Go to **Security**.
3. Select **Report a vulnerability** (if available).
4. Submit the report privately.

Include, when possible:

- A clear description of the issue and its potential impact.
- Affected versions, files, or components.
- Steps to reproduce the issue safely.
- Relevant logs or a minimal proof of concept, with secrets removed.
- Suggested mitigations, if known.

Reports will be reviewed as maintainer availability permits. We cannot guarantee a response or resolution deadline. We may ask for more information, work on a fix, or close reports that are not reproducible or are outside the project's scope.

## Security Scope

Reports related to the plugin, its scripts, AI-agent integrations, Roblox Studio MCP interactions, or official distribution files are welcome.

Potential concerns include unauthorized actions, unsafe command execution, exposed credentials, or security issues caused by untrusted input.

Issues in third-party services or Roblox Studio itself should also be reported to the relevant vendor through its official security reporting process.

## Disclaimer and Reporting Commitment

Roblox Axiom Engine and Precision Builder are provided **"as is"**, without warranties, to the extent permitted by applicable law. The maintainers do not accept liability for losses, damages, disruptions, or other issues arising from the use of the plugin, **to the extent permitted by applicable law**. This statement does not exclude responsibilities that cannot legally be excluded.

**Please report any bugs, security vulnerabilities, unexpected behavior, or other problems.** We encourage users to share enough information for us to investigate and work toward a fix. Reports are appreciated and will be reviewed as maintainer availability allows, but a fix or response time cannot be guaranteed.

For security vulnerabilities, use GitHub's **private vulnerability reporting** feature. For ordinary bugs and feature issues, use the repository's public **Issues** section, without including secrets or sensitive information.

## AI and MCP Safety Precautions

- Back up Roblox Studio projects before allowing automated changes.
- Review AI-generated scripts, asset imports, and destructive actions before publishing.
- Monitor connected AI agents and grant only necessary permissions.
- Never expose API keys, tokens, or passwords.
- Check third-party provider terms, costs, and usage limits.
- Test changes in a safe environment before deploying them.

AI outputs may be incorrect or insecure. Reporting suspected issues helps maintainers investigate and work toward fixes, but does not guarantee a resolution.

## Responsible Disclosure

Please allow reasonable time for investigation and mitigation before publicly disclosing an unpatched vulnerability. Coordinate disclosure with the maintainers through the private report.

Do not access other people's accounts or data, disrupt services, or test against systems without authorization.

## Protecting Credentials

Never include API keys, access tokens, passwords, or other secrets in public issues, screenshots, logs, or example configurations. Revoke and rotate credentials if they are exposed.

---

**Maintained by 404 Studios br — Roblox Axiom Engine.**
