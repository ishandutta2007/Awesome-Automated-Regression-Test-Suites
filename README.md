# Awesome-Automated-Regression-Test-Suites

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **Postman's plan structure changed in March 2026**, **Testim is now Tricentis Testim**, and **several entries have no usable pricing**.

## The data problems

**Postman's plans changed in March 2026.** Free, Solo, Team, and Enterprise replaced Free/Basic/Professional/Enterprise. **Collection runs are now unlimited on all plans**—the old per-run limits are gone . Monitoring is **$20 per 50,000 requests per team per month** on paid plans . **Do not cite legacy Postman pricing.**

**Testim is now Tricentis Testim.** Software Advice lists **$450/month** starting, with both a free trial and free version available . This is a directory listing, not Tricentis-published.

**Cypress Cloud pricing has a genuine free tier for open source.** The OSS plan includes **5 users, 100,000 test results/month, and parallelization** . Paid Cloud starts at **$75/month** per Vendr . Test results are the metered unit, not test runs or seats.

**Playwright has no paid cloud pricing**—it is an open-source test runner. The only pricing surfaced is a third-party Apify wrapper at **$250 per 1,000 test runs** , which is not Playwright's own product.

**Tricentis Tosca is pricing available upon request** per Software Advice . No figures surfaced.

**Ranorex Studio starts at $650** per Software Advice .

**Ghost Inspector starts at $125/month** per Software Advice .

**mabl's pricing is from Vendr transactions, not vendor-published.** Tier-based **$450–$3,000/month**; mid-market total **$15,000–$40,000/year**; annual contracts typical .

## What the search results actually contain

| Platform | Pricing | Source |
|---|---|---|
| **Postman** | **Monitoring $20/50K requests/team/month**; unlimited collection runs on all plans  | Vendor-published |
| **Katalon Studio Enterprise** | **$229/seat/month**; **$1,000/seat/year for first 3 seats**, $2,199 from 4th seat  | Vendor-published |
| **Testim (Tricentis)** | **$450/month**  | Directory listing |
| **mabl** | **$450–$3,000/month**; **$15K–$40K/year mid-market**  | Vendr benchmarks |
| **Cypress Cloud** | **From $75/month**; **OSS free: 5 users, 100K results/month, parallelization**  | Vendr + vendor docs |
| **Playwright** | **Open source, free**; no paid cloud  | N/A |
| **Tricentis Tosca** | **Available upon request**  | Directory listing |
| **PractiTest** | **$47/user/month** (Team); Corporate min 10 licenses  | Vendor-published |
| **Ranorex** | **$650** starting  | Directory listing |
| **Ghost Inspector** | **$125/month** starting  | Directory listing |

**Open-source projects (usable):**

| Project | License | What it actually does |
|---|---|---|
| **Playwright Test Runner** | Apache 2.0 | Cross-browser E2E testing; built-in test runner, assertions, parallelization, trace viewer |
| **Cypress** | MIT | Browser E2E testing; open-source core, optional Cloud for recording/parallelization |

**No star counts were surfaced** for Playwright or Cypress in these results. Do not invent them.

## What I recommend

**Split into two honest categories:**

**1. SaaS Regression Platforms** (proprietary):
- **Postman** — unlimited collection runs; Monitoring $20/50K requests 
- **Katalon** — Studio Enterprise $229/seat/month, or $1,000/seat/year for first 3 
- **Testim** — from $450/month (directory)
- **mabl** — $450–$3,000/month (Vendr)
- **Cypress Cloud** — from $75/month; OSS free with 100K results 
- **PractiTest** — $47/user/month 
- **Tricentis Tosca** — quote-only 
- **Ranorex** — from $650 (directory) 
- **Ghost Inspector** — from $125/month (directory) 

**2. Open-Source Test Runners**:
- **Playwright** — Apache 2.0, free, cross-browser, built-in runner 
- **Cypress** — MIT, free core, optional Cloud 

**Mark directory listings as indicative**—Testim, Ranorex, Ghost Inspector, and Tosca figures are not vendor-published. **Do not present Vendr's mabl benchmarks as mabl's list price.**

**Flag the metering difference explicitly:** Postman meters monitoring requests , Cypress meters test results , mabl meters by tier , and Katalon meters by seat . A reader comparing costs needs that context.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not cite Postman's pre-March-2026 plans, fabricate Tosca pricing, or present directory listings as vendor-confirmed rates.
