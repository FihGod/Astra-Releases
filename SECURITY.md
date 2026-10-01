# Security policy

## Supported releases

Security fixes target the latest stable Astra release. Update to the latest release before reporting a problem. Older releases and prereleases may not receive fixes.

## Report a vulnerability privately

Use [GitHub's private vulnerability reporting form](https://github.com/FihGod/Astra-Releases/security/advisories/new). Do not open a public issue or post exploit details in public Discord channels.

Include the affected version and operating system, a clear description, safe reproduction steps, expected and actual behavior, and the potential impact. Redact license keys, passwords, tokens, payment information, and personal data. Use test accounts and minimal examples.

The maintainer will review the report and coordinate next steps privately. There is no guaranteed response time or bounty program. Agree on disclosure timing with the maintainer before publishing details.

## Scope and security expectations

This repository distributes Astra's Windows and Linux downloads, installation helpers, update metadata, and documentation. The application source and production services are maintained separately. Reports involving official Astra downloads, update verification, authentication, authorization, or unintended exposure of customer information are welcome here and can be routed to the appropriate component.

Official updates must verify signed release metadata and asset integrity before installation. Untrusted input must not grant access to another user's account, license, tickets, or administrative actions. Credentials and signing secrets must not be exposed through downloads, logs, or support reports. These are required properties, not a claim that every component has been independently audited.

## Responsible testing

Test only accounts and systems you own or have permission to assess. Do not access other customers' data, disrupt service, send unsolicited messages, or test against third-party payment, hosting, Microsoft, Discord, or game services without their authorization. Stop if you encounter private data and report the minimum evidence needed to explain the issue.

Routine setup problems and feature requests belong in support tickets or public issue templates after removing sensitive information. Suspected security issues should still be reported privately when uncertain.
