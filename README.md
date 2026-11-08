# Awesome-AI-Test-Failure-RCA-Agent

# Awesome-AI-Test-Failure-RCA-Agent

**Top AI Test Failure RCA Agent (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Root Cause Analysis, Failure Categorization, Flaky Test Detection & Self-Hosted Test Intelligence*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Test Failure RCA Agents**. These tools enable QA and engineering teams to move beyond pass/fail dashboards—automatically correlating logs, screenshots, and history to classify failures as product bugs, automation issues, or environment problems, and suggesting fixes before engineers spend hours digging.



**Examples** include BrowserStack Test Failure Analysis Agent, Sauce Labs Failure Analysis, Datadog CI Visibility, ReportPortal, Allure TestOps, Launchable, SeaLights, Develocity (Gradle Enterprise), Sentry Seer, and Gremlin Foresight (the category leaders in commercial and open-source space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted RCA, failure classification, and open test analytics. **Critical note**: The open-source landscape is anchored by **ReportPortal**—the most mature Apache 2.0 test analytics platform with ML-based Auto-Analyzer for failure reasons , and **CrashLab**—a newer Python library for deterministic replay and divergence detection in AI agent testing . No open-source project matches BrowserStack's one-click RCA with 95% faster analysis or Launchable's predictive test selection, but for self-hosted test intelligence, the options are production-capable.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global software testing and quality engineering market is estimated at **$45B–$50B** (with the dedicated test automation and AI-augmented test intelligence segment valued between **$20B–$28B**, expanding at a 20%+ CAGR). The sector is **moderately fragmented**: while hyperscale observability and enterprise testing incumbents command significant enterprise footprints, no single vendor maintains a winner-take-all monopoly, leaving ample room for specialized AI-native root-cause analysis (RCA), flaky test detection, and test failure intelligence agents.

## SaaS/Hosted Platforms

| Company / Product | Company Size (Valuation / Revenue) | Pricing | Free Tier / Trial Limits | Key Features / RCA Scope | Trade-offs & Limitations |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Datadog CI Visibility** | **~$48B Market Cap** (~$3.43B FY2025 Rev) | **$8 per committer/month** (billed for committers with ≥3 commits/month) | **14-day free trial** with full platform access across connected CI/CD pipelines | Monitors CI/CD pipeline job performance, test failures, and execution traces; integrates with Datadog APM & logs. | CI/CD pipeline monitoring focus rather than deep autonomous test RCA; per-committer costs scale with team size. |
| **BrowserStack Test Failure Analysis Agent** | **$4.0B Valuation** (~$230M+ ARR) | **$299 per user/year** (bundled with Test Reporting & Analytics / Automate Pro plans) | **14-day free trial** (standard sandbox / 100 automated minutes limit; no permanent free tier for AI agent) | One-click automated RCA correlating logs, screenshots, and stack traces; classifies failure categories; AI suggested fixes with natural language follow-up. | FUP caps RCA volume (30 test failures per 1,000 TRA executions/mo; 1,000 failures/mo per parallel session); requires paid subscription. |
| **Sentry Seer** | **$3.0B Valuation** (~$120M+ ARR) | **$40 per active contributor/month** (active = ≥2 PRs merged/month in connected repos; Team tier base from $26/mo) | **14-day free trial** (for GitHub/GitHub Enterprise users; Developer free plan includes 1 user & 5K errors/mo, but excludes Seer) | Autonomous AI debugging agent utilizing runtime context (errors, traces, code diffs, logs) to isolate defects in PRs and production. | Focused on runtime errors and production crashes rather than CI test execution failure logs or end-to-end flaky test suites. |
| **Sauce Labs Failure Analysis** | **~$500M Valuation** (~$92M ARR) | **$199/month** (Live Testing starting tier; Automated Testing starting at $199/month) | **28-day free trial** (capped at 60 total testing minutes, 3 parallel VMs, and 50 Sauce AI queries) | AI-powered error analytics; Sauce Error Reporting for failure diagnosis; links test run failures with live production error telemetry. | Pricing model is rigid for smaller teams; error analytics standalone add-ons require additional configuration. |
| **Develocity (Gradle Inc.)** | **~$160M Valuation** (~$40M ARR) | **~$700 per developer/year** (annual contract, typically minimum 10–25 developer seats) | **30-day free trial** (custom evaluation environment with dedicated engineer support using real build data) | Build and test toolchain observability; flaky test detection; build caching acceleration; failure analytics across Gradle, Maven, and Bazel. | Specialized for build-tool pipelines (Gradle/Maven/Bazel) rather than framework-agnostic functional/UI test RCA. |
| **SeaLights (Tricentis)** | **$150M Acquisition** (Acquired by Tricentis; parent val ~$4.5B) | **$10,000/year** (estimated starting baseline; tiered by lines of code / developer seats via custom quote) | **14-day proof-of-concept / evaluation trial** (available via Tricentis sales demo request; no permanent free tier) | Test Impact Analysis (TIA); test gap analytics identifying untested code paths; PR quality gates showing changed code test status. | Preventive/predictive test impact analysis rather than post-run root cause diagnostic agent for failed tests. |
| **Gremlin Foresight** | **~$150M Valuation** (~$35M ARR) | **$2,500/year** (platform service tiers from ~$200/mo; Foresight AI priced per team under early access) | **30-day free trial** (full platform access with automated reliability testing; no credit card required) | Autonomous reliability testing agent; simulates failure modes, diagnoses root cause failures, generates code fix diffs, and re-runs to verify. | Geared toward chaos engineering and architectural resilience rather than standard unit/integration CI test triage. |
| **Launchable (CloudBees)** | **$13M Venture Funding** (Acquired by CloudBees; parent val ~$1.0B) | **$12,000/year** (Mars team plan baseline; pay-as-you-go usage-based tiers available) | **Permanent Free Tier ("Moon Plan")** (limited to **1 developer/user**; includes basic ML test session insights and predictive selection) | Machine learning predictive test selection; dynamic test subset optimization; flaky test entropy tracking and duration metrics. | Focuses on optimizing which tests to run prior to execution, rather than explaining the root cause of an unexpected failure. |
| **Allure TestOps (Qameta Software)** | **~$15M Valuation** (~$5M ARR) | **$39 per user/month** (Cloud tier, billed annually; on-premise from $30/user/mo) | **14-day free trial** (fully functional cloud workspace, 60 GB combined storage, 2 MB max test result file size; no credit card required) | Centralized test operations; defect linking; regex & rule-based failure clustering; MCP server (v26.1.1, 13 tools) for automated triage. | Failure grouping relies primarily on pattern matching and regex classification rather than autonomous LLM-driven root cause reasoning. |



## Open-Source GitHub Projects



- **ReportPortal**

  **AI-powered test automation dashboard** (Apache 2.0) — **the most mature open-source test analytics and failure analysis platform**, with **1,700+ companies** including **40+ Fortune 500** using it, processing **85M+ launches/year** . **Features**: **Real-time analytics**—investigate failure reasons immediately after test completion; **Machine Learning Auto-Analyzer**—analyzes failure reasons based on ML, detecting patterns and predicting future results; **AI-assisted failure triage**—assists manual review of logs and new failure patterns; **Automated Quality Gates**—decision-making for release pipelines; **Dashboards & History**—visualize trends and detect patterns . **Tech stack**: Java, Docker/Kubernetes . **Deploy**: Self-hosted (Apache 2.0, Docker/K8s) or cloud. **Trade-off**: **Report-first platform with ML labels**—not an autonomous agent; requires test result ingestion; UI can feel dated compared to SaaS platforms . **Best for**: teams wanting a proven, self-hosted test analytics platform with ML-based failure classification—especially those already using ReportPortal for test reporting.



- **CrashLab**

  **Deterministic replay and divergence detection for AI agents** (PyPI) — **the most focused open-source tool for diagnosing AI agent test failures**, addressing a gap that traditional test RCA tools miss . **Features**: **Records every LLM and tool call**—normalizes OpenAI and Anthropic conversations to stable request hashes; redacts API keys, auth headers, and token-like strings before writing; stores SQLite index plus JSONL cassettes per run . **Strict offline replay**—re-runs recorded entry point with every LLM and tool call served from cassette; no API key, no network; tools never run (side_effects=True tools cannot fire); matches by step order plus normalized hash; raises DivergenceError with step, differing fields, and diff . **Fork at step N with patch**—re-runs with steps before N from cassette and step N onwards live, with typed patches (SystemPromptPatch, ToolResultPatch, ModelParamPatch); side_effects=True tools never run live . **Outcome oracles**—`@crashlab.check("agent-name")` functions determine pass/fail; runtime checks emit typed findings (step_repetition, tool_error_streak, bad_tool_args, suspicious_tool_result, budget, length_cutoff) . **Tech stack**: Python . **Deploy**: `pip install crashlab`; local store `.crashlab/` . **Trade-off**: **AI agent testing only**—not for traditional test suites; newer project with limited validation. **Best for**: developers testing AI agents wanting deterministic replay and divergence diagnosis—especially those building agentic workflows where failures are non-deterministic and hard to reproduce.



### Additional Strong Open-Source Options



- **No mature open-source equivalent to BrowserStack's one-click RCA exists.** BrowserStack, Sauce Labs, Launchable, SeaLights, Develocity, Sentry Seer, and Gremlin Foresight are proprietary. **ReportPortal** provides ML-based failure classification but not autonomous RCA agents. **CrashLab** addresses AI agent testing, not traditional CI failures. For production-grade autonomous RCA, commercial platforms are required.



**Frameworks for building custom systems**: **ReportPortal** provides the test analytics and ML classification foundation; **CrashLab** provides deterministic replay for AI agent failures. **Neither matches BrowserStack's one-click RCA with 95% faster analysis or Launchable's predictive test selection.**



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Test failure RCA platforms handling test data and application telemetry must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "one-click RCA agent" vs. "failure analytics platform" vs. "predictive test selection" vs. "AI agent replay" distinction is critical.** **BrowserStack Test Failure Analysis Agent** is a **one-click RCA agent**—it analyzes failed tests, categorizes failures, and recommends fixes with natural language follow-up . **Sauce Labs Failure Analysis, Datadog CI Visibility, and ReportPortal** are **failure analytics platforms**—they provide dashboards and ML classification but not autonomous agent-style RCA . **Launchable and SeaLights** are **predictive test selection**—they optimize what to run, not diagnose failures after the fact . **CrashLab** is **AI agent replay**—it diagnoses non-deterministic failures in AI agents . **Sentry Seer** is **runtime error debugging**—not test failures . **Choose based on whether you need autonomous RCA, analytics dashboards, test selection, agent replay, or runtime debugging.**

- **BrowserStack's Fair Usage Policy limits analysis to 30 failures per 1,000 TRA executions/month**—or **1,000 per parallel/month** on Automate/App Automate . **For high-volume test suites, model your failure rate against these limits** .

- **Sauce Labs' pricing is noted as inflexible** by reviewers, challenging for smaller organizations . **Error Reporting as a standalone add-on should be evaluated if production defect rate justifies it** .

- **Launchable starts at $12,000/year** and provides **predictive test selection, not RCA**—it tells you which tests to run, not why one failed . **Do not confuse test selection with failure diagnosis.**

- **SeaLights is test impact analysis, not RCA**—it identifies which tests to run based on code changes and flags untested code . **The trade-off**: dynamic analysis prevents failures; it does not diagnose them.

- **Sentry Seer is for runtime errors, not test failures.** It uses production error context to debug issues—not CI test suite failures . **The trade-off**: $40/active contributor/month for unlimited use is attractive for production debugging, but it is not a test RCA tool .

- **ReportPortal is the most mature open-source test analytics platform**—Apache 2.0, 1,700+ companies, 85M+ launches/year, with ML Auto-Analyzer for failure classification . **The trade-off**: report-first with ML labels; not an autonomous agent; requires test result ingestion.

- **CrashLab is the only open-source tool for diagnosing AI agent test failures**—deterministic replay, divergence detection, and typed patches . **The trade-off**: AI agent testing only; newer project with limited validation. **For teams building agentic workflows where failures are non-deterministic, it fills a real gap.**

- Self-hosted open-source solutions require proper infrastructure (Java/Docker for ReportPortal, Python for CrashLab), security hardening, and ongoing maintenance. **Test failure data includes application logs and stack traces**—ensure your deployment meets your organization's security and compliance requirements before ingesting production test results.



---



**Made for QA engineers, test automation leads, and organizations building transparent test intelligence solutions.**

Let's make AI Test Failure RCA Agents more open, data-driven, and debugging-friendly.
