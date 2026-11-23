# Test Plan — Remington Arms Website

## 1. Document information
- Project: Remington Arms Website QA
- Version: 0.1
- Status: Draft
- Target: https://remington-arms.com/
- Author: [Your name / GitHub username]
- Execution date: [Fill in after testing]

## 2. Objective
Assess the basic quality of publicly accessible informational website features: page availability, navigation, visible content, links, document access, responsive presentation, and form validation behavior where it can be checked without submitting real personal data.

## 3. Scope — In scope
- Homepage rendering.
- Header and footer navigation.
- Public informational pages linked from the homepage.
- Owner's Manuals page and document links (availability/opening only).
- Newsletter form field presentation and client-side validation, without submitting real data.
- Accessibility basics: keyboard focus, labels, meaningful link text, image alternative text where observable.
- Responsive layout at common desktop, tablet, and mobile viewport sizes.
- Cross-browser smoke checks.

## 4. Out of scope
- Firearm operation, assembly, maintenance, performance, or safety procedures.
- Ammunition or ballistic content testing.
- Product purchasing, ordering, dealer allocation, or sales workflows.
- Restricted/admin areas, penetration testing, vulnerability scanning, load testing, or automated high-volume requests.
- Sending real contact/newsletter submissions.

## 5. Test approach
1. Review public pages and identify user-visible components.
2. Create and execute manual checklist items.
3. Execute test cases and record actual results.
4. Capture evidence for reproducible failures.
5. Report only verified defects.
6. Automate stable read-only checks after manual behavior is understood.

## 6. Test types
- Smoke testing
- Functional UI testing
- Navigation and link testing
- Compatibility testing
- Responsive UI testing
- Basic accessibility checks
- Basic form validation observation

## 7. Test data
Use only synthetic, non-personal test strings where local validation can be observed without submitting a form. Do not send the form or create accounts.

## 8. Entry criteria
- Target website is publicly reachable.
- Browser and test environment are recorded.
- Test cases and checklist are reviewed.

## 9. Exit criteria
- All planned checks have a recorded status.
- Every Fail has reproducible steps and evidence, where safe.
- No unverified issue is described as a confirmed bug.
- A concise test summary is completed.

## 10. Risks and limitations
The website may change during testing. Third-party scripts, geographic restrictions, cookie settings, and network conditions can affect behavior. Public pages do not provide a formal requirements document; expected results must therefore be limited to clearly observable behavior and documented assumptions.

## 11. Deliverables
- Test Plan
- Checklists
- Test Cases
- Verified Bug Reports (if any)
- Evidence screenshots
- Test Summary Report
- Small read-only UI automation suite
