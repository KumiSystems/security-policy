# Kumi Systems Security Policy

This document outlines the security policy for Kumi Systems. It is intended to
be a living document, and will be updated as needed.

First and foremost, Kumi Systems is committed to the security of our customers
and their data. We take security very seriously, and we are thankful to the
community for helping us to improve our security posture.

## Reporting a Vulnerability

If you believe you have found a security vulnerability in one of our products,
please report it to us as described below.

### Open Source Projects

If you believe you have found a security vulnerability in one of our open
source projects, please first check if the vulnerability has already been
reported by searching the related issue trackers in our [KumiGit](https://kumig.it/kumisystems)
and [GitHub](https://github.com/kumisystems) organizations.

If you do not find an existing issue, please report it by creating a new issue
in the appropriate issue tracker[^1]. Please include as much information as
possible, including:

- The version of the project you are using
- The version of the operating system you are using
- The version of any other software you are using that may be related to the
  vulnerability
- A description of the steps required to reproduce the vulnerability
- A description of the expected behavior, and how the actual behavior differs
  from the expected behavior
- If you can demonstrate the vulnerability, please include a link to a
  demonstration, or the code required to reproduce the vulnerability
- Any other information you believe may be relevant to the vulnerability
- If you are able to provide a fix for the vulnerability, please include a
  link to a pull request with your fix

If the vulnerability allows an attacker to gain access to personal data, or
other sensitive information, please make sure to mark the issue as 
confidential. This will ensure that only the maintainers of the project will
be able to see the issue. If you are not sure how to mark an issue as
confidential, please contact us. Please do not publicly disclose the
vulnerability until it has been fixed.

### Web Applications

If you believe you have found a security vulnerability in one of our web
applications, please first check if the vulnerability has already been
reported by searching the related issue trackers in our [KumiGit](https://kumig.it/kumisystems/security-policy/issues)
and [GitHub](https://github.com/kumisystems/security-policy/issues)
security policy issue trackers.

If you do not find an existing issue, please report it by creating a new issue
in the appropriate issue tracker[^1]. Please include as much information as
possible, including:

- The URL of the web application you are using
- The version of the browser you are using
- The version of the operating system you are using
- The version of any other software you are using that may be related to the
  vulnerability
- A description of the steps required to reproduce the vulnerability
- A description of the expected behavior, and how the actual behavior differs
  from the expected behavior
- If you can demonstrate the vulnerability, please include a link to a
  demonstration, or the code required to reproduce the vulnerability
- Any other information you believe may be relevant to the vulnerability

If the vulnerability allows an attacker to gain access to personal data, or
other sensitive information, please make sure to mark the issue as
confidential. This will ensure that only the maintainers of the project will
be able to see the issue. If you are not sure how to mark an issue as
confidential, please contact us. Please do not publicly disclose the
vulnerability until it has been fixed.

### Other Products

If you believe you have found a security vulnerability in one of our other
products, please follow the process described in the section for web
applications.

### Third-Party Products

If you believe you have found a security vulnerability in a third-party
product we use, we definitely appreciate you letting us know. However,
the primary responsibility for fixing security vulnerabilities in third-party
products lies with the maintainers of those products. We will work with you
to ensure that the maintainers of the third-party product are aware of the
vulnerability, and we will work with the maintainers of the third-party
product to ensure that the vulnerability is fixed. However, we cannot
guarantee that the maintainers of the third-party product will fix the
vulnerability in a timely manner.

## Disclosure Policy

When we receive a security report, we will assign it to a member of our
security team. The security team member will acknowledge your report within
three business days, and will send a more detailed response within seven
business days indicating the next steps in handling your report.

If you have not received a reply to your report within seven business days,
you have the following options:

- Contact the assigned security team member by email directly
- Raise the issue to the attention of the entire security team by email
  (see below)
- Contact the Kumi Systems CEO directly (see below)

After the initial reply to your report, the security team will endeavor to
keep you informed of the progress being made towards a fix and full
announcement. As recommended by the [RFPolicy](https://dl.packetstormsecurity.net/papers/general/rfpolicy-2.0.txt),
these updates will be sent at least every five days, although we will ideally
be in touch more often than that. If the issue is not resolved within 90 days,
the security team will send a final update indicating that progress towards a
fix has halted.

Do not publicly disclose the issue until it has been fully resolved. If you
have not received a full update by the 90 day limit, feel free to publicly
disclose the issue.

## Rewards

We do not offer monetary rewards for security reports. However, we do offer
public recognition for security reports regarding our own products. If you
would like to be publicly recognized for your report in our security-policy
repositories, please let us know.

Additionally, we will send you a free Kumi Systems t-shirt if you are the first
to report a given non-trivial security vulnerability. And we may be able to 
offer you free services or other benefits, depending on the severity of the 
vulnerability.

## Safe Harbor

Kumi Systems is committed to working with researchers who submit reports to us
in accordance with this policy. We believe that working with researchers
helps us to ensure the security and privacy of our users.

We ask that you attempt, in good faith, to avoid privacy violations, destruction
of data, and interruption or degradation of our services. Please only interact
with accounts you own or with explicit permission of the account owner. If
you encounter any data that you believe to be personally identifiable
information (PII), we ask that you notify us immediately so we can take steps
to remove it.

Please make sure to follow the Disclosure Policy when reporting an issue to us.
Do not publicly disclose the issue until it has been fully resolved.

If you follow these guidelines when reporting an issue to us, we commit that
we will not bring or support legal action against you for acts or omissions
that are consistent with this policy. This commitment does not apply to
malicious acts.

## Scope

This policy applies to all products and services provided by Kumi Systems. It
does not apply to third-party products and services.

## Comments on this Policy

If you have any comments on this security policy, please open an issue in the
security-policy issue tracker.

## Contact Information

If you need to contact us regarding anything related to this security policy,
please send an email to: security@kumi.systems

You may use our GPG key to encrypt your email. You can find our key in the
[security-key.gpg](security-key.gpg) file in this repository.

If you need to contact us regarding anything else, please send an email to:
support@kumi.systems

If you need to get in touch with the Kumi Systems CEO, please use:

- Email: kumitterer@kumi.systems ([kumitterer-key.gpg](kumitterer-key.gpg))

[^1]: If you are not sure which issue tracker to use, you may always use the
    security-policy issue tracker. Also, if you do not have an account on
    KumiGit, you may use the security-policy issue tracker on GitHub. Lastly,
    if all else fails, you may email us. See the dedicated section for more 
    information.