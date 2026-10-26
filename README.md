# When Contact Forms Fail

**ABEL and Dustin Sprenger · October 25, 2026**

An independent evidence record of one explicit reCAPTCHA integration error and two university contact-form failures with unresolved causes.

[Read the evidence page](https://dustinsprenger.github.io/contact-form-failure-evidence/) · [Download the evidence package](evidence.zip) · [Google forum report](https://security.googlecloudcommunity.com/fraud-defense-recaptcha-6/broken-recaptcha-and-opaque-university-form-failures-engineering-review-and-usable-diagnostics-requested-8479)

## Findings

| Institution | Observed UTC | Result |
|---|---|---|
| Kyrgyz National University | 2026-10-25T23:57:51.773Z | `ERROR for site owner: Invalid key type` before inquiry entry or submission |
| University of Sarajevo | 2026-10-25T23:53:45.116Z | Both “Unable to send email” and “Your message has been sent” |
| Dar Al Uloom University | 2026-10-26T00:20:38.976Z | “Failed to send your message” |

The latter two messages do not establish Google involvement. The record does not establish deliberate suppression or a common root cause. Times are observation/capture-log timestamps, not server events.

## Evidence

Original PNG screenshots, [structured observations](observations.json), [submitted report](report.txt), [SHA-256 checksums](SHA256SUMS.txt), and Google's [submission confirmation](forum-submission-confirmation.png). The forum submission was awaiting moderator review at the recorded check.

Each PNG matches its retained local original. Hashes establish byte identity, not an independently certified date or causal explanation.

The full report includes the six public OSF research links, including **Fifty Milliseconds Before Consent**, and requests engineering review, safe diagnostics, accessible recovery routes and preservation of relevant records.

## Preservation

Removing the Google forum post would not erase these evidence copies. Keep corrections and responses with the original record. No credentials, cookies, private authentication tokens, or unpublished manuscripts are included. AI-assisted preparation is disclosed in the report.
