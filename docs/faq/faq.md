# Science Central FAQ
Welcome to the Science Central FAQ! This comprehensive guide provides answers to frequently asked questions about using the Science Central platform. Whether you're having trouble with account access, submitting proposals, managing data, or using advanced features, you'll find step-by-step solutions and troubleshooting tips organized by topic below.

If you can't find the answer you're looking for, or if the suggested solutions don't resolve your issue, please don't hesitate to contact our support team at [**sc.support@pnnl.gov**](mailto:sc.support@pnnl.gov) with the specific details mentioned in each section.

## Account & Login

**Q: I can't log in because my account is linked to an old email address I no longer access. What should I do?**

**A:** Contact NEXUS support to update the account email. Support will verify identity and change the email so you can request password resets.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Current and old emails
- Full name
- ORCID (if any)
- Screenshot of login error

**Q: I'm a PNNL employee and I'm having trouble logging in or resetting my password. What's the process?**

**A:** PNNL accounts use your network/IdP credentials. On-campus (or on VPN) you should get SSO automatically. Off-campus, follow the IdP login flow. If SSO fails, refresh Kerberos (kinit) or contact your IT. If problems persist, open a support ticket.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Whether you’re on VPN
- The time of attempt
- Exact error
- Browser

**Q: I’m seeing SSO/IdP errors or an “unexpected error” during sign-in. How do I troubleshoot?**

**A:** Try a private browser, clear cookies, and retry. If it persists, capture the exact error text and timestamp; it’s often an IdP metadata/certificate or SAML negotiation problem that requires SP/IdP log correlation.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- IdP name (if known)
- Error text
- Timestamp
- SAML request ID or screenshots

**Q: I get an Error 400: “Size of a request header field exceeds server limit.” What do I do?**

**A:** This is usually a proxy/header-size limit or very long cookie. Clear cookies for the site or try a fresh browser session. If it persists, we’ll need server logs to adjust proxy limits or identify problematic headers.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Exact error text
- Screenshot
- Browser
- Whether clearing cookies fixed it

**Q: After logging in I see the wrong user/account — who am I actually logged in as?**

**A:** That indicates a session/identity mapping bug (redirect or cached session). Log out, clear cookies, try private mode; if reproducible, capture steps and timestamps so engineers can trace session tokens.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Steps to reproduce
- Timestamp
- Screenshot showing wrong user

**Q: I’m locked out or didn’t receive a password reset email. What next?**

**A:** Check spam/junk and any secondary inboxes, request another reset, and wait ~15 minutes. If still not delivered, support will trigger a manual recovery or investigate email delivery issues.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Your account email
- Time(s) you requested reset
- Any bounce/error from mail system

**Q: I have duplicate accounts and want them merged.**

**A:** Request an account merge with support, providing both emails and proof of ownership. Specify which account should be primary and what data to preserve. Merges are handled manually and may require re-association of some objects.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Both emails
- Proof of ownership
- The preferred primary account

**Q: How do I change my account email or link/unlink ORCID?**

**A:** Update email in Profile → Edit → Change Email and confirm via verification link. Link ORCID via the profile ORCID button and complete OAuth. For conflicts (email already used), request an account merge.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Screenshots of errors or verification failures

## Submissions, LOIs & Proposals

**Q: How do I submit an LOI or full proposal?**

**A:** Call page → New Submission/LOI → fill required metadata → attach files → validate → submit. Use provided templates. Save drafts; validate before final submission.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Call id
- Submission id (if any)
- Step where you’re stuck
- Validation error text

**Q: The “Start Full Proposal” or submit button is missing — why?**

**A:** Submission UI appears only while the call is active. If the call is active but button missing, it may be role/permission or UI issue; try another browser and check account role.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Call id
- User role
- Screenshots
- Account email

**Q: My submission fails validation or is rejected for eligibility — what can I do?**

**A:** Check call eligibility rules. If you believe you meet criteria, request a manual review from program staff with supporting documents. If system validation is wrong, provide submission id and exact validation errors.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Submission id
- Validation error text
- Supporting evidence for eligibility

**Q: I submitted but need to withdraw or cancel — how?**

**A:** Use the withdraw option if available in the UI; otherwise file a support ticket with submission id and reason. Confirm withdrawal’s effect on review.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Submission id
- Confirmation that withdrawal is requested

**Q: Required templates or metadata sheets are missing from the submission UI.**

**A:** These should be attached to the call page. If missing, request the template via support; we can upload or provide the file directly.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Call id
- Which template is missing

**Q: I want the system to re-run ingestion or reprocess my submission after fixes.**

**A:** Open a ticket with submission id and describe what changed (files/metadata). Admins will re-trigger ingestion and share processing logs.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Submission id
- Changed files
- Timestamps

## Attachments & Uploads

**Q: I get “Reporter does not have permission to create attachments.” How to fix?**

**A:** That role lacks attachment permission. Ask the submission owner to add you as collaborator with upload rights, or request admin to change permissions.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Submission id
- Your role
- Screenshot of the permission error

**Q: Uploads fail (hang, time out, or never complete). What should I try?**

**A:** Use a wired connection, split/zip large files, try an alternate browser or private window, and reattempt. For very large files, use the data transfer/cart workflow instead of submission attachments.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- File name and size
- Error message
- Browser console logs if possible
- Transfer timestamps

**Q: Files are rejected for MIME type or file-size limits. What are acceptable formats?**

**A:** Use standard formats (PDF, DOCX, CSV) and ensure MIME matches file extension. Zip odd files to avoid MIME checks. For size limits, compress or use data transfer tools.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- File name
- Extension
- Size
- Server error

