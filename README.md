# Remington Arms — Independent QA Portfolio Project

**Project type:** Educational website testing case study  
**Testing focus:** Manual QA + UI automation foundations  
**Languages:** English / Русский  
**Target website:** https://remington-arms.com/  
**Status:** Initial project setup — testing not yet executed

> This is an independent educational QA project. It is not affiliated with, endorsed by, or authorized by Remington or the website operator.
>
> Scope is limited to publicly accessible website behavior such as navigation, page rendering, links, document availability, responsive layout, accessibility basics, and newsletter/contact form presentation. No weapon operation, weapon performance, ammunition, purchasing, ordering, or sales-system testing is included.

## Project goals / Цели проекта

- Practice writing test plans, checklists, and test cases.
- Evaluate public informational pages and navigation.
- Record reproducible website defects with evidence.
- Build a small UI automation suite for safe, read-only checks.
- Learn to report test results clearly in English and Russian.

## Initial observed site areas / Первоначально обнаруженные разделы

Based on a preliminary review of the public homepage:
- 700 Series
- 870 Series
- Owner's Manuals
- Contact
- Newsletter / launch-update signup
- Accessibility Statement
- Privacy Policy

These are initial observations, not a complete requirements specification. Verify availability during testing.

## Repository structure

```text
remington-arms-qa/
├── README.md
├── docs/
│   ├── test-plan-en.md
│   └── test-plan-ru.md
├── checklists/
│   ├── homepage-en.md
│   └── homepage-ru.md
├── test-cases/
│   ├── test-cases-en.csv
│   └── test-cases-ru.csv
├── bug-reports/
│   └── README.md
├── evidence/
│   └── README.md
└── automation/
    └── README.md
```

## How to use / Как использовать

1. Read the Test Plan.
2. Run the checklist manually in a normal browser session.
3. Execute test cases and record actual results.
4. Create bug reports only for issues that you personally reproduce.
5. Save screenshots in `evidence/` without exposing personal data.
6. Add automation only for stable, public, read-only behavior.

## Test environment / Тестовая среда

Record before execution:
- Date and time:
- Browser and version:
- Operating system:
- Screen resolution:
- Device type:
- Network conditions:
- Website URL:

## Test status legend

- **Not Run** — not executed yet.
- **Pass** — actual result matches expected result.
- **Fail** — actual result differs from expected result.
- **Blocked** — execution cannot continue.
- **Not Applicable** — scenario does not apply.

## Important

Do not submit real personal information to forms. Do not place orders, attempt to access restricted systems, perform load/security testing, or interact with weapon-related operational content. Use only normal public browsing and low-impact checks.
