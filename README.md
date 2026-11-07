# Suspicious Recruitment Outreach: An OSINT and Social Engineering Case Study

**Case status:** Unverified recruitment outreach; fraud not established.  
**Method:** Screenshot review, evidence classification, hypothesis testing, and defensive recommendations.  
**Publication:** Sanitized case study. Original evidence is maintained separately in a private archive.

## Executive summary
An unsolicited LinkedIn message claimed a recruiting affiliation with a named employment company and advertised unspecified remote full-time or part-time work, flexible hours, training, and no prior experience requirement. The sender requested a phone number or resume to arrange further contact. The recipient responded affirmatively but reports sharing no phone number, resume, or additional information. These features warrant independent verification; they do **not** prove fraud.

## Scope and limitations
This case uses screenshots supplied by the recipient and their account of subsequent contact. No independent employer verification, account ownership verification, message-header analysis, or confirmed malicious destination is available. A separately viewed GitHub profile shared a surname with the LinkedIn profile, but **no relationship or relevance was established**; it is excluded from attribution.

## Evidence summary
| ID | Sanitized observation | Status |
|---|---|---|
| E01 | Unsolicited LinkedIn recruitment message | Observed |
| E02 | Claimed affiliation with a recruiting/employment brand | Claim unverified |
| E03 | Remote full-/part-time roles, flexible hours, training, no experience | Observed |
| E04 | Requested phone number or resume before a specific role was identified | Observed |
| E05 | Recipient replied affirmatively | Observed |
| E06 | Recipient reports no phone number, resume, or other information shared | Self-reported |
| E07 | Similar surname appeared on an unrelated GitHub profile | No link established; excluded from attribution |

## Hypotheses
- H1: Legitimate broad recruiter outreach. **Possible; not verified.**
- H2: Misleading or fraudulent recruiting pretext intended to gather personal information. **Possible; not verified.**
- H3: Account impersonation of an employment brand. **Not determined.**

## Risk assessment
**Screening priority: Elevated verification need.** This is a qualitative triage judgment, not a validated probability of fraud. No confirmed compromise, financial loss, credential disclosure, malicious URL, or malware is shown.

## Investigation workflow
1. Preserve original evidence locally, with file hashes and collection notes.
2. Record observable claims without treating them as facts.
3. Seek an exact job title, requisition number, official job listing, and verified corporate contact.
4. Verify through the company's independently obtained official channels, not links supplied by the sender.
5. Update findings only when new evidence supports them.

## Conclusion
The outreach exhibits multiple characteristics commonly seen in suspicious recruitment approaches, particularly vague job details and an early request for contact information. The available evidence does **not** establish that the sender or any named individual committed fraud. The case illustrates evidence-based social engineering triage and responsible publication.

## Ethical publication
Names, profile images, personal URLs, emails, and unique account identifiers are intentionally omitted. Do not upload the private archive or unredacted screenshots. No individual should be publicly accused based on this case study.

See [evidence-analysis.md](evidence-analysis.md), [mitre-mapping.md](mitre-mapping.md), and [prevention-guide.md](prevention-guide.md).