**Q: I can't find the upload button on a proposal page.**

**A:** The UI may hide upload controls based on role or submission stage. Confirm you are owner/collaborator and in draft mode. If UI bug, provide the submission id and a screenshot.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Submission id
- Your role
- Screenshot

## Data Cart & Downloads / Data Portal

**Q: My data cart download failed or is incomplete — how to resume?**

**A:** Try to resume the transfer if your client supports it. If not, regenerate the cart and restart transfer. For large downloads, request a pre-packaged tarball or staging link from support.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Cart id
- Transfer tool used
- Last successful file
- Error logs

**Q: "Create Cart" does nothing or hangs — what now?**

**A:** Wait a few minutes (backend job); if it still doesn’t generate, open a support ticket with cart attempt timestamp and dataset/project id. We can check job queue and generate manually.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Project id
- Time tried
- Screenshot

**Q: Data portal facets or filters aren’t working (missing Project Type or broken filters).**

**A:** This is a UI/feature issue. We’ll route to product/UX for backlog. Workaround: search or narrow results differently until fix.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Page URL
- Steps to reproduce
- Screenshots

**Q: I can click “Download” while logged out — is that intended?**

**A:** Some previews may show the modal but require authentication to access data. If files actually download without auth, report immediately (possible ACL bug).

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Steps
- URLs
- Test results

**Q: Issues removing or managing Globus identities from profile.**

**A:** If the remove identity button does nothing, it’s likely a UI bug; support can remove identities server-side.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Account email
- Identity id
- Screenshot

## Metadata, Templates & Schemas

**Q: The metadata template won’t download / the CSV template is empty or invalid.**

**A:** Try another browser; if template still fails, support will provide the file. For schema validation errors, follow the provided schema docs and formatting rules.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Project id
- Template name
- Browser
- Screenshot/errors

**Q: My metadata fields produce validation errors — how to fix?**

**A:** Validate against the schema; ensure required fields are present and types match (dates, numbers). Use the example template. If the validator misbehaves, include the sample row and error text.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Dataset id
- Sample metadata snippet
- Validation error

## Permissions & Collaboration

**Q: I can't add collaborators or change permissions on my submission.**

**A:** Only the submitter/owner can add collaborators. If your role should permit it but doesn’t, open a ticket with submission id and collaborator emails for admin assistance.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Submission id
- Desired collaborator emails
- Your current role

**Q: A collaborator cannot access a shared submission or data.**

**A:** Confirm the collaborator was added and that permissions were saved. If access still fails, admins can reapply permissions or re-share resources.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Collaborator email
- Resource id
- Error messages

## Programmatic Access & Transfers

**Q: How do I use the API or set up automated transfers (rsync/ssh)?**

**A:** See API docs for endpoints, auth methods, and rate limits. For transfers, use documented rsync/ssh endpoints or the transfer client. Request API tokens or service accounts as needed and provide intended usage for limit assignment.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Intended use
- Frequency
- Scripts/commands you plan to run

**Q: Automated transfer/rsync fails mid-transfer with network errors.**

**A:** Check firewall and network stability, confirm credentials and paths, and try resumable transfers. Support can provide staging or pre-packaged exports if transfers repeatedly fail.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Transfer command
- Stdout/stderr
- Timestamps

## Notifications, Emails & Help Links

**Q: I was tagged but didn't get an email notification.**

**A:** Check spam/junk and notification preferences. Email delivery can fail due to bouncing addresses. Support can re-send or investigate delivery logs.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Expected notification type
- Target email
- Timestamps

**Q: Some help or external links are broken or open in the same tab.**

**A:** UX/content issue — we’ll update the link or target="_blank" behavior. Report the page URL and offending link.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Page URL
- Link text
- Desired behavior

**Q: Where do I get notified about call re-openings and deadlines?**

**A:** Subscribe to the call’s notification list or contact the call owner to be added to distribution. We can also provide RSS/email alerts where available.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Call id
- Email to subscribe

## Instrument Reservation, Samples & Restricted Data

**Q: I can't reserve instrument time or access instrument pages.**

**A:** Confirm your account has the required role and the proposal includes instrument access. If a reservation error appears, include instrument id and error text for support.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Instrument id
- Proposal id
- User role
- Error screenshot

**Q: How do I request access to restricted datasets or samples?**

**A:** Use the dataset’s access request workflow, supply justification and approvals. Track the request in your account; escalate via support if approval stalls.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Dataset id
- Reason for access
- PI approval if required

## System & Incidents

**Q: Who do I contact for site-wide outages or urgent production problems?**

**A:** Open a high-priority support ticket with “PRODUCTION OUTAGE” in subject and include affected URLs, screenshots, and timestamps. Use incident on-call if available.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Affected endpoints
- Number of users impacted
- Screenshots

**Q: I see nightly “missing files detected” alerts in logs — what does this mean?**

**A:** These are system diagnostics indicating missing objects in storage. Ops will investigate and reconcile missing files from backups or re-ingestion.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Alert timestamp
- Affected project ids

## Navigation

**Q: I need help with site navigation between Science Central and NEXUS.**

**A:** Some internal links open new tabs or redirect. If navigation breaks flow (losing search context), report exact link and behavior. We can harmonize link targets.

If you still see issues or the issue isn't resolved, send us an email at [sc.support@pnnl.gov](mailto:sc.support@pnnl.gov) and include the items below:

- Originating page
- Link clicked
- Observed behavior

